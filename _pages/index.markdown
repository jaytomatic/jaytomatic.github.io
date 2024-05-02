---
layout: default
title: Home
permalink: /
---

<div class="bodycontent">
<h2> Lastest Post </h2>

{% assign post = site.posts.first %}
<a href="{{ post.url }}"> {{ post.title}}
</a>
</div>


### [FAQ](/faq/)