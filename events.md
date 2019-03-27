---
layout: page
title: Events
permalink: /events
---
Here is the list of past and future events:

{% for post in site.categories.events %}
* # {{post.title}}
{{post.content}}
<br>
{% endfor %}
<hr>


Here you can suggest an activity for the society that you believe will benefit others.


### Here is an excellent tool for making documents

<a href="https://www.overleaf.com?r=24632a1b&rm=d&rs=b">Online LaTeX Editor Overleaf</a>
