---
layout: data
title: "static files"
permalink: "images"
---
{{ page.title }}
<h2 style=" color: red"> This Is The Static File Page  </h2>
<h3 style="color: blue">
{% for file in site.static_files %}
    {% if file.image %}
        <img src="{{file.path}}" alt="{file.name}" height="400px" width="300px">
    {% endif %}
{% endfor %}