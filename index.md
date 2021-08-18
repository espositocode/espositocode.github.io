{% for post in site.posts %}
  <div class="post">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <div class="summary">{{ post.content }}</div>
  </div>
{% endfor %}
