{% if site.paginate %}
	{% for post in paginator.posts %}
  {{ post.title }}
  {% endfor %}
 {% endif %}
