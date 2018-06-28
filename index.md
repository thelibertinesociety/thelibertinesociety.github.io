---
title: The Libertine Society
layout: default                 # options are `default`, `post`, `opinion`
permalink: /
published: true
allow_others_to_edit: false     # display the "think you can say it better?" link at the bottom of the file.
allow_comments: false           # displays the `Disqus` comment thingy.
---


<h1 class="headline">{{site.title}}</h1>

Our community, and this site, are a work in progress. <3


## Documents

{% for x in site.documents %}
* <a href="{{x.url | prepend: site.baseurl}}">{{x.title}}</a>
{% endfor %}


... these files aren't uploaded yet ...

* How the writing process works (not written)
* The Consent Talk (v1 exists)
* Code of Conduct (v1 exists)



## here are the "blog style" posts

{% for post in site.posts %}
  <h3>
    <a href="{{post.url | prepend: site.baseurl}}">{{post.title}}</a>
  </h3>
{% endfor %}

<!--
# here are our cupcakes:

{% for x in site.cupcakes %}
  <a href="{{x.url | prepend: site.baseurl}}">{{x.title}}</a>
{% endfor %}


# here are our cookies:

{% for x in site.cookies %}
  <a href="{{x.url | prepend: site.baseurl}}">{{x.title}}</a>
{% endfor %}
-->
