---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Testing the timeago plugin on GitHub Pages

{% assign date = '2020-04-13T10:20:00Z' %}

Test

- Original date - {{ date }}, {{ date | timeago }}
