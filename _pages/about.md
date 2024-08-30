---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I received my Ph.D. in Computer Science from SUNY Binghamton, under the supervision of [Prof.Yifan Zhang](https://www.binghamton.edu/computer-science/people/profile.html?id=zhangy). During my Ph.D. studies, I also collaborated on a project with [Prof.Kanad Ghose](https://www.binghamton.edu/computer-science/people/profile.html?id=ghose). 

My current research interests lie in mobile systems, embedded systems, operating systems and virtualization, with a special emphasis on security. I am particularly passionate about designing and implementing robust security mechanisms using virtulization techniques for resource-constrained mobile environments. My goal is to fortify these mobile systems against a broad spectrum of attackes.
    
# Publications

<style style="text/css">
  	.hoverTable{
		width:85%; 
		border-collapse:collapse; 
		border: 0px;
	}
	.hoverTable td{ 
		padding:7px; border:#4e95f4 0px solid;
	}
	/* Define the default color for all the table rows */
	.hoverTable tr{
		background: #ffffff;
	}
	/* Define the hover highlight color for the table row */
    .hoverTable tr:hover {
          background-color: #f7f7f7;
    }
</style>

<table class="hoverTable">
  <col style="width:75%">
  <col style="width:25%">
  {% for post in site.publications reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}
</table>
