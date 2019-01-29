---
layout: page
title: Events
permalink: /events
---
Here is the list of past and future events:

{% for post in site.categories.events %}
* **{{post.title}}**
{{post.content}}
<br>
{% endfor %}

<hr>
Here you can suggest an activity for the society that you believe will benefit others.
