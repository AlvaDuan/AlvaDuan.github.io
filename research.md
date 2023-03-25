---
layout: page
permalink: /research/
title: Research
pubs:

    - title:   "Underemployment Trap"
      author:  "with Paul Jackson"
      journal: "c"
      note:    ""
      year:    ""
      url:     "https://www.dropbox.com/s/j5dszovqzv7j5mv/Underemployment_Trap_20230223.pdf?dl=0"
      doi:     
      image:   
      media:
        - name: 
          url:  



---

## Working Paper

{% assign thumbnail="left" %}

{% for pub in page.pubs %}
{% if pub.image %}
{% include image.html url=pub.image caption="" height="100px" align=thumbnail %}
{% endif %}
[**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})<br />
{{pub.author}}<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} *{{pub.year}}* {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}
{% if pub.media %}<br />Media: {% for article in pub.media %}[[{{article.name}}]({{article.url}})]{% endfor %}{% endif %}

{% endfor %}
