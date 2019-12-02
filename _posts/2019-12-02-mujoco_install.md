---
title: 'MuJoCo install tips'
date: 2019-12-02
permalink: /posts/rl/mujoco/
excerpt: "MuJoCo installに関するTips"
tags:
  - rl
---

# MuJoCo Install Tips

MuJoCoインストールでたまにこけるのでTipsを随時追加する

## Mac

### ld: library not found for -lglfw.3 (2019/12/2)

GLFW (Graphic Library Flamework)が見つからないというエラー

```bash
$ pip install mujoco-py
Collecting mujoco-py
...
  ld: library not found for -lglfw.3
  collect2: error: ld returned 1 exit status
  error: command '/usr/local/bin/gcc-9' failed with exit status 1
  ----------------------------------------
  ERROR: Failed building wheel for mujoco-py
  Running setup.py clean for mujoco-py
Failed to build mujoco-py
ERROR: Could not build wheels for mujoco-py which use PEP 517 and cannot be installed directly
```

brewでglfwをインストール

```bash
$ brew install glfw
```

インストール先のパスを確認。

```bash
$ find /usr/local -name libglfw*
/usr/local/lib/libglfw.dylib
/usr/local/lib/libglfw.3.dylib
/usr/local/lib/libglfw.3.3.dylib
/usr/local/Cellar/glfw/3.3/lib/libglfw.dylib
/usr/local/Cellar/glfw/3.3/lib/libglfw.3.dylib
/usr/local/Cellar/glfw/3.3/lib/libglfw.3.3.dylib
```

**ライブラリパスを指定して**mujoco-pyをインストール

```bash
$ LIBRARY_PATH=/usr/local/lib pip install mujoco-py
...
Successfully built mujoco-py
Installing collected packages: mujoco-py
Successfully installed mujoco-py-2.0.2.9
```

動作確認：エラーが起きなければOK

```bash
$ python -c "import mujoco_py"
```