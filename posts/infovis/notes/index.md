
<div class="tiles">
{% for post in site.categories./posts/notes %}
  {% include post-grid.html %}
{% endfor %}
</div>
