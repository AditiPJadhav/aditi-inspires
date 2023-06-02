---
layout: default
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/logo.png
excerpt: >
  Codeset search and get more information.<br />
feature_row:
  - image_path: /assets/images/codeset.png
    alt: "customizable"
    title: "Writing"
    excerpt: "Writings"
    url: "/writing/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/logo.svg
    alt: "fully responsive"
    title: "Travel"
    excerpt: "Travel"
    url: "/travel/"
    btn_class: "btn--primary"
    btn_label: "Learn more"   
---

{% include feature_row %}

{% if site.search == true %}
      <div class="search-content">
        {% include search/search_form.html %}
      </div>
    {% endif %}
