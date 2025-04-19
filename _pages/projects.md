---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

You can find most of my projects on <a href="https://github.com/{{ author.github }}"><i class="fab fa-fw fa-github" aria-hidden="true" style="color: black"></i>GitHub</a> or <a href="https://gitlab.crans.org/tjester"><i class="fab fa-fw fa-gitlab" style="color: #ef7d1f;" aria-hidden="true"></i>GitLab</a>

---

This section has not been completed yet...

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}

