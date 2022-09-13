---
title: Publications
layout: archive
permalink: /publications/
author_profile: false
entries_layout: list 
collection: publications
classes: wide
---

For a full list of our publications,  
[click here](https://ui.adsabs.harvard.edu/search/filter_author_facet_hier_fq_author=AND&filter_author_facet_hier_fq_author=author_facet_hier%3A%220%2FLongland%2C%20R%22&fq=%7B!type%3Daqp%20v%3D%24fq_author%7D&fq=%7B!type%3Daqp%20v%3D%24fq_aff%7D&fq_aff=(aff_facet_hier%3A%220%2FNCSU%22%20OR%20aff_facet_hier%3A%220%2FUNCCH%22%20OR%20aff_facet_hier%3A%220%2FUPC%22)&fq_author=(author_facet_hier%3A%220%2FLongland%2C%20R%22)&q=Longland&sort=date%20desc%2C%20bibcode%20desc&p_=0){:.btn .btn--primary}

Note that this page is still under construction  
{: .notice--danger} 


{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}


<!---
<h2 class="archive__subtitle clear:both"> Highlighted Papers  </h2>
<div class="grid__wrapper clear: both">
{% for member in site.team %}
	{% if member.alumni != true and member.sidekick == true %}
        <div class="grid__item">
        <article class="archive__item" itemscope itemtype="https://schema.org/CreativeWork">
            <div class="archive__item-teaser">
                <a href="{{ site.baseurl }}{{ member.url }}">
                <img src="{{ site.baseurl }}{{ member.image }}" alt=""></a>
            </div>
        <h2 class="archive__item-title no_toc" itemprop="headline">
        <a href="{{ site.baseurl }}{{ member.url }}">{{ member.title }}</a> 
        </h2>         <small> {{ member.position }} </small>
        </article>
        </div>
    {% endif %}
{% endfor %}
</div>

<div class="grid__wrapper clear: both">
{% for member in site.team %}
	{% if member.alumni != true and member.sidekick != true %}
        <div class="grid__item">
        <article class="archive__item" itemscope itemtype="https://schema.org/CreativeWork">
            <div class="archive__item-teaser">
                <a href="{{ site.baseurl }}{{ member.url }}">
                <img src="{{ site.baseurl }}{{ member.image }}" alt=""> </a>
            </div>
        <h2 class="archive__item-title no_toc" itemprop="headline">
        <a href="{{ site.baseurl }}{{ member.url }}">{{ member.title }}</a> 
        </h2>         <small> {{ member.position }} </small>
        </article>
        </div>
    {% endif %}
{% endfor %}
</div>

<h2 class="archive__subtitle" style="clear:both"> Alumni </h2>
<div class="grid__wrapper" style="clear:both">
{% for member in site.team reversed %}
	{% if member.alumni == true %}
        <div class="grid__item">
        <article class="archive__item" itemscope itemtype="https://schema.org/CreativeWork">
            <div class="archive__item-teaser">
                <a href="{{ site.baseurl }}{{ member.url }}">
                <img src="{{ site.baseurl }}{{ member.image }}" alt=""> </a>
            </div>
        <h2 class="archive__item-title no_toc" itemprop="headline">
        <a href="{{ site.baseurl }}{{ member.url }}">{{ member.title }}</a> 
        </h2> <small> {{ member.position }} </small>
        </article>
        </div>
    {% endif %}
{% endfor %}
</div>


-->
