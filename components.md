---
layout: page
title: Components
---

The following is a collection of these various elements, from
the most basic building blocks fundamental to a good design to element collages
that combine these elements together into a single design deliverable.
{: class="intro" }

{% for post in site.posts %}
<div class="post-intro">

    <a class="post-title-link" href="{{ post.url | prepend: site.baseurl }}">
        <h2 class="post-title gamma">{{ post.title }}</h2>
    </a>

    <p>{{ post.excerpt }}</p>

    <p><a href="{{ post.url | prepend: site.baseurl }}">View {{ post.title }} &rarr;</a></p>

</div>
{% endfor %}
