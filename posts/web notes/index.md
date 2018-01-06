
<div class="tiles">
{% for post in site.categories.web notes %}
  {% include post-grid.html %}
{% endfor %}
</div>
