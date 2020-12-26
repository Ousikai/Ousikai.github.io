---
permalink: /tempest-crossing/
layout: page
title: "Tempest Crossing"
sitemap: false
header:
    image_fullwidth: "header-search.jpg"
    caption: Argo the information broker of Sword Art Online
    caption_url: "https://en.wikipedia.org/wiki/Sword_Art_Online"
comments: true
---

### A New Storm Wakes on the Horizon
Coming soon...

<ul>
    {% for post in site.categories.tempest-crossing %}
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