---
title: Test
date: 2018-10-02 17:10:05
tags:
---
使用命令
hexo new post 标题
即可创建新post

标签插件引用块
{% blockquote [我是作者[, source]] [我是链接] [source_link_title] %}
我是引用内容
{% endblockquote %}

只输出普通的blockquote
{% blockquote %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.
我也不知道这堆东西是什么

{% endblockquote %}

引用书上的内容
{% blockquote David Levithan, Wide Awake %}
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.

不要只追寻你的幸福，用善良和施舍为他人谋求幸福。
{% endblockquote %}

代码块举例
{% codeblock Array.map %}
array.map(callback[, thisArg])
{% endcodeblock %}

{% codeblock _.compact http://underscorejs.org/#compact Underscore.js %}
_.compact([0, 1, false, 2, '', 3]);
=> [1, 2, 3]
{% endcodeblock %}

试图插入一个youtube视频
{% youtube bp_WidtF2zs %}
