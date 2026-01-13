---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<sup>*</sup> indicates that authors made equal contributions

# Peer-reviewed papers

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Preprints

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

# PhD thesis

**Joe Hilton** (2017). &quot;Stochastic approaches to infectious disease in heterogeneous populations.&quot; PhD thesis, University of Warwick. <br/>
<a href="http://wrap.warwick.ac.uk/147970/" target="_blank"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a>
<a href="http://wrap.warwick.ac.uk/147970/1/WRAP_Theses_Hilton_2019.pdf" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a>
