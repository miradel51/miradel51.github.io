---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=NaN6LowAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Patent
======
* __Mieradilijiang Maimaiti__, Yang Liu, Huanbo Luan and Maosong Sun, "Unsupervised Domain Adaptation for Neural Machine Translation", __Computer Patent for Invention__, Authorization number: CN 107038159 A; China Patent Application No: **2017**10139214.0, __Authorized__；
* Maosong Sun, __Mieradilijiang Maimaiti__, Yang Liu and Huanbo Luan, "The Training Method for Neural Machine Translation", __Computer Patent for Invention__, Authorization number: CN 109117483 B; China Patent Application No：**2018**10845896.1, __Authorized__；

Preprint
======
* Yang Liu, __Mieradilijiang Maimaiti__, Huanbo Luan and Maosong Sun, "The System and Method for Low-Resource Neural Machine Translation Based on Data Augmentation", __Computer Patent for Invention__; China Patent Application No: **2021**10xxxxxxx, __Under Review__；
