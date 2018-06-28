---
layout: default
permalink: /cupcakes/
published: true
---

{{site.title}}

We are in the cupcakes section of our site.

here are our cupcakes:

{% for x in site.cupcakes %}
* [{{x.title}}]({{x.url | prepend: site.baseurl}})
{% endfor %}
