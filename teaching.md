---
layout: default
title: Teaching
---


<div class="row">


<div class="mb-4 col-sm-5">
<div class="mb-4">
<h3 class="text-primary">Teaching</h3>
I'm currently working as a professional teaching fellow at the University of Auckland. My teaching focuses on software requirements, working in development teams, and software maintenance and evolution.<br>
</div>

<h3 class="text-primary">Courses</h3>
{% for item in site.data.teaching %}
  <div style="padding-bottom: 10px"> <b>{{item.name}}</b><br>
  <i>{{item.place}}</i><br>
  {{item.years}}</div>
{% endfor %}
</div>

<div class="mb-4 col-sm-6">
 <img class="img-fluid" right="100" src="imgs\uoa.jpg" alt="James Tizard" width="600" 
     >
</div>

</div>
