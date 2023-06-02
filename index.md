---
layout: default
title: Home
---

[About](./about.html)

[Contact](./contact.html)



## Reports

<ul>
{% assign sorted_reports = site.reports | sort: 'date' | reverse %}
{% for doc in sorted_reports %}
    <li>
        <a href="{{ doc.url }}">{{ doc.title }}</a>
    </li>
{% endfor %}
</ul>

## Lecture notes

<ul>
{% assign sorted_posts = site.posts | sort: 'date' | reverse %}
{% for post in sorted_posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>

## Presentations

<ul>
{% assign sorted_presentations = site.presentations | sort: 'date' | reverse %}
{% for doc in sorted_presentations %}
    <li>
        <a href="{{ doc.url }}">{{ doc.title }}</a>
    </li>
{% endfor %}
</ul>



