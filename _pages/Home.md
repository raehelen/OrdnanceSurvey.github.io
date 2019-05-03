---
title: "Repositories"
layout: single
permalink: /
author_profile: true

header:
  overlay_color: "#fff"
  overlay_filter: "0.5"
excerpt: "GitHub repositories containing code samples, stylesheets, demos and more for our major products."

feature_row:
  - image_path: /assets/images/OS-MasterMap-Topography.png
    alt: "Topography Image"
    title: "OS MasterMap Topography"
    excerpt: "Most detailed and accurate view of Great Britain's landscape – from roads to fields, to buildings and trees and more."
    url: "https://github.com/OrdnanceSurvey/OS-Master-Map-Topography"
    btn_label: "GitHub" 
    btn_class: "btn--primary" 
feature_row2:
  - image_path: /assets/images/OS-Open-Zoomstack.png
    alt: "Zoomstack Image"
    title: "OS Open Zoomstack"
    excerpt: "A comprehensive vector basemap showing coverage of Great Britain from a national level, right down to street detail."
    url: "https://github.com/OrdnanceSurvey/OS-Open-Zoomstack"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/OS-VectorMap-Local.png
    alt: "VM Local Image"
    title: "OS VectorMap Local"
    excerpt: "A highly-detailed, customisable street-level map - showing fences, building outlines, paths and street names."
    url: "https://github.com/OrdnanceSurvey/OS-VectorMap-Local"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/OS-Open-Greenspace.png
    alt: "Greenspace Image"
    title: "OS Open Greenspace"
    excerpt: "Britain’s most comprehensive Open dataset of urban and rural greenspaces."
    url: "https://github.com/OrdnanceSurvey/OS-Open-Greenspace"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/OS-MasterMap-Highways-Network.png
    alt: "Highways Image"
    title: "OS MasterMap Highways Network"
    excerpt: "The next generation of road mapping with an authoritative single view of the whole road network."
    url: "https://github.com/OrdnanceSurvey/OS-MasterMap-Highways-Network"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row6:
  - image_path: /assets/images/OS-Maps-API.png
    alt: "OS Maps API"
    title: "OS Maps API"
    excerpt: "Working examples of how to use the OS Maps API, a RESTful API based on the OS datasets."
    url: "https://github.com/OrdnanceSurvey/OS-Maps-API"
    btn_label: "GitHub"
    btn_class: "btn--primary"    
feature_row7:
  - image_path: /assets/images/vectormap-district-hackney.jpg
    alt: "OS VectorMap District"
    title: "OS VectorMap District"
    excerpt: "Show enough detail to give the lie of the land while avoiding overwhelming detail with this customisable map."
    url: "https://github.com/OrdnanceSurvey/OS-VectorMap-District"
    btn_label: "GitHub"
    btn_class: "btn--primary"    
feature_row8:
  - image_path: /assets/images/terrain-50-place3.jpg
    alt: "OS Terrain 50"
    title: "OS Terrain 50"
    excerpt: "Visualise simple landscapes in 3D and bring your geographic analysis to life."
    url: "https://github.com/OrdnanceSurvey/OS-Terrain-50"
    btn_label: "GitHub"
    btn_class: "btn--primary"    
---

<select id="select-anchor" onChange="window.location.hash=this.value" class="Product">
		<option value="">Select Product</option>
		<option value="fr_1">OS MasterMap Topography</option>
	 	<option value="fr_3">OS VectorMap Local</option>
		<option value="fr_2">OS Open Zoomstack</option>
		<option value="fr_4">OS Open Greenspace</option>
	 	<option value="fr_5">OS MasterMap Highways Network</option>
		<option value="fr_6">OS Maps API</option>
		<option value="fr_7">OS VectorMap District</option>
		<option value="fr_8">OS Terrain 50</option>
</select>
	

	
<div id="fr_1"></div>{% include feature_row id="feature_row" type="left" %}
<div id="fr_2"></div>{% include feature_row id="feature_row2" type="left" %}
<div id="fr_3"></div>{% include feature_row id="feature_row3" type="left" %}
<div id="fr_4"></div>{% include feature_row id="feature_row4" type="left" %}
<div id="fr_5"></div>{% include feature_row id="feature_row5" type="left" %}
<div id="fr_6"></div>{% include feature_row id="feature_row6" type="left" %}
<div id="fr_7"></div>{% include feature_row id="feature_row7" type="left" %}
<div id="fr_8"></div>{% include feature_row id="feature_row8" type="left" %}
