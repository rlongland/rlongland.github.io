---
title: Team
layout: archive
permalink: /team/
collection: team
classes: narrow
---

<h2 class="archive__subtitle clear:both"> Current members  </h2>
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



<!-- ## Current Members -->

<!-- <ul> -->
<!--     {% for member in site.team %} -->
<!--         <li> -->
<!--             <a href="{{ member.url }}">{{ member.title }}</a> -->
<!--         </li> -->
<!--     {% endfor %} -->
<!-- </ul> -->


<!-- ## Jekyll Serif -->

<!-- <div class="row well"> -->
<!--     {% assign teams = site.team | where: "promoted", empty | sort: "weight" %} -->
<!--     {% for team in teams %} -->
<!--         <div class="col-4 col-md-4 mb-1"> -->
<!--             <div> -->
<!--                 <img width="100" height="100" alt="{{ team.title }}" class="img-fluid pull-left" src="{{ team.image | relative_url }}" /> -->
<!--                 <h3><a href="{{ team.url | relative_url }}">{{ team.title }}</a></h3> -->
<!--                 <p class="team-description">{{ team.position }}</p> -->
<!--             </div> -->
<!--         </div> -->
<!--     {% endfor %} -->
<!-- </div> -->

<!-- ## Recreate Longland site -->

<!-- <div class="row well"> -->
<!--     {% assign teams = site.team | where: "promoted", empty | sort: "weight" %} -->
<!--     {% for team in teams %} -->
<!--         <div class="col-md-4 col-sm-8 col-xs-10"> -->
<!--         <div class="thumbnail well"> -->
<!-- 	    <img src="/assets/images/team/richard-longland.jpg" width="100" alt="Richard" class="img-responsive thumbnail"> -->
<!-- 	    <div> -->
<!--             <H3>Professor Richard Longland   -->
<!--             <small>Assistant Professor</small></H3> -->
<!--         </div> -->
<!--         </div> -->
<!--         </div> -->
<!--     {% endfor %} -->
<!-- </div> -->

<!-- ## Lex code -->

<!-- <div class="well"> -->
<!-- {% for member in site.team reversed %} -->
<!-- 	{% if member.alumni != true and member.sidekick != true %} -->
<!--     {% cycle 'add rows': '<div class="row">', '<\!-- two -\->', '<\!-- three -\->' %} -->
<!--         <div class="col-md-4"> -->
<!-- 			<div class="media"> -->
<!--   				<a class="pull-left" href="{{ site.baseurl }}{{ member.url }}"> -->
<!--     				<img width=160 class="mr-3" src="{{ site.baseurl }}{{ member.image }}"> -->
<!--   				</a> -->
<!--  			 	<div class="media-body"> -->
<!--     				<div class="head mb-1"><a href="{{ site.baseurl }}{{ member.url }}" class="off">{{ member.title }}</a></div> -->
<!--     				<p class="note">{{ member.position }}</p> -->
<!--   				</div> -->
<!-- 			</div> -->
<!-- 			<div class="bigspacer"></div> -->
<!-- 			<div class="bigspacer"></div> -->
<!--         </div> -->
<!--     {% cycle 'close rows': '', '', '</div>' %} -->
<!--     {% endif %} -->
<!-- {% endfor %} -->
<!-- {% cycle 'close rows': '', '</div>', '</div>' %} -->
<!-- </div> -->
