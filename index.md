---
title: The Libertine Society    # page title
layout: default                 # options are `default`, `post`, `opinion`
permalink: /                    # optional. If commented out, will use the file path as the url.
published: true                 # Is page visible to people?
allow_others_to_edit: false     # display the "think you can say it better?" link at the bottom of the page.
allow_comments: false           # displays the `Disqus` comment thingy.
---


<h1 class="headline">{{site.title}}</h1>

Our community, and this site, are a work in progress. <3


## Documents

{% for x in site.documents %}
* [{{x.title}}]({{x.url | prepend: site.baseurl}})
{% endfor %}


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
