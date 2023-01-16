---
layout: splash
permalink: /
header:
  overlay_image: /assets/images/header.svg
title: 'ReiseNavet'
tagline: 'Mobility as a Service'
feature_row:
  - image_path: /assets/images/wiki.svg
    alt: "wiki image"
    title: "MaaS wiki"
    excerpt: "Wiki with information about MaaS topics."
    url: "/maas/intro/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - image_path: /assets/images/results.svg
    alt: "results image"
    title: "Results"
    excerpt: "Results from the project"
    url: "/maas/results"
    btn_class: "btn--primary"
    btn_label: "More info"
  - image_path: /assets/images/team.svg
    alt: "about image"
    title: "About ReiseNavet"
    excerpt: "ReiseNavet is a Norwegian research project..."
    url: "/about"
    btn_class: "btn--primary"
    btn_label: "Learn More"
    
---

{% include feature_row id="feature_row" %}

## News from the project
{% for post in site.posts limit:2 %}
{% capture notice-2 %}
#### [{{post.title}}]({{post.url}})
{{post.excerpt}}
{% endcapture %}
<div class="notice--primary">{{ notice-2 | markdownify }}</div>
{% endfor %}

[More news](/news){: .btn .btn--primary}
