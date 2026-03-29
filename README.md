# Краснодарский край

<ul>
{% for city in site.data.cities %}
  <li>
      {{ city.name }}, {{ city.population }}
  </li>
{% endfor %}
</ul>
