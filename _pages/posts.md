---
layout: archive
title: "Blog"
permalink: /posts/
author_profile: false
---

<h1 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Blog - All Posts" }}</h1>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% if page.url == '/' and insta_image != true and site.url == 'fake.url' %}
  <h1 class="archive__subtitle">Instagram Feed</h1>
  <div id="IG_bottom">
      <figure class="sixth" id="IG_bottomFigure"></figure>
  </div>
{% endif %}

{% include paginator.html %}
