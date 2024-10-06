---
layout: page
title: About
description: 技术宅改变世界
keywords: Chunjiang Ding,丁春江
comments: true
menu: 关于
permalink: /about/
---

我是丁春江，求索于技术的深海。

仰慕「优雅编码的艺术」。

相信技术宅将改变世界，编写未来。

## 联系

<ul>
  <li>博客邮箱：<a href="mailto:1534014218@qq.com">your-email@example.com</a></li>
  <li>博客用户名：@Dingchunjiang</li>
  <!-- 如果有其他联系方式，可以继续添加 -->
</ul>





## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
