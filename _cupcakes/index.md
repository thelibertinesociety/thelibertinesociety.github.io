---
layout: default
---
{{site.title}}

We are in the cupcakes section of our site.

here are our cupcakes:

{% for x in site.cupcakes %}
 * <a href="{{x.url | prepend: site.baseurl}}">{{x.title}}</a>
{% endfor %}