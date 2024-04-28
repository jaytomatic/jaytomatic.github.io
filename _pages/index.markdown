---
layout: default
title: Home
permalink: /
---

<h2> Lastest Post </h2>

{% assign post = site.posts.first %}
<a href="{{ post.url }}"> {{ post.title}}
</a>


### [FAQ](/faq/)