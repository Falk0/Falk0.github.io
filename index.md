---
layout: default
title: Home
---

[About](./about.html)

[Contact](./contact.html)



## Reports

<ul>
{% for doc in site.reports %}
    <li>
        <a href="{{ doc.url }}">{{ doc.title }}</a>
    </li>
{% endfor %}
</ul>

## Lecture notes

<ul>
{% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>

## Presentations

<ul>
{% for doc in site.presentations %}
    <li>
        <a href="{{ doc.url }}">{{ doc.title }}</a>
    </li>
{% endfor %}
</ul>


