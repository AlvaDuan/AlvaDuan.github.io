---
layout: page
permalink: /research/
title: Research
pubs:

    - title:   "Underemployment Trap"
      author:  "with Paul Jackson"
      journal: 
      note:   
      year:   
      url:     "https://www.dropbox.com/s/j5dszovqzv7j5mv/Underemployment_Trap_20230223.pdf?dl=0"
      doi:     
      image:   

workpaper:

    - title:   "The Procyclicality of Wage Loss"
      author:  
      journal: 
      note:   
      year:   
      url:   
      doi:     
      image:   



---

## Working Paper

{% assign thumbnail="left" %}

{% for pub in page.pubs %}
{% if pub.image %}
{% include image.html url=pub.image caption="" height="100px" align=thumbnail %}
{% endif %}
[{{pub.title}}]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
{{pub.author}}<br />
{{pub.journal}}
{% if pub.note %} ({{pub.note}})
{% endif %} *{{pub.year}}* {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}
{% if pub.media %}<br />Media: {% for article in pub.media %}[[{{article.name}}]({{article.url}})]{% endfor %}{% endif %}

{% endfor %}

## Working in Progress

{% assign thumbnail="left" %}

{% for wp in page.workpaper %}
{% if wp.image %}
{% include image.html url=wp.image caption="" height="100px" align=thumbnail %}
{% endif %}
[{{wp.title}}]({% if wp.internal %}{{wp.url | prepend: site.baseurl}}{% else %}{{wp.url}}{% endif %})<br />
{{wp.author}}<br />
{{wp.journal}}
{% if wp.note %} ({{wp.note}})
{% endif %} *{{wp.year}}* {% if wp.doi %}[[doi]({{wp.doi}})]{% endif %}
{% if wp.media %}<br />Media: {% for article in wp.media %}[[{{article.name}}]({{article.url}})]{% endfor %}{% endif %}

{% endfor %}
