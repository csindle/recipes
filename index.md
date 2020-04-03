---
title: Jill's Recipes
---

<div class="row">

  <div class="column">
  <h2>Sweet</h2>
    {% for recipe in site.baking %}
    <p>
      <a class="post-link" href="{{ recipe.url | prepend: site.baseurl }}">
      {{ recipe.title }}
      </a>
    </p>
    {% endfor %}
  </div>
  
  <div class="column">
  <h2>Savoury</h2>
    {% for recipe in site.savoury %}
    <p>
      <a class="post-link" href="{{ recipe.url | prepend: site.baseurl }}">
      {{ recipe.title }}
      </a>
    </p>
    {% endfor %}
  </div>
  
</div> 


![crater](assets/img/crater.jpg)
