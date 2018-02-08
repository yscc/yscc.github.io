---
layout: home
---
<!--dump/index.md-->
<div class="index-content dump">
    <div class="section">
        <ul class="artical-cate">
            <li class="on"><a href="/"><span>导师</span></a></li>
            <li style="text-align:center"><a href="/worker"><span>员工</span></a></li>
            <li style="text-align:right"><a href="/student"><span>学生</span></a></li>
        </ul>
        <div class="cate-bar">
            <span id="cateBar"></span>
        </div>
        <ul class="artical-list">
        {% for post in site.categories.worker %}
            <li>
                <h2>
                    <a href="{{ post.url }}">{{ post.title }}</a>
                </h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
<!--End dump/index.md-->
