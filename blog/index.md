---
layout: home
---

<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
            <li><a href="/"><span>Work</span></a></li>
            <li class="on" style="text-align:center"><a href="/blog"><span>Blog</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
       {% for post in site.categories.blog %}
            <div class="postl"><li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
            </div>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
