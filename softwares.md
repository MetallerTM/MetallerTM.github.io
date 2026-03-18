---
title: "Softwares"
layout: single
sidebar:
  nav: "sw"
---

<ul style="list-style:none; padding:0;">
    {% for sw in site.softwares %}
    <li style="margin-bottom:1.5em;">
        <img src="{{ sw.logo }}" alt="{{ sw.title }} logo" style="height:auto; width:150px; vertical-align:bottom; margin-right:10px;">
        <a href="{{ sw.url }}"><strong>{{ sw.title }}</strong></a>
        <br>
        <span style="margin-left:50px;">{{ sw.description }}</span>
      </li>
    {% endfor %}
</ul>
