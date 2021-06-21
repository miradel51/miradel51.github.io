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
  {% include archive-single.html %}
{% endfor %}

Patent
======
* __米尔阿迪力江·麦麦提__，刘洋，栾焕博，孙茂松， “一种基于无监督领域自适应的神经网络机器翻译方法”，计算机_发明专利_，授权号：CN 107038159 A;中国专利申请号：**2017**10139214.0，__已授权__；
* 孙茂松, __米尔阿迪力江·麦麦提__，刘洋，栾焕博， “神经网络机器翻译模型的训练方法和装置” ，计算机_发明专利_，授权号：CN 109117483 B;中国专利申请号：**2018**10845896.1，__已授权__；

Preprint
======
* N/A
