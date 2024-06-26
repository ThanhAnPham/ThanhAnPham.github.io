---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find a more up-to-date list of my publications in
<a href="https://scholar.google.com/citations?user=_ZJ9X0QAAAAJ&hl=fr&authuser=1"> <img src="https://scholar.google.se/favicon-png.ico" style="width:1em;margin-right:.2em;" alt="Google Scholar icon">Google Scholar</a>, 
<a itemprop="sameAs" content="https://orcid.org/0000-0001-6231-2569
" href="https://orcid.org/0000-0001-6231-2569
" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.2em;" alt="ORCID iD icon">orcid.org</a>,
<a href="https://www.researchgate.net/profile/Thanh-an_Pham"><img src="https://c5.rgstatic.net/m/426351313275430/images/favicon/favicon.ico" style="width:1em;margin-right:.2em;">Research Gate</a>

{% include base_path %}

Preprints
--------------
{% for post in site.publications reversed %}
	{% if post.category contains 'preprint' %}
		{% include archive-single.html %}
	{% endif %}
{% endfor %}

Journals
--------------
{% for post in site.publications reversed %}
	{% if post.category contains 'journal' %}
		{% include archive-single.html %}
	{% endif %}
{% endfor %}

Proceedings
--------------
{% for post in site.publications reversed %}
	{% if post.category contains 'proceeding' %}
		{% include archive-single.html %}
	{% endif %}
{% endfor %}

Abstracts
--------------
{% for post in site.publications reversed %}
	{% if post.category contains 'abstract' %}
		{% include archive-single.html %}
	{% endif %}
{% endfor %}

<!--

Journals
--------------

{% for post in site.publication reversed %}
	{% include archive-single.html %}
{% endfor %}

Proceedings
------------------

{% for post in site.proceeding reversed %}
	{% include archive-single.html %}
{% endfor %}

Abstracts
--------------

{% for post in site.abstract reversed %}
	{% include archive-single.html %}
{% endfor %}
-->
