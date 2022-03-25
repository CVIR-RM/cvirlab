---
title: "CIVR-RM - Pictures"
layout: piclay
excerpt: "CVIR-RM -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [CVIR](#cvir), [Journal Club](#journal-club), [Online Meetings](#online-meeting)


## CVIR

<^_^>: # Timelapse of our lab assembling:
<iframe width="640" height="430" max-width:100% src="https://www.bilibili.com/video/BV1Jv411p7Uz?spm_id_from=333.337.search-card.all.click" scrolling="yes" bordder="0" frameborder="0" allowfullscreen="true"></iframe>

#### Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_cvir %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

## Journal club
From the [journal club](http://www.cvirlab.com/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/jc2.jpg" width="40%">
</figure>


## online meeting
From the [online meeting](http://www.cvirlab.com/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/olme1.png" width="40%">
</figure>
