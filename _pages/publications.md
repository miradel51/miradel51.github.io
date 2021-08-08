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
* __Mieradilijiang Maimaiti__，Yang Liu，Huanbo Luan，Maosong Sun， "Unsupervised Domain Adaptation for Neural Machine Translation"，__Computer Patent for Invention__，Authorization number: CN 107038159 A; China Patent Application No: **2017**10139214.0，__Authorized__；
* Maosong Sun, __Mieradilijiang Maimaiti__，Yang Liu，Huanbo Luan， "The Training Method for Neural Machine Translation"，__Computer Patent for Invention__，Authorization number: CN 109117483 B; China Patent Application No：**2018**10845896.1，__Authorized__；

Preprint
======
* **Mieradilijiang Maimaiti**, Yang Liu*, Yuanhang Zheng, Gang Chen, Kaiyuhuang Hunag, Ji Zhang, Huanbo Luan, and Maosong Sun. Segment, Mask, and Predict: Self-supervised Word Segmentation. In Proceedings of the 2021 conference on YYY, 2021.
* Yuanhang Zheng, Zhixing Tan, Meng Zhang, **Mieradilijiang Maimaiti**, Huanbo Luan, Maosong Sun, and Yang Liu*. Self-Supervised Quality Estimation for Machine Translation. In Proceedings of the 2021 conference on YYY, 2021.
