---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{% include header.html %}

{% include splash-page/hero.html %}

{% include splash-page/intro.html %}

<div id="projects" class="projects sec-pad">


<div class="main-container">
   <h2 class="heading heading-sec heading-sec__mb-bg">
     <span class="heading-sec__main">Projects</span>
     <span class="heading-sec__sub">
         Here are a few of my projects.
     </span>
   </h2>


{% for project in site.data.projects %}
{% include splash-page/project.html project=project %}
{% endfor %}


</div>

</div>