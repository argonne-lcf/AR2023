---
layout: page

theme: cyan
permalink: features

title: Features
intro: "With the launch of new supercomputing and AI resources and capabilities, the ALCF is enabling pioneering research at the intersection of simulation, big data analysis, and machine learning."
---


<div class="teasers">

{% assign features = site.data.nav-config.toc | where: "title", "Features" %}
{% for entry in features[0].subfolderitems %}
{% assign feature = site.pages | where: 'permalink', entry.url %}


<div class="teaser">
  <a href="/{{ entry.url }}">
  	<div class="image-wrapper">
  		<div><img src="/assets/images/{{ feature[0].hero-img-source }}"></div>
  		<div class="hover-scrim"></div>
  	</div>
  	<div class="content-wrapper">
  		<h3>{{ entry.page }}</h3>
  		<p>{{ feature[0].intro }}</p>
  	</div>
  </a>
</div>

{% endfor %}

</div>

