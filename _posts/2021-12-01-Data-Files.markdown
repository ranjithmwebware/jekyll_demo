---
layout: "data"
title: "Data Files"
---
<h2 style="color: blue">This is from data files</h2>
<h3 style="color: red">
{% for person in site.data.people %}
    {{ person.name }} , {{ person.occupation }}<br>
{% endfor %}</h3>