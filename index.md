---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---

sodifjsdofijo
<div class="home">
sdfosijdfo
  {% for project in site.projects %}
    <h2>{{ project.project_title }} </h2>
    <h3>{{ project.technologies }}</h3>
    <p>{{ project.content}}</p>
  {% endfor %}
</div>