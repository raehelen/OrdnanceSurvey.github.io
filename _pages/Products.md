---
title: "Products"
layout: single
permalink: /products/
author_profile: true

feature_row:
  - image_path: /assets/images/OSMM_Topography_Layer.jpg
    id: "fr_1"
    alt: "Topography Image"
    title: "OS MasterMap Topography"
    excerpt: 'Most detailed and accurate view of Great Britain's landscape – from roads to fields, to buildings and trees and more.'
    url: "#test-link"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/zoomstack.PNG
    id: "fr_2"
    alt: "Zoomstack Image"
    title: "OS Open Zoomstack"
    excerpt: 'A comprehensive vector basemap showing coverage of Great Britain from a national level, right down to street detail.'
    url: "#test-link"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/VectorMap Local.PNG
    id: "fr_3"
    alt: "VM Local Image"
    title: "OS VectorMap Local"
    excerpt: 'A highly-detailed, customisable street-level map - showing fences, building outlines, paths and street names.'
    url: "#test-link"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/OSMM_Greenspace.jpg
    id: "fr_4"
    alt: "Greenspace Image"
    title: "OS Open Greenspace"
    excerpt: 'Britain’s most comprehensive Open dataset of urban and rural greenspaces.'
    url: "#test-link"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/highways.PNG
    id: "fr_5"
    alt: "Highways Image"
    title: "OS MasterMap Highways Network"
    excerpt: 'The next generation of road mapping with an authoritative single view of the whole road network.'
    url: "#test-link"
    btn_label: "GitHub"
    btn_class: "btn--primary"
---

<select id="select-anchor" onChange="window.location.hash=this.value">
		<option value="">Search Product</option>
		<option value="#fr_1">OS MasterMap Topography</option>
	 	<option value="#fr_3">OS VectorMap Local</option>
		<option value="#fr_2">OS Open Zoomstack</option>
		<option value="#fr_4">OS Open Greenspace</option>
	 	<option value="#fr_5">OS MasterMap Highways Network </option>
</select>
	
	
{% include feature_row id="feature_row" type="left" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="left" %}
{% include feature_row id="feature_row4" type="left" %}
{% include feature_row id="feature_row5" type="left" %}


