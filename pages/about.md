---
layout: page
title: About
description: 我们曾在黑夜中起舞
keywords: Kael Wu
comments: true
menu: 关于
permalink: /about/
---


## 坚信

* 熟能生巧
* 努力改变人生

## 联系

* GitHub：[@kaelwu](https://github.com/kaelwu)
* 博客：[{{ site.title }}]({{ site.url }})
* 微博: [@W_Q_H](http://weibo.com/1797126244/profile?rightmod=1&wvr=6&mod=personinfo&is_all=1)

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Mobile Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_mobile_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Windows Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_windows_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
