---
layout: default
title: Почетна
---

<section id="content">

    {% assign post = site.posts.first %}

    {% include featured_post_preview.html %}
    
    {% for post in site.posts offset:1 %}
        {% include post_preview.html %}
    {% endfor %}

</section>

<section id="friends">
	<h3>Пријатели</h3>
	<a href="http://reggaehr.org/" title="Reggae.hr" style="margin-top: 15px;">
	    <img src="/assets/img/reggaehr.gif" alt="Reggae.hr" />
	</a>
	<a href="http://missidreadvibration.wordpress.com/" title="Miss I Dread Vibration" style="margin-top: 15px; margin-left: 10px;" target="_blank">
	    <img src="/assets/img/missidread.png" alt="Miss I Dread Vibration" />
    </a>
</section>
