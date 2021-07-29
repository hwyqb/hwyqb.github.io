---
layout:       post
title:        "multi-language demo"
subtitle:     "multi-language demo"
date:         2017-07-12 12:00:00
author:       "xjfuuu"
header-img:   "img/common/post-bg/post-bg-alibaba.jpg"
# 标题图片蒙版
header-mask:  0.3
catalog:      true
# 是否隐藏文章
hidden: false
# 多语言支持
multilingual: true
tags:
    - Template
---

<!-- Chinese Version -->
<div class="zh post-container">
    {% capture about_zh %}{% include posts_multi/2017-07-12-multi-language-demo/zh.md %}{% endcapture %}
    {{ about_zh | markdownify }}
</div>

<!-- English Version -->
<div class="en post-container">
    {% capture about_en %}{% include posts_multi/2017-07-12-multi-language-demo/en.md %}{% endcapture %}
    {{ about_en | markdownify }}
</div>
