---
layout: default
title: MissionNET Radio
---
 
# Welcome to MissionNET Radio
 
**Networking, Exploration, and Testing.**
 
This is a public blog documenting my experiences using professional radios — Motorola MOTOTRBO, Harris, and others — for amateur radio purposes. Content is for educational and informational purposes only.
 
---
 
## Posts
 
{% if site.posts.size > 0 %}
{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
<small>{{ post.date | date: "%B %d, %Y" }}{% if post.tags.size > 0 %} &middot; {{ post.tags | join: ", " }}{% endif %}</small>
 
{{ post.excerpt }}
 
---
{% endfor %}
{% else %}
*No posts yet — check back soon!*
{% endif %}
 
