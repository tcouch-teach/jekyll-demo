{% for member in site.data.members %}
- **{{ member.name }}** — {{ member.role }}
{% endfor %}
