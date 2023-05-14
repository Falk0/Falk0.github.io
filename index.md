---
layout: default
title: Home
---

[About](./about.html).

## Latest Post

{% assign latest_post = site.posts.first %}
### [{{ latest_post.title }}]({{ latest_post.url }})
{{ latest_post.excerpt }}

## Post History

<ul>
{% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
