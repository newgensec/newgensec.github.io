---
title: "GrunnSec Research Group - News"
layout: textlay
excerpt: "GrunnSec Research Group"
sitemap: false
permalink: /allnews.html
---
<div markdown="0" width="10%" id="carousel" class="carousel slide" data-ride="carousel" data-interval="5000" data-pause="hover" align="center">
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">

        <div class="item">
            <img class="slider_img" src="{{ site.url }}{{ site.baseurl }}/images/slider/memoryexp.png" alt="Slide 1" />
        </div>  
        <div class="item">
            <img class="slider_img" src="{{ site.url }}{{ site.baseurl }}/images/slider/biagio.jpg" alt="Biagio" />
        </div>
        <div class="item active">
            <img  class="slider_img" src="{{ site.url }}{{ site.baseurl }}/images/slider/sapienza.webp" alt="Slide 2" />
        </div>
    </div>

  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
<h1 class="sapienza-text"> News </h1>

{% for article in site.data.news %}
<p><b>{{ article.date }}</b> <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
