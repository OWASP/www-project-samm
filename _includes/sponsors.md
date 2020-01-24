<div class="member-list">
  <div>
  {% for sponsor in include.data %}
    <a class="member-logo" href="{{ sponsor.url }}" rel="sponsored" target="_blank">
      <img src="{{ sponsor.image }}" alt="{{ sponsor.name }}" />
    </a>
  {% endfor %}
  </div>
</div>
