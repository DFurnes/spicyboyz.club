---
layout: default
title: ""

---

<header class="jumbotron subhead" id="overview">
  <center>
    <br /><br /><br />
    <div class="row">
      <h1><img src="logo.gif" title="Spicy Boyz Inc" width="549" height="104" /></h1>
      <p class="lead">Heroes 4 Hire</p>
    </div>
    Your premier source for adventure, intrigue, and large-scale destruction since 1358 DR.
  </center>
</header>

### Adventures
<ul class="adventure-list">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %e, %Y" }}
  </li>
{% endfor %}
</ul>
