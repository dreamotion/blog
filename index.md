## Dreamotion Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
	<div>
		{{ post.excerpt }}
	</div>
  {% endfor %}
</ul>

