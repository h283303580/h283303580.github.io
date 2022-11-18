---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
**Huang, C.**, Mao, Yu. Ultrathin Crosslinking Vapor Deposition Encapsulation of Dexamethasone for Controlled Release from Three-dimensional Devices (In preparation).

**Huang, C.**, Mao, Yu. One-step and Substrate-independent Vapor Deposition of Superhydrophobic Coating with Hierarchical Roughness to Reduce Bio-adhesion (In preparation).

**Huang, C.**, Zhu, M., Mao, Yu. Solventless Polymer-Grafted Mesh for Rapid and Efficient Oil-Water Separation (submitted to ACS Applied Polymer Materials).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
