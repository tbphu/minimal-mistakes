---
permalink: /people/
---



{% for person in site.people %}
	{{person.firstname}} {{person.last}}
{% endfor %}

