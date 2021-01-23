---
layout: page
subheadline: "Blog"
title: "The Twilight Theater (The Past)"
teaser: "All the world's a stage, and all the men and women merely players. They have their exits and their entrances, and one man in his time plays many parts."
header:
    image_fullwidth: "blog/teller-of-worlds/floor-1-original.png"
    caption: In this world, a single blade can take you anywhere you want to go.
    caption_url: "https://en.wikipedia.org/wiki/Sword_Art_Online"
image:
    thumb:  blog/teller-of-worlds/floor-1-thumb.jpg
    homepage: blog/teller-of-worlds/floor-1-thumb.jpg
categories:
    - blog
tags:
    - reflection
    - social-commentary
author: Ousikai
show_meta: true
comments: true
---

-----

*Fall like a leaf in the wind on the ocean*


*Of blue like your eyes in the twilight theater*


*With symphonies playing in the world without sound*


[*We're given and denied*](https://www.youtube.com/watch?v=B6s3q2pbYYk)

-----

## Latest Blog Posts
<ul>
    {% for post in site.tags.twilight-theater %}
    <div class="row">
      <div class="small-12 columns b60">
        <h2><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
        <p>
          {% if post.image.thumb %}<a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}" title="{{ post.title | escape_once }}"><img src="{{ site.urlimg }}{{ post.image.thumb }}" class="alignleft" width="150" height="150"></a>{% endif %}

          {% if post.meta_description %}{{ post.meta_description | strip_html | escape }}{% elsif post.teaser %}{{ post.teaser | strip_html | escape }}{% endif %}

          <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}" title="{{ site.data.language.read }} {{ post.title | escape_once }}"><strong>{{ site.data.language.read_more }}</strong></a>
        </p>
      </div><!-- /.small-12.columns -->
    </div><!-- /.row -->
    {% endfor %}
</ul>


<!-- [![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Q5Q81LOP9) -->
