# Hello world

This is my first webpage.

## Posts

These are my blog posts:

<ul>
  {% for post in site.post %}
    <li>
      <a herf="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date_to_string }}
    </li>
  {% endfor %}
</ul>
