---
layout: default
title: Home
permalink: /
---

<div class="bodycontent">
<p> Lastest Post </p>

{% assign post = site.posts.first %}
<h2> {{ post.title }} </h2>
<p> {{ post.content | truncatewords:75 }} <a href="{{ post.url }}"> read more...
</a> </p>



<h2> <a href="/_pages/faq.md>">FAQ</a> </h2>