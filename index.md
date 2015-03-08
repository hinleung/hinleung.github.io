---
layout: home
---

<div class="index-content work">
    <div class="section">
        <ul class="artical-cate">
            <li class="on"><a href="/"><span>Work</span></a></li>
            <li style="text-align:center"><a href="/blog"><span>Blog</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.work %}
            <div class="postl"><li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
            </div>
        {% endfor %}
        </ul>
    </div>

</div>
