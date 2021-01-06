---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-publications.html %}
{% endfor %}



## All publications
### International conference

1. **Kei Ota**, Devesh K. Jha, Tadashi Onishi, Asako Kanezaki, Yusuke Yoshiyasu, Yoko Sasaki, Toshisada Mariyama, Daniel Nikovski, “Deep Reactive Planning in Dynamic Environments”, CoRL2020. [arXiv](https://arxiv.org/abs/2011.00155).
1. **Kei Ota**, Yoko Sasaki, Devesh K Jha, Yusuke Yoshiyasu, Asako Kanezaki, “Efficient Exploration in Constrained Environments with Goal-Oriented Reference Path”, IROS2020. [arXiv](https://arxiv.org/abs/2003.01641).
1. **Kei Ota**, Tomoaki Oiki, Devesh K. Jha, Toshisada Mariyama, Daniel Nikovski, “Can Increasing Input Dimensionality Improve Deep Reinforcement Learning?”, ICML2020. [arXiv](https://arxiv.org/abs/2003.01629).
1. **Kei Ota**, Devesh K. Jha, Tomoaki Oiki, Mamoru Miura, Takashi Nammoto, Daniel Nikovski, Toshisada Mariyama, “Trajectory Optimization for Unknown Constrained Systems using Reinforcement Learning”, IROS2019. [arXiv](https://arxiv.org/abs/1903.05751).
1. **Kei Ota**, Takehiko Koike, Yoichi Yatsu, and Saburo Matunaga, "On-board Satellite Imagery Classification using Convolutional Neural Networks," 31st International Symposium on Space Technology and Science, 2017-n-10, Matsuyama, Japan, June 3-9, 2017.
1. Yuhei Kikuya, Masanori Matsushita, Masaya Koga, **Kei Ota**, Yuki Hayashi, Takehiko Koike, Toshiki Ozawa, Yoichi Yatsu, and Saburo Matunaga ,"Fault Tolerant Circuit Design for Low-cost and Multi-Functional Attitude Sensor Using Real-time Image Recognition," *31st International Symposium on Space Technology and Science*, 2017-f-093, Matsuyama, Japan, June 3-9, 2017.
1. Yoichi Yatsu, Nobuyuki Kawai, Masanori Matsushita, Shota Kawajiri, Kyosuke Tawara, **Kei Ota**, Masaya Koga, Saburo Matunaga, Shin'ichi Kimura. What we learned from the Tokyo Tech 50 kg-satellite “TSUBAME”, Small Satellite Conference 2017, Small Satellite Conference, 2017.
1. **Kei Ohta**, Masaya Koga, Sota Suzuki, Kazuyoshi Miyasato, Shota Kawajiri, EuGene Kim and Saburo Matunaga, "Proposal and Results of an Automatic Operation System for Nano Satellites Using Multiple Ground Stations", 30th International Symposium on Space Technology and Science, 2015-j-19, Kobe, Japan, July 6-10, 2015.
1. Kurita Shin, Ohuchi Haruka, Arimoto Makoto, Yatsu Yoichi, Kawai Nobuyuki, **Ota Kei**, Koga Masaya, Kim EuGene, Tawara Kyosuke, Suzuki Souta, Miyasato Kazuyoshi, Nagasu Takashi, Kawajiri Shouta, Matsushita Masanori, Matunaga Saburo, Moriyama Nagahisa, Kimura Shin'ichi, TSUBAME team. Development of a micro-satellite TSUBAME for X-ray polarimetry of GRBs, 2014 Fermi Symposium, 2014 Fermi Symposium proceedings, 2015.

### Domestic conference

1. 小林卓矢，澤健太郎，角武憲，**太田佳**，山内尚久，"Q-Learning を用いた無線メッシュネットワークの通信性能評価"，信学技報，2019．
1. 俵京佑，針田聖平，河尻翔太，松下将典，吉井健敏，**太田佳**，古賀将哉，渡邉輔祐太，菊谷侑平，林雄希，小池毅彦，新谷勇介，谷津陽一，河合誠之，松永三郎，"50kg級技術実証衛星「ひばり」－形状可変姿勢制御と重力波対応天体観測"，第17回宇宙科学シンポジウム，P-147，相模原，2017年1月5-6日．
1. 吉井健敏, **太田佳**, 松下将典, 菊谷侑平, 林雄希, 小池毅彦, 新谷勇介, 針田聖平, 小澤俊貴, 下川辺隆史, 谷津陽一, 河合誠之, 松永三郎, "深層学習を用いた新しい衛星姿勢決定方法の開発", 第17回宇宙科学シンポジウム, P-161, 相模原，2017年1月5-6日．
1. **太田佳**，小池毅彦，谷津陽一，松永三郎，"オンボード衛星画像分類のための機械学習手法の比較検討"，第25回スペース・エンジニアリング・コンファレンス，1B1，山口，2016年12月21-22日．
1. 菊谷侑平，河尻翔太，松下将典，俵京佑，**太田佳**，古賀将哉，渡邉輔祐太，林雄希，小池毅彦，新谷勇介，松永三郎，"東工大 松永研究室 小型衛星開発プログラム 2016"，University Space Engineering Consortium Workshop (UNISEC-WS 2016)，東京，2016年12月10-11日．
1. **太田佳**，谷津陽一，松永三郎，"深層学習を用いた軌道上実時間衛星画像分類"，第60回宇宙科学技術連合講演会，JSASS-2016-4628，4G10，函館，2016年9月6-9日．
1. 谷津 陽一, 吉井 健敏, 針田 聖平, 村木 雄太郎, 河合 誠之, 佐久間 惇一, HyunJin Jung, 井上 中順, 篠田 浩一, 下川辺 隆史, **太田 佳**. 突発天体観測用天文台全球リレーのための気象モニターの開発, 天文学会, 天文学会予稿集, p. 210, Sep. 2016.
1. 谷津陽一，吉井健敏，村木雄太郎，針田聖平，**太田佳**，松永三郎，下川辺隆史，"深層学習を応用した革新的姿勢センサの実証"，第60回宇宙科学技術連合講演会，JSASS-2016-4616，4F12，函館，2016年9月6-9日.
1. 松下将典，河尻翔太，鈴木聡太，俵京佑，宮里和良，**太田佳**，古賀将哉，渡邉輔祐太，栗田真，有元誠，谷津陽一，森山永久，木村真一，松永三郎，"50kg級衛星TSUBAMEプロジェクトの総合報告－開発と軌道上運用からの教訓－"，第16回宇宙科学シンポジウム，P-059，相模原，2016年1月6-7日．
1. 渡邉輔祐太，**太田佳**，古賀将哉，宮里知良，鈴木聡太，俵京介，河尻翔太，松下将典，近藤尚登，佐々木謙一，松永三郎，"東京工業大学 ISAS/JAXA 松永研究室 活動報告 ～地球・天体観測技術実証衛星「TSUBAME」の総括と次期衛星開発プロジェクト～"，University Space Engineering Consortium Workshop (UNISEC-WS 2015) ，東京，2015年12月5-6日．
1. **太田佳**，"超小型衛星TSUBAMEのC&DH系軌道上運用結果と技術課題", University Space Engineering Consortium Workshop (UNISEC-WS 2015)，東京，2015年12月5-6日．
1. **太田 佳**，古賀 将哉，鈴木 聡太，松永 三郎，"超小型衛星TSUBAMEのC&DH系の軌道上評価と技術課題"，第59回宇宙科学技術連合講演会，JSASS-2015-4358，2I06，鹿児島，2015年10月7-9日．
1. 古賀将哉, 松下将典, 河尻翔太, 長洲孝, 鈴木聡太, 俵京佑, 宮里和良, **太田佳**, 下中淳史, Hao Ting, Kim EuGene, 木村真一, 谷津陽一, 松永三郎, "小型衛星開発プログラム活動報告", 2015年1月6-7日，第15回宇宙科学シンポジウム
1. 松下将典，河尻翔太，長洲孝，宮里知良，鈴木聡太，俵京佑，キムユージン，**太田佳**，古賀将哉，下中淳史，カクテイ，栗田真，森山長久，有元誠，谷津陽一，木村真一，松永三郎，"超小型衛星TSUBAMEのフライトモデル開発とクリティカルフェーズ運用"，5th UNISEC Space Takumi Conference，UNISEC 2014-003，相模原，2014年12月26日．
1. **太田佳**，河尻翔太，宮里和良，古賀将哉，谷津陽一，松永三郎，"複数地上局を用いた超小型衛星用自動運用システムの提案", 第23回スペース・エンジニアリング・コンファレンス，E06，羽咋，2014年12月19-20日．
1. 俵京佑，河尻翔太，長洲孝，松下将典，鈴木聡太，宮里和良，**太田佳**，古賀将哉，金柔真，カクテイ，松永三郎，"東工大 ISAS/JAXA 松永研究室 小型衛星プログラム 2014"，University Space Engineering Consortium Workshop (UNISEC-WS 2014)，堺，2014年12月6-7日．
1. **太田佳**，"複数地上局を用いた超小型衛星用自動運用システムの開発"", University Space Engineering Consortium Workshop (UNISEC-WS 2014), 堺，2014年12月6-7日．

## Journal publications

1. 毬山利貞，**太田佳**，"技術解説「強化学習の基礎と実用化に向けた課題」"，映像情報メディア学会誌，2019年3月号．

## Preprint
1. **Kei Ota**, Devesh K. Jha, Diego Romeres, Jeroen van Baar, Kevin A. Smith, Takayuki Semitsu, Tomoaki Oiki, Alan Sullivan, Daniel Nikovski, Joshua B. Tenenbaum, “Towards Human-Level Learning of Complex Physical Puzzles,” arXiv, 2020. [arxiv](https://arxiv.org/abs/2011.07193).