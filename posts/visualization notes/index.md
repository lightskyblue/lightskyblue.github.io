
<div class="tiles">
{% for post in site.categories.visualization notes %}
  {% include post-grid.html %}
{% endfor %}
</div>
