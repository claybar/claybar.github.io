### Add a list of tags
```
<div class="container">
  <ul>
    {% for tags in page.tags %}
    <li>{{ tags }}</li>
    {% endfor %}
  </ul>
</div>
```
