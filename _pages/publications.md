---
title: "Publications"
layout: gridlay
excerpt: "Publications."
sitemap: false
permalink: /publications/
---

Full list of publications of each group member can be found in the [People section](http://vlbigroup.iaa.es/people/).

# Latest Publications

{% for publi in site.data.publist %}

 <strong> {{ publi.title }} </strong> <br />
 <span style="color:grey"> <em>{{ publi.date }},  {{ publi.journal }} </em> </span> <br />
  <em>{{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
