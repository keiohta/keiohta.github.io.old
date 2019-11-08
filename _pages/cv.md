---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
Education
======
* B.S. in Aerospace Engineering, Tokyo Institute of Technology, 2015
* M.S. in Aerospace Engineering, Tokyo Institute of Technology, 2017
* 日本語テスト

Work experience
======
* 11/2013 ~ 6/2016: Internship
  * [AxelSpace](https://www.axelspace.com/)

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
