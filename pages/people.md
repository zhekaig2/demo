---
layout              : page
show_meta           : false
title               : "Getting Started in 10 Steps"
subheadline         : "A Step-by-Step Guide"
teaser              : "This step-by-step guide helps you to customize Feeling Responsive to your needs."
header:
   image_fullwidth  : "header_homepage_13.jpg"
permalink           : "/getting-started/"
---
<div class="people">
<div class="jumbotron">

<h1>Our research group</h1>

</div>

	{% include group-members.html %}
	
	<h3>Older group photos:
	<a href="{{ site.baseurl }}/img/group-photo-large-1.jpg">[1]</a>
	<a href="{{ site.baseurl }}/img/2014group2.jpg">[2]</a>
	<a href="{{ site.baseurl }}/img/group-photo-2011.jpg">[3]</a> 
	<a href="{{ site.baseurl }}/tracks/">[4]</a>
	<a href="{{ site.baseurl }}/img/group-photo-simpsons.jpg">[5]</a> 
	<a href="{{ site.baseurl }}/img/group-photo-alma-mater.jpg">[6]</a></h3>

	<div name="name="previous-group-members"></div>	
	<h1 class="category-title">Previous group members</h1>
	
	{% include previous-group-members.html %}

</div>
