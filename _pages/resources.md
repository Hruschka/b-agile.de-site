---
title: "Ressourcen"
layout: splash
permalink: /resources
header:
    overlay_color: "#d7ecf8"
    overlay_filter: rgba(15, 80, 180, 0.6)
    overlay_image: /images/splash/resources.jpg
    caption: "[**Unsplash**](https://unsplash.com/)"

excerpt: "Laden Sie sich hier Vorträge, Artikel und Bücher herunter"

vorträge:
- title: "Vorträge"
  image_path: "/images/resources/42.png"
  url: "/resources/lectures"
  btn_label: "Vorträge herunterladen"
  btn_class: btn--primary
  excerpt: "Laden Sie sich hier Vorträge herunter."

artikel:
- title: "Artikel"
  image_path: "/images/resources/42.png"
  url: "/resources/articles"
  btn_label: "Artikel herunterladen"
  btn_class: btn--primary
  excerpt: "Laden Sie sich hier Artikel herunter."

bücher:
- title: "Bücher"
  image_path: "/images/resources/42.png"
  url: "/resources/books"
  btn_label: "Bücher herunterladen"
  btn_class: btn--primary
  excerpt: "Laden Sie sich hier Bücher herunter."
---

{% include feature_row id="vorträge" type="left"%}
{% include feature_row id="artikel" type="right"%}
{% include feature_row id="bücher" type="left"%}