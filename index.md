---
layout: default
title: aai4r
---

<link rel="stylesheet" href="/assets/css/member.css">
<link rel="stylesheet" href="/assets/css/index.css">
<script type="text/javascript" src="/assets/js/index.js"></script>

<div class="bk-container">
  <img class="bk-img" src="/assets/images/main.png">
  <h2 class="bk-header">
    <i> Adaptive AI for Robots! </i>
  </h2>
</div>

<!--<div class="update content-container">
  <h1 class = "content-title">
    Updates
  </h1>
  {% for news in site.data.updates %}
  <p class="content-item news news-{{ forloop.index0 }}">
    <span id="date">{{ news.date }}</span>
    {{ news.content }}
  </p>
  {% endfor %}
  <p class="content-item showMore">
    <span id="more" onclick="showMore()">More</span>
<span id="noMoreContext" style="display:none;color: #cccccc;"><br>No more news available.</span>
  </p>
</div>-->

<div class="about content-container">
  <h2 class = "content-title">
    What is AAI4R Project?
  </h2>
  <p class="content-item">
   AAI4R project aims to develop adaptive intelligence technologies for service robots.
  </p>
</div>

<div class="people content-container">
  <h2 class = "content-title">
    People
  </h2>
  <div class="content-item">
    {% for person in site.data.people %}
      <div class="member">
        <div class="member-profile">
          <img class="member-profile" src="{{person.src}}">
        </div>
        <div class="member-info member-name">
          {{ person.name }}
        </div>
        <div class="member-info member-position">
          {{ person.role }}
        </div>
        <div class="member-info member-position">
          {{ person.affiliation }}
        </div>
      </div>
    {% endfor %}
  </div>
</div>
