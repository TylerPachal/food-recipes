# Food Recipes

A collection of recipes that I have found and enjoyed.  I used to bookmark them but a lot of the blogs they were hosted on get taken down.  Here I can format/save/search them.

## Recipes

{% for recipe in site.recipes %}
  <a href="{{ recipe.url | relative_url }}">
    {{ recipe.name }}
  </a>
{% endfor %}
