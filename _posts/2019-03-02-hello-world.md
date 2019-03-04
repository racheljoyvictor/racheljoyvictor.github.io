---
layout: post
title: "Hello World"
date: 2019-03-02
tags: housekeeping
categories: ideas
---

Well. Finally got around to putting this old website together. Neat thing about it - powered by [Jekyll](http://jekyllrb.com) and I can use Markdown to author my posts. It actually is a lot easier than I thought it was going to be.

<small>
    {% for tag in page.tags %}
    <a href="/tags/{{ tag }}/">{{ tag }}</a>
    {% endfor %}
</small>
