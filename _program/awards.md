---
layout: page
title: Awards
description: Award details.
priority: 6
invisible: false
published: true
---


Congratulations to the following authors!

## Best Paper Award Finalists

 {% for paper in site.data.rss2023CameraReadyInfo %}
 {% if paper.AwardNom == "BEST" %}

<a class="{{ paper.AwardWinner }}" href="{{ site.baseurl }}/program/papers/{{ paper.PaperIDZeroes
}}/">{{paper.PaperTitle}}</a>
<br>
<i>{{ paper.AuthorNames | replace: ';', ' and ' | replace: '*', ''}}</i>

 {% endif %}
 {% endfor %}


<hr>
 
## Best System Paper Award Finalists

 {% for paper in site.data.rss2023CameraReadyInfo %}
 {% if paper.AwardNom == "BEST SYSTEM" %}

<a class="{{ paper.AwardWinner }}" href="{{ site.baseurl }}/program/papers/{{ paper.PaperIDZeroes
}}/">{{paper.PaperTitle}}</a>
<br>
<i>{{ paper.AuthorNames | replace: ';', ' and ' | replace: '*', ''}}</i>

 {% endif %}
 {% endfor %}


<hr>
 
## Best Student Paper Award Finalists

 {% for paper in site.data.rss2023CameraReadyInfo %}
 {% if paper.AwardNom == "BEST STUDENT" %}

<a class="{{ paper.AwardWinner }}" href="{{ site.baseurl }}/program/papers/{{ paper.PaperIDZeroes
}}/">{{paper.PaperTitle}}</a>
<br>
<i>{{ paper.AuthorNames | replace: ';', ' and ' | replace: '*', ''}}</i>

 {% endif %}
 {% endfor %}


<hr>
 
## Best Demo Paper Award Finalists

 {% for paper in site.data.rss2023CameraReadyInfo %}
 {% if paper.AwardNom == "BEST DEMO" %}

<a class="{{ paper.AwardWinner }}" href="{{ site.baseurl }}/program/papers/{{ paper.PaperIDZeroes
}}/">{{paper.PaperTitle}}</a>
<br>
<i>{{ paper.AuthorNames | replace: ';', ' and ' | replace: '*', ''}}</i>

 {% endif %}
 {% endfor %}

<hr>