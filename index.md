---
layout: default
---

<div id="home">
    {% for post in site.posts %}
        <h1>{{ post.date | date_to_string }}&raquo; {{ post.title }}</h1>
        {{ post.content }}
        <hr/>
    {% endfor %}
</div>