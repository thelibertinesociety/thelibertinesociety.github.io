---
title: Documents
layout: default               # options are `default`, `post`, `opinion`
permalink: /documents/        # optional... will use file path if commented out.
published: true
allow_others_to_edit: false   # display the "think you can say it better?" link at the bottom of the file.
allow_comments: false         # displays the `Disqus` comment thingy.
---

# {{site.title}}

Here is the documents section of our website!

{% for x in site.documents %}
  - <a href="{{x.url | prepend: site.baseurl}}">{{x.title}}</a>
{% endfor %}


... these files aren't uploaded yet ...

### How the writing process works (not written)

### TODO - what documents should be written in the future? (v1 exists)

### Governance (v1 exists)

### The Consent Talk (v1 exists)

### Code of Conduct (v1 exists)
