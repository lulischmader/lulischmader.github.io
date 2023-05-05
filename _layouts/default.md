---
title: "{% if page.title %}{{ page.title }} – {% endif %}{{ site.name }} – {{ site.description }}"
---

{% seo title=false %}

{% include meta.html %}

[//]: # (Stylesheets)
[//]: # (-----------------------------------------------------------------------)
[//]: # (Primary Stylesheet)
[//]: # (-----------------------------------------------------------------------)
<link rel="stylesheet" type="text/css" href="{{ site.baseurl }}/assets/style.css" />

[//]: # (Alternate Stylesheet)
[//]: # (-----------------------------------------------------------------------)
<link rel="alternate" type="application/rss+xml" title="{{ site.name }} - {{ site.description }}" href="{{ site.baseurl }}/feed.xml" />

[//]: # (Canonical URL)
[//]: # (-----------------------------------------------------------------------)
<link rel="canonical" href="{{ site.url }}{{ page.url }}" />

[//]: # (Theme Color)
[//]: # (-----------------------------------------------------------------------)
<meta name="theme-color" content="#000000">

[//]: # (Favicon)
[//]: # (-----------------------------------------------------------------------)
<link rel="icon" type="image/png" sizes="32x32" href="{{ site.baseurl }}/images/favicon-32x32.png">

{% include analytics_head.html %}

# {{ site.name }}

{% comment %}
Navigation Links
{% endcomment %}

* [Home]({{ site.baseurl }}/)
* [About]({{ site.baseurl }}/about)
* [Projects]({{ site.baseurl }}/projects)
* [Talks]({{ site.baseurl }}/talks)
* [Teaching]({{ site.baseurl }}/teaching)
* [CV]({{ site.baseurl }}/cv)
* [Contact]({{ site.baseurl }}/contact)

{{ content }}

---

[//]: # (Footer)
[//]: # (-----------------------------------------------------------------------)
[//]: # (SVG Icons)
[//]: # (-----------------------------------------------------------------------)
{% include svg-icons.html %}

@2023 Luli Schmader. Powered by Jekyll and Github, a fork of Reverie.

{% include analytics.html %}
