---
title: "Portfolio"
profile: true
permalink: "portfolio/"
---
The following page shows some of the Android apps that I've coded and designed as a freelancer or parttime job 

{% for p in site.apps %}
<div class="app_wrapper">
	<h3 class="app_title">{{ p.title }}</h3>
	<img class="app_icon" src="{{ p.logo }}" width="100" alt="{{ p.title }}"/>
	<p class="app_description"> {{ p.description }}</p>
</div> 
{% endfor %}  

<p>And many other apps, this listing will only keep the last 5 apps</p>