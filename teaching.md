---
layout: default
title: Teaching
---

<div class="col-4 ml-4">
<div class="mb-4">
In 2022 I'll be taking on an exciting new challenge working as a teaching fellow at the University of Auckland. My teaching will focus on software requirements, and development methodologies.<br>
</div>

<h3 class="text-primary">Courses</h3>
{% for item in site.data.teaching %}
  <div style="padding-bottom: 10px"> <b>{{item.name}}</b><br>
  <i>{{item.place}}</i><br>
  {{item.years}}</div>
{% endfor %}

</div>