---
title: "Adding Teaser Images to 'Minimal-Mistakes' Jekyll Theme Blog"
layout: posts
tagline: ""
header:
    teaser: /assets/images/blog-with-teasers-header.png
---

The [Minimal Mistakes Theme](https://github.com/mmistakes/minimal-mistakes) for Jekyll/Github Pages is great, but the blog view ("archive-single") only displays your posts teaser images in 'Grid View' by default. I want to change that.

# Default 'List View' Behaviour
![](../assets/images/blog-without-teasers.png)

# Improved 'List View' Behaviour
List view now shows your post's 'teaser image' in the list view

![](../assets/images/blog-with-teasers.png)

## How?

In the file `_includes/archive-single.html` you simply add the following liquid commands to the line just before `</article>` 

```markdown
 {% if include.type == "list" and teaser %}
   <div class="archive__item-teaser">
     <img src="{{ teaser | relative_url }}" alt="">
   </div>
 {% endif %}
```

and that is is.

Just in case it isn't obvious where I mean, below is a copy of my entire `_includes/archive-single.html` file:

```markdown
{% if post.header.teaser %}
  {% capture teaser %}{{ post.header.teaser }}{% endcapture %}
{% else %}
  {% assign teaser = site.teaser %}
{% endif %}

{% if post.id %}
  {% assign title = post.title | markdownify | remove: "<p>" | remove: "</p>" %}
{% else %}
  {% assign title = post.title %}
{% endif %}

<div class="{{ include.type | default: 'list' }}__item">
  <article class="archive__item" itemscope itemtype="https://schema.org/CreativeWork">
    {% if include.type == "grid" and teaser %}
    <div class="archive__item-teaser">
      <img src="{{ teaser | relative_url }}" alt="">
    </div>
    {% endif %}
    <h2 class="archive__item-title no_toc" itemprop="headline">
      {% if post.link %}
        <a href="{{ post.link }}">{{ title }}</a> <a href="{{ post.url | relative_url }}" rel="permalink"><i class="fas fa-link" aria-hidden="true" title="permalink"></i><span class="sr-only">Permalink</span></a>
      {% else %}
        <a href="{{ post.url | relative_url }}" rel="permalink">{{ title }}</a>
      {% endif %}
    </h2>
    {% include page__meta.html type=include.type %}
    {% if post.excerpt %}<p class="archive__item-excerpt" itemprop="description">{{ post.excerpt | markdownify | strip_html | truncate: 160 }}</p>{% endif %}
    {% if include.type == "list" and teaser %}
    <div class="archive__item-teaser">
      <img src="{{ teaser | relative_url }}" alt="">
    </div>
    {% endif %}
  </article>
</div>
```


***