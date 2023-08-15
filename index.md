---
title: "Home"
---
# {{page.title}}
This is sample Text
{{% for post in site.posts %}}
      -[{ post.title }]({ post.url })
{{% endfor %}}
