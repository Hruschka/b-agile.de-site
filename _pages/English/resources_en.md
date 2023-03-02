---
title: "Resources"
layout: splash
permalink: /en/resources
header:
    overlay_color: "#d7ecf8"
    overlay_filter: rgba(15, 80, 180, 0.6)
    overlay_image: /images/splash/resources.jpg
    caption: "[**Unsplash**](https://unsplash.com/)"

excerpt: "Download services, talks, articles and books here"

services:
- title: "Services"
  excerpt: "Hier können Sie PDF-Dateien meiner Dienstleistungen herunterladen."
  image_path: "/images/resources/services.jpg"
  image_caption: "Image from [Unsplash](https://unsplash.com)"
  btn_label: "Untersuchung zur 'Lage der Nation'"
  btn_class: btn--primary
  url: "downloads/services/Lage-der-nation.pdf"

vorträge:
- title: "Vorträge"
  image_path: "/images/resources/lectures.jpg"
  url: "/resources/lectures"
  btn_label: "Zu den Vorträgen"
  btn_class: btn--primary
  excerpt: "Hier stehen für Sie verschiedene Vorträge zum Download zur Verfügung."

artikel:
- title: "Artikel"
  image_path: "/images/resources/articles.jpg"
  image_caption: "Image from [Unsplash](https://unsplash.com)"
  url: "/resources/articles"
  btn_label: "Zu den Artikeln"
  btn_class: btn--primary
  excerpt: "Hier stehen für Sie verschiedene Artikel zum Download zur Verfügung."

bücher:
- title: "Bücher"
  image_path: "/images/resources/book.jpg"
  image_caption: "Image from [Unsplash](https://unsplash.com)"
  url: "downloads/books/agile_softwareentwicklung_embedded_real_time_systems_uml.pdf"
  btn_label: "Zum Download"
  btn_class: btn--primary
  excerpt: "Das Buch „Agile Softwareentwicklung für Embedded Real-Time Systems mit der UML“ ist leider nicht mehr im Handel erhältlich. Deshalb hier als Gratis-Download"
---

{% include feature_row id="services" type="right"%}
{% include feature_row id="vorträge" type="left"%}
{% include feature_row id="artikel" type="right"%}
{% include feature_row id="bücher" type="left"%}