---
title: "Tools"
layout: single
permalink: /tools/
author_profile: true

feature_row:
  - image_path: /assets/images/os-basemap-styles.gif
    alt: "OS Maps API"
    title: "OS Maps API"
    excerpt: "Working examples of how to use the OS Maps API, a RESTful API based on the OS datasets."
    url: "https://github.com/OrdnanceSurvey/OS-Maps-API"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/GDVeg.png
    alt: "GeoDataViz Toolkit"
    title: "GeoDataViz Toolkit"
    excerpt: "A set of resources that will help you communicate your data effectively through the design of compelling visuals."
    url: "https://github.com/OrdnanceSurvey/GeoDataViz-Toolkit"
    btn_label: "GitHub" 
    btn_class: "btn--primary" 
feature_row3:
  - image_path: /assets/images/VectorMap Local.PNG
    alt: "OS OpenSpace iOS SDK"
    title: "OS OpenSpace iOS SDK"
    excerpt: "Software development kit providing access to a number of mapping layers and gazetteer lookups to create free and commercial mobile applications with our data."
    url: "https://github.com/OrdnanceSurvey/openspace-ios-sdk"
    btn_label: "GitHub"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/OSMM_Greenspace.jpg
    alt: "OS OpenSpace Android SDK"
    title: "OS OpenSpace Android SDK"
    excerpt: "Software development kit providing access to a number of mapping layers and gazetteer lookups to create free and commercial mobile applications with our data."
    url: "https://github.com/OrdnanceSurvey/openspace-android-sdk"
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
    
---

<select id="select-anchor" onChange="window.location.hash=this.value">
		<option value="">Select Tool</option>
		<option value="fr_1">OS MasterMap Topography</option>
	 	<option value="fr_3">OS VectorMap Local</option>
		<option value="fr_2">OS Open Zoomstack</option>
		<option value="fr_4">OS Open Greenspace</option>
	 	<option value="fr_5">OS MasterMap Highways Network </option>
</select>
	

	
<div id="fr_1"></div>{% include feature_row id="feature_row" type="left" %}
<div id="fr_2"></div>{% include feature_row id="feature_row2" type="left" %}
<div id="fr_3"></div>{% include feature_row id="feature_row3" type="left" %}
<div id="fr_4"></div>{% include feature_row id="feature_row4" type="left" %}
<div id="fr_5"></div>{% include feature_row id="feature_row5" type="left" %}
