---
layout: single
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/nova_cen_notext_logosm.png
  actions:
    - label: "Contact Me!"
      url: "mailto:richard_longland@ncsu.edu"
excerpt: "Longland Group"
intro: 
   - excerpt: "The Longland research group is committed to diversity and equality. A diverse set of experiences across race, gender, age, religion, and identity helps us unlock the mysteries of the universe in new and unique ways!"
feature_row:
  - image_path: assets/images/EngeView1-feature.png
    alt: "Enge CAD Drawing"
    title: "Research"
    excerpt: "An overview of our research and projects "
    url: "/research/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/Library-feature.jpg
    alt: "library image"
    title: "Publications"
    excerpt: "A list of our publications"
    url: /publications/ 
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/Students_2017-feature.jpg
    title: "Our Team"
    excerpt: "Click here to see who we are!"
    url: "/team/"
classes: wide
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

# Recent News 

See [here](/news/) for more!

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}
