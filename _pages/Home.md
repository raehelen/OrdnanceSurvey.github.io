---
title: "Products"
layout: single
permalink: /
author_profile: true

feature_row:
  - image_path: /assets/images/OSMM_Topography_Layer.jpg
    alt: "Topography Image"
    title: "OS MasterMap Topography"
    excerpt: "Most detailed and accurate view of Great Britain's landscape – from roads to fields, to buildings and trees and more."
    url: "https://github.com/raehelen/OS-MasterMap-Topography"
    btn_label: "GitHub" 
    btn_class: "btn--primary" 
feature_row2:
  - image_path: /assets/images/zoomstack.PNG
    alt: "Zoomstack Image"
    title: "OS Open Zoomstack"
    excerpt: "A comprehensive vector basemap showing coverage of Great Britain from a national level, right down to street detail."
    url: "#test-link"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/VectorMap Local.PNG
    alt: "VM Local Image"
    title: "OS VectorMap Local"
    excerpt: "A highly-detailed, customisable street-level map - showing fences, building outlines, paths and street names."
    url: "#test-link"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/OSMM_Greenspace.jpg
    alt: "Greenspace Image"
    title: "OS Open Greenspace"
    excerpt: "Britain’s most comprehensive Open dataset of urban and rural greenspaces."
    url: "#test-link"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/highways.PNG
    alt: "Highways Image"
    title: "OS MasterMap Highways Network"
    excerpt: "The next generation of road mapping with an authoritative single view of the whole road network."
    url: "#test-link"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row6:
  - image_path: /assets/images/os-basemap-styles.gif
    alt: "OS Maps API"
    title: "OS Maps API"
    excerpt: "Working examples of how to use the OS Maps API, a RESTful API based on the OS datasets."
    url: "https://github.com/OrdnanceSurvey/OS-Maps-API"
    btn_label: "GitHub"
    btn_class: "btn--primary"    
---

<select id="select-anchor" onChange="window.location.hash=this.value">
		<option value="">Select Product</option>
		<option value="fr_1">OS MasterMap Topography</option>
	 	<option value="fr_3">OS VectorMap Local</option>
		<option value="fr_2">OS Open Zoomstack</option>
		<option value="fr_4">OS Open Greenspace</option>
	 	<option value="fr_5">OS MasterMap Highways Network</option>
		<option value="fr_6">OS Maps API</option>
</select>
	

	
<div id="fr_1"></div>{% include feature_row id="feature_row" type="left" %}
<div id="fr_2"></div>{% include feature_row id="feature_row2" type="left" %}
<div id="fr_3"></div>{% include feature_row id="feature_row3" type="left" %}
<div id="fr_4"></div>{% include feature_row id="feature_row4" type="left" %}
<div id="fr_5"></div>{% include feature_row id="feature_row5" type="left" %}
<div id="fr_6"></div>{% include feature_row id="feature_row6" type="left" %}
