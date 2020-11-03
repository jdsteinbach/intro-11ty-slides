### Collections

```
{% raw %}{% for link in collections.nav %}
  <li>
    <a href="{{ link.url }}">
      {{ link.title }}
    </a>
  </li>
{% endfor %}{% endraw %}
```
