---
layout: default
---


<h1 class="headline">{{site.title}}</h1>

Our community, and this site, are a work in progress. <3

{% for post in site.posts %}
  <h3>
    <a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a>
  </h3>
{% endfor %}


# here are our cupcakes:

{% for x in site.cupcakes %}
  <a href="{{x.url | prepend: site.baseurl}}">{{x.title}}</a>
{% endfor %}


# here are our cookies:

{% for x in site.cookies %}
  <a href="{{x.url | prepend: site.baseurl}}">{{x.title}}</a>
{% endfor %}