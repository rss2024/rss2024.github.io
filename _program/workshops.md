---
layout: page
title: Workshops
description: Workshop times, venues, and details.
days: ['Mon', 'Fri']
priority: 9
invisible: false
published: true
---


Workshops will take place across two days of the conference on July 10 and July 14, 2023. Each workshop is organized as a semi-independent event, and has a unique schedule reflecting the planned activities, constraints and preferences of the organizers. Please check the workshop websites for more details on their particular schedules. 

For instructions and directions at the venue, please check out the [venue page]({{ site.baseurl }}/attending/atvenue/). For virtual attendance please find more information [here]({{ site.baseurl }}/attending/virtual/)
{% for day in page.days %}
<div style="display: block; width: 100%; height: 20px;"></div>
{% if day == 'Mon' %}
### Monday, July 10 
#### (Full or half day)
{% assign innerdays = "10th, 12-13, tbd" | split: ", " %}
{% elsif day == 'Fri' %}
### Friday, July 14 
#### (Half day)
{% assign innerdays = "14th, tbd" | split: ", " %}
{% endif %}

<table class="table table-striped table-workshop" id="{{ day }}ID">
  <thead>
    <tr>
      <th width="7%" align="center">ID</th>
      <th width="15%" align="center">Location</th>
      <th width="50%">Title</th>
      <th width="28%">Organizers</th>
    </tr>
  </thead>
  <tbody>
    {% for innerday in innerdays %}
    {% for workshop in site.data.workshops %}
    {% if workshop.date contains innerday %}

    <tr>
      <td><span style="font-weight:bold; color: #3a3946;"> {{ workshop.external_id }} </span></td>
      <td>{{ workshop.location }} &nbsp; <span style="font-size:smaller; line-height:0.9; display:block;">{{ workshop.note }}</span> </td>
      <td>
        <a href="{{ workshop.url }}">
          {{ workshop.title }}
        </a>
      </td>
      <td style="font-size:smaller;">
        {{ workshop.organizers | replace: ',', '<br/>' | truncatewords: 7, "&nbsp;<button type='button' class='collapsible' style='border:none;background:none;font-size:smaller;color:#222299;'>...more&gt;</button>"}}
      <div class="content" style="display:none; padding-top:20px;">
        {{ workshop.organizers | replace: ',', '<br/>'}}
      </div>
      </td>     
    </tr>
    {% elsif workshop.date contains "?" and innerday contains 'tbd' %}
    <tr>
      <td>{{ workshop.external_id }}</td>
      <td><span style="color:#aaa;font-size:smaller;text-align:center;">TBD</span></td>
      <td>
        <a href="{{ workshop.url }}">
          {{ workshop.title }}
        </a>
      </td>
      <td style="font-size:smaller;">
        {{ workshop.organizers | replace: ',', '<br/>' | truncatewords: 7, "&nbsp;<button type='button' class='collapsible' style='border:none;background:none;font-size:smaller;color:#222299;'>...more&gt;</button>"}}
      <div class="content" style="display:none; padding-top:20px;">
        {{ workshop.organizers | replace: ',', '<br/>'}}
      </div>
      </td>     
    </tr>
    {% endif %}
    {% endfor %}
    {% endfor %}
  </tbody>
</table>
{% endfor %}

<span style="color:white; font-size:50px;">&nbsp;</span><br>
<span style="color:white; font-size:50px;">&nbsp;</span><br>
<span style="color:white; font-size:50px;">&nbsp;</span><br>
<span style="color:white; font-size:50px;">&nbsp;</span><br>
<span style="color:white; font-size:50px;">&nbsp;</span><br>


<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    this.style.display = "none";
    var content = this.nextElementSibling;
    //if (content.style.display === "block") {
    //  content.style.display = "none";
    //} else {
    //  content.style.display = "block";
    //}
    var c = this.parentElement;
    c.innerHTML = content.innerHTML;
    });
}
</script>

