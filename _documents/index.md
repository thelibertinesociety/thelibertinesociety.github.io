---
layout: default  # options are `default`, `post`, `opinion`
permalink: /documents/
published: true
allow_others_to_edit: false  # display the "think you can say it better?" link at the bottom of the file.
allow_comments: false  # displays the `Disqus` comment thingy.
---

# {{site.title}}

Here is the documents section of our website!

{% for x in site.documents %}
hello
  - <a href="{{x.url | prepend: site.baseurl}}">{{x.title}}</a>
{% endfor %}
