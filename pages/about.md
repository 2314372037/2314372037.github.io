---
layout: page
title: About
description: 随便写点，为自己做个记录
keywords: 张豪, Hao
comments: true
menu: 关于
permalink: /about/
---

我是张豪，码而生，码而立。

仰慕「优雅编码的艺术」。

坚信熟能生巧，努力改变人生。

## 联系

zh2314372037@outlook.com

## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
