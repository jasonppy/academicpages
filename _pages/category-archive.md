---
layout: categories
permalink: /categories/
title: "Posts by Category"
author_profile: true
---

<!-- {% assign categories_max = 0 %}
{% for category in site.categories %}
{% if category[1].size > categories_max %}
{% assign categories_max = category[1].size %}
{% endif %}
{% endfor %}

<ul class="taxonomy__index">
  {% for i in (1..categories_max) reversed %}
  {% for category in site.categories %}
  {% if category[1].size == i %}
  <li>
    <a href="#{{ category[0] | slugify }}">
      <strong>{{ category[0] }}</strong> <span class="taxonomy__count">{{ i }}</span>
    </a>
  </li>
  {% endif %}
  {% endfor %}
  {% endfor %}
</ul> -->

<!-- {% assign entries_layout = page.entries_layout | default: 'list' %}
{% for i in (1..categories_max) reversed %}
{% for category in site.categories %}
{% if category[1].size == i %}
<section id="{{ category[0] | slugify | downcase }}" class="taxonomy__section">
  <h2 class="archive__subtitle">{{ category[0] }}</h2>
  <div class="entries-{{ entries_layout }}">
    {% for post in category.last %}
    {% include archive-single.html type=entries_layout %}
    {% endfor %}
  </div>
  <a href="#page-title" class="back-to-top">{{ site.data.ui-text[site.locale].back_to_top | default: 'Back to Top' }}
    &uarr;</a>
</section>
{% endif %}
{% endfor %}
{% endfor %} -->

<!-- {% include base_path %}
{% include group-by-array collection=site.posts field="categories" %}

{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %} -->