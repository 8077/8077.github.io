---
layout: page
title: About
description: 马儿哎， 你快些走
keywords: Alex Ma, 马走田
comments: true
menu: 关于
permalink: /about/
---

人生这盘棋啊，我特想走快点，哪怕扯了蛋

......

## 坚信

* ......
* ......

## 联系

* GitHub：[@8077](https://github.com/8077)
* LinkedIn：[@majunshan](https://www.linkedin.com/in/majunshan)
* 博客：[{{ site.title }}]({{ site.url }})
* 微博: [@斯莫维尔](http://weibo.com/am8077)

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

<!--#### Mobile Developer Keywords-->
<div class="btn-inline">
    {% for keyword in site.skill_mobile_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

<!--#### Windows Developer Keywords-->
<div class="btn-inline">
    {% for keyword in site.skill_windows_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
