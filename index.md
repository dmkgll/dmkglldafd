---
layout: default
date: 25 October 2023
---

<style>img{max-width:500px;} </style>

![dm](/img/homepage.jpeg)

<pre>A Felon Under Various Laws</pre>

---

The ten most recent things are listed below:

{% for post in site.posts limit 10 %}
  * {{ post.date | date: "%m-%d-%Y" }}: [{{ post.title }}]({{ post.url }})
{% endfor %}

This site is divided into the following top-level categories:

<ul>
  <li style="font-size:20px;"><a href="/about">Everything</a></li>
<li style="font-size:20px;"><a href="/about">About</a></li>
  <li style="font-size:20px;"><a href="/links">Links</a></li>
    <li style="font-size:20px;"><a href="/aoe2">Video Games</a></li>
   <li style="font-size:20px;"><a href="/aoe2">Cryptocurrency, Cypherpunks, etc.</a></li>
  <li style="font-size:20px;"><a href="/aoe2">Books</a></li>
  <li style="font-size:20px;"><a href="/aoe2">Miscellaneous</a></li>
</ul>
