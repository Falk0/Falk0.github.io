---
layout: default
title: Home
---

[About](./about.html)

[Contact](./contact.html)


## Post History

<ul>
{% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>



## Latest Post

Here should the latest post be published

