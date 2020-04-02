---
title: Home

layout: default

---

![crater](img/crater.jpg)

<h2>Baking</h2>

{% for recipe in site.baking %}
<p>
  <a class="post-link" href="{{ recipe.url | prepend: site.baseurl }}">{{ recipe.title }}</a>
</p>
{% endfor %}


<h2>Savoury</h2>
{% for recipe in site.savoury %}
<p>
  <a class="post-link" href="{{ recipe.url | prepend: site.baseurl }}">{{ recipe.title }}</a>
</p>
{% endfor %}

