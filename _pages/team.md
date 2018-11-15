---
title: "HUSUME - Team"
layout: gridlay
excerpt: "Husume: Team members"
sitemap: false
permalink: /team/
---

# Group Members

{% assign members = site.data.real_team_members %}

<div class="row" id="team_container">

  {% for member in members %}
  
    <div class="col-sm-6 clearfix profile">
      <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
      <h4>{{ member.name }}</h4>
      <i>{{ member.info }}<br><{{ member.email }}><br>{{ member.interests }}</i>


  
    </div>  

  {% endfor %}

</div>
