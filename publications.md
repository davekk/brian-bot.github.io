---
layout: page
title: publications
description: Davies Kiamenyi's publications
permalink: /publications/
---

***
***
<br>

This is a personally curated list of my publications. Other sources include [Google Scholar](https://scholar.google.com/citations?user=87X0SmcAAAAJ&hl=en), and [ORCID](https://orcid.org/0000-0002-6320-3740).

{% for pub in site.data.publications %}
- {{ pub.authors }}. *{{ pub.title }}*. <u>{{ pub.journal }}</u>. {{ pub.year }}. [doi:{{ pub.doi }}](https://doi.org/{{ pub.doi }})
{% endfor %}
***
***
