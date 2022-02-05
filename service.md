---
layout: default
title: Academic Service
---

<div class="row">

<div class="mb-4 col-sm-5">

<!-- <h2 class="text-primary">Journal Board Memberships</h2>
{% for item in site.data.service_journals %}
  <div style="padding-bottom: 10px"><b> {{ item.name }} </b><br>
  {% for entry in item.venues %}
    <i>{{entry.venue}}</i>, {{entry.tenure}}<br>
  {% endfor %}
  </div>
{% endfor %}

<h2 class="text-primary">Executive Committee Memberships</h2>
{% for item in site.data.service_exec %}
  <div style="padding-bottom: 10px"><b> {{ item.name }} </b><br>
  {% for entry in item.venues %}
    <i>{{entry.venue}}</i>, {{entry.tenure}}<br>
  {% endfor %}
  </div>
{% endfor %} -->
<div class="mb-4">
<h3 class="text-primary">Organizing Committee Memberships</h3>
{% for item in site.data.service_oc %}
  <div style="padding-bottom: 10px"><b> {{ item.name}} </b><br>
  {% for entry in item.venues %}
    <i>{{entry.venue}}</i>, {{entry.tenure}}<br>
  {% endfor %}
  </div>
{% endfor %}

<h3 class="text-primary">Program Committee Memberships</h3>
{% for item in site.data.service_pc %}
  <div style="padding-bottom: 10px"><b> {{ item.name}} </b><br>
  {% for entry in item.venues %}
    <i>{{entry.venue}}</i>, {{entry.tenure}}<br>
  {% endfor %}
  </div>
{% endfor %}

<h3 class="text-primary">Reviewing</h3>
{% for item in site.data.service_reviewing %}
  <div style="padding-bottom: 0px">{{item.venue}}</div>
{% endfor %}

</div>
</div>

<div class="mb-4 ml-5 col-sm-6">
 <img class="img-fluid" right="100" src="imgs\service image.PNG" alt="James Tizard" width="450px" 
     >
</div>



</div>