---
layout: page
title: community
description: Brian M. Bot's community activities
permalink: /community/
---

***
***
<br>

I am committed to being an active participant in the open science community. Here is a list of community activities I have been involved with:

{% for comm in site.data.community %}
- **{{ comm.role }}**. *{{ comm.activity }}*. {{ comm.date }}
{% endfor %}

***
***
