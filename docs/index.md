# Новости

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "news" %}
      <li style="list-style-type:none">
        <h2>{{ post.title }}</h2>
        <div id="list">
          {{ post.excerpt }}
        </div>
      </li>
    {% endif %}
  {% endfor %}
</ul>
