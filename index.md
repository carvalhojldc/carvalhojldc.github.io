## Recent posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.description }}
{% endfor %}
