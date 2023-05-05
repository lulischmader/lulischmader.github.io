---
title: {% if page.title %}{{ page.title }} – {% endif %}{{ site.name }} – {{ site.description }}
---

[comment]: <> (CSS stylesheet)
<link rel="stylesheet" type="text/css" href="{{ site.baseurl }}/assets/style.css" />

[comment]: <> (RSS feed link)
<link rel="alternate" type="application/rss+xml" title="{{ site.name }} - {{ site.description }}" href="{{ site.baseurl }}/feed.xml" />

[comment]: <> (Canonical URL)
<link rel="canonical" href="{{ site.url }}{{ page.url }}" />

[comment]: <> (Site icon and theme color)
<meta name="theme-color" content="#000000">
<link rel="icon" type="image/png" sizes="32x32" href="{{ site.baseurl }}/images/favicon-32x32.png">

[comment]: <> (Analytics code)
{% include analytics_head.html %}

# {{ site.name }}

- [Home]({{ site.baseurl }}/){% if page.title == "About" %} {% else %}- [About]({{ site.baseurl }}/about){% endif %}
- [Projects]({{ site.baseurl }}/projects)
- [Talks]({{ site.baseurl }}/talks)
- [Teaching]({{ site.baseurl }}/teaching)
- [CV]({{ site.baseurl }}/cv)
- [Contact]({{ site.baseurl }}/contact)

{{ content }}

---

[comment]: <> (SVG icons)
{% include svg-icons.html %}

[comment]: <> (Footer text)
* @2023 Luli Schmader. Powered by Jekyll and Github, a fork of Reverie.

[comment]: <> (Analytics code)
{% include analytics.html %}
