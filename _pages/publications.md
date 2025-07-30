---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!--  * xxx, **Tianyi Fu**, Kai Bu, Chunling Yang, Zhihua Chang, Wenzhi Chen, Zhou Ma, Chongjie Chen, Yongsheng Shen, and Kui Ren, &quot;[MineShark: Cryptomining Traffic Detection at Scale]()&quot;. *in The Network and Distributed System Security Symposium (NDSS) San Diego, California, USA, Feburary 23-28, 2025* (**NDSS 2025**). -->


* Shaoke Xi, **Tianyi Fu**, Kai Bu, Chunling Yang, Zhihua Chang, Wenzhi Chen, Zhou Ma, Chongjie Chen, Yongsheng Shen, and Kui Ren, &quot;[MineShark: Cryptomining Traffic Detection at Scale](https://www.ndss-symposium.org/ndss-paper/mineshark-cryptomining-traffic-detection-at-scale/)&quot;. *in The Network and Distributed System Security Symposium (NDSS) San Diego, California, USA, Feburary 23-28, 2025* (**NDSS 2025**).

* **付添翼**, 席少珂, 卜凯, 任奎, 张帆, &quot;[A virtual currency mining traffic detection method based on deep learning](https://patents.google.com/patent/CN116208356B/en)&quot;(**2023-09-29
Publication of CN116208356B**).

* 吴福康, **付添翼**, 卜凯, 任奎, &quot;[Efficient authentication method, device and readable storage medium for blockchain voting system based on pipeline structure](https://patents.google.com/patent/CN118869179A/en)&quot;(**2024-10-29
Publication of CN118869179A**). 

* **付添翼**, 卜凯,  &quot;[Method for enhancing delay fairness of block chain network order](https://patents.google.com/patent/CN120123424A/en)&quot;(**2025-06-10
Publication of CN120123424A**). 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
