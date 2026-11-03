---
layout: academic
title: Publications
permalink: /publications/
---

<h2>Journal articles</h2>
<ol class="pubs">
{% for pub in site.data.publications %}{% if pub.type == "journal" %}{% include pub.html %}{% endif %}{% endfor %}
</ol>

<h2>Conference papers</h2>
<ol class="pubs">
{% for pub in site.data.publications %}{% if pub.type == "conference" %}{% include pub.html %}{% endif %}{% endfor %}
</ol>

<p class="footnote">* Equal contribution.</p>

<h2>Theses</h2>
<ol class="pubs">
{% for pub in site.data.publications %}{% if pub.type == "thesis" %}{% include pub.html %}{% endif %}{% endfor %}
</ol>
