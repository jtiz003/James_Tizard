---
layout: default
title: Teaching
---
In 2022 I'll be taking on an exciting new challenge working as a teaching fellow at the University of Auckland. My teaching will focus on software requirements, and development methodologies.<br>

<h2 class="text-primary">Courses</h2>
{% for item in site.data.teaching %}
  <div style="padding-bottom: 10px"> <b>{{item.name}}</b><br>
  <i>{{item.place}}</i><br>
  {{item.years}}</div>
{% endfor %}