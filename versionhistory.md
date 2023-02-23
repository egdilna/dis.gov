---
layout: page
title: Protokol verzí portálového engine
---

{% for revize in site.data.versionlist %}
<p>{{ revize.Datum }} (verze {{ revize.Verze }}): {{revize.Popis}}</p>
{% endfor %}