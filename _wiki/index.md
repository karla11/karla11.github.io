---
layout  : wikiindex
title   : wiki
toc     : true
public  : true
comment : false
Regenerate: true
---

## wiki items

* [[todo]]
* [[book]]
* [[project]]
    *[[Jetson_Nano_2GB_Developer_Kit]]
    *[[ESPRESSObin]]
    *[[Raspberry_Pi_4]]
    *[[BeagleBone_AI]]
    *[[IMX_8M_Plus]]

---

## blog posts
<div>
    <ul>
{% for post in site.posts %}
    {% if post.public != false %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                {{ post.title }}
            </a>
        </li>
    {% endif %}
{% endfor %}
    </ul>
</div>

