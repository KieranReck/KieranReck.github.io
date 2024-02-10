---
title: "Adding Teaser Images to 'Minimal-Mistakes' Jekyll Theme Blog"
layout: posts
tagline: ""
header:
    teaser: /assets/images/< enter 4:3 CROPPED IMAGE filename + extension here >
---
![](../assets/images/blog-without-teasers.png)
``` HTML
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
  </article>
</div>
```


![](../assets/images/blog-with-teasers.png)

``` HTML
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

>[!tip] Useful Liquid Tags - Delete before posting
{: .align-center width="400px"} - Needs to be inline with the image
{: .notice--primary} - needs to be the line below the **single line** of text

>[!success] Useful Liquid Tags - Adding a Gallery
>
>{% include gallery id="gallery" layout="half" caption="..." %}
>Layout="half"(2 images wide) or default 3 images wide

>[!caution] Useful HTML Tags - Adding a  single/half/third figure
```
<figure class="half">
    <a href="/assets/images/sealing-face-recessed.jpg"><img src="/assets/images/sealing-face-recessed.jpg"></a>
    <a href="/assets/images/sealing-face-recessed2.jpg"><img src="/assets/images/sealing-face-recessed2.jpg"></a>
    <figcaption>Photo: Sealing face is the ‘inner’ section of the top face.  
(O-Ring groove is found on the mating part).</figcaption>
</figure>
```







***