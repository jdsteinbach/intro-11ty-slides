### Content from an API

```
{% raw %}{% for p in posts %}
  <li>
    <a href="{{ p.url }}">
      {{ p.title }}
    </a>
  </li>
{% endfor %}{% endraw %}
```
