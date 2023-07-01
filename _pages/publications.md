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


[RCBEVD: Radar-Camera Fusion in Bird's Eye View for Detection with Velocity Estimation](https://ias-18.org/wp-content/uploads/2023/05/0050_FI.pdf)
Jia, Yansong; Lee, Christina Dao Wen; Ang Jr, Marcelo H (National University of Singapore, Singapore)
