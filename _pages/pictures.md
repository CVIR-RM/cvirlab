---
title: "CIVR-RM - Pictures"
layout: piclay
excerpt: "CVIR-RM -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [CVIR](#cvir), [Journal Club](#journal-club), [Online Meetings](#online-meeting)


## CVIR

<!---
 # Timelapse of our lab assembling:
--->
#### Visit RMUA2021 in ICRA2021 Xi'An.
<!---
<iframe width="690" height="470" src="player.bilibili.com/player.html?aid=248567251&bvid=BV1Jv411p7Uz&cid=352550304&page=1" scrolling="no" bordder="0" frameborder="0" allowfullscreen="true"></iframe>
--->
<iframe width="720" height="510" src="https://player.bilibili.com/player.html?aid=248567251&bvid=BV1Jv411p7Uz&cid=352550304&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
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
