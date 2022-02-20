---
layout: page
subheadline: "Tempest Crossing"
title: "The Grand Challenge"
teaser: "A call from the future threatens to tear down our boring yesterdays."
header:
    image_fullwidth: "blog/the-grand-challenge/HEADER-EDIT.png"
    caption: "How can tomorrow even exist for us if you won't fight for yourself today?"
    caption_url: "https://www.youtube.com/watch?v=jNGNaD5qx00"
image:
    thumb:  blog/the-grand-challenge/THUMB-EDIT.png
    homepage: blog/the-grand-challenge/RAW-EDIT.png
categories:
    - blog/
tags:
    - ongoing-stories
author: Ousikai
show_meta: true
comments: true
---
A man trudges along through life with an unremarkable past and no clear future. Everyday is the dreaded cycle of despair as he gets up, goes to work, returns home, and repeats the tasks endlessly. His only saving grace is virtual reality, where even just for a brief moment, he can pretend to be somewhere else. 

Someone else. 

Someone who matters and does things that matter. 

Fleeting as it may, the salvation lasts just as long as the battery lasts, and once the screen turns black, he comes back again to reality and faces himself. Even this too was slowly losing its glimmer, until one day he receives a peculiar invitation for a new VR experience he does not remember signing up for…

<ul>
    {% for post in site.tags.the-grand-challenge %}
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