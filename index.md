---
layout: page
title: Developing in Simplicity
tagline: developing, design
---
{% include JB/setup %}

### Technology I Use
		
	::Programming Langauages			::Design Tools
	 ::Main Weapons						 ::Main Tools
	  :Ruby								  :Inkscape
	  :Python							  :Gimp
	  :PHP								  :Adobe Fireworks
	  :JavaScript						  :Adobe Photoshop
	  :C/C++							  :Adobe Illustrator

#### Under Construction
	

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



