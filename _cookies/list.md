---
layout: default
permalink: /cookies/
published: true
---

{{site.title}}

We are in the cookies section of our site.

here are our cookies:

{% for x in site.cookies %}
* [{{x.title}}]({{x.url | prepend: site.baseurl}})
{% endfor %}
