---
layout: academic
permalink: /
---

## About

I am a Postdoctoral Scholar at Caltech, advised by Prof. Aaron Ames. I received my PhD in Mechanical Engineering at UC San Diego under the supervision of Prof. Jorge Cortés, and a B.Sc. in Mathematics and a B.Sc. in Engineering Physics in 2020 from the Universitat Politècnica de Catalunya, in Barcelona.

My research aims to develop decision-making architectures for autonomous systems  in which safety is a formally certifiable property. To do so, I leverage tools from systems and control theory, optimization, uncertainty quantification, and AI.

<div class="section-head">
<h2>Selected publications</h2>
<a href="{{ '/publications/' | relative_url }}">All publications →</a>
</div>
<ol class="pubs">
{% for pub in site.data.publications %}{% if pub.selected %}{% include pub.html %}{% endif %}{% endfor %}
</ol>

{% if site.data.news.size > 0 %}
<h2>News</h2>
<ul class="news">
{% for item in site.data.news %}<li><span class="date">{{ item.date }}</span><span class="text">{{ item.text }}</span></li>{% endfor %}
</ul>
{% endif %}
