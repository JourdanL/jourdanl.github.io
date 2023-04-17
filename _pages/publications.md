---
layout: publications
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
  -
    title: "Text revision in Scientific Writing Assistance: An Overview."
    url: "https://arxiv.org/pdf/2303.16726.pdf"
    <!---link: "https://github.com/boudinfl/ir-using-kg" --->
    authors: "Léane Jourdan, Florian Boudin, Richard Dufour, Nicolas Hernandez"
    journal: "Proceedings of the 13th International Workshop on Bibliometric-enhanced Information Retrieval (ECIR 2023)"
    date: "Apr 2023"
  -
