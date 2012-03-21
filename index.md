---
layout: page
title: Developing in Simplicity
tagline: developing, design
---
{% include JB/setup %}

### Technology I Use
		
	::Programming Langauages			
	 ::Main Weapons						 
	  :Ruby								  
	  :Python							  
	  :PHP								  
	  :JavaScript						  
	  :C/C++			

	::Design Tools
	 ::Main Tools
	  :Inkscape
	  :Gimp
	  :Adobe Fireworks
	  :Adobe Photoshop
	  :Adobe Illustrator
	  
#### Under Construction
	

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



