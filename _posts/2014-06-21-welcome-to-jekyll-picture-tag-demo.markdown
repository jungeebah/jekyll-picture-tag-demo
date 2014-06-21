---
layout: post
title:  "Welcome to jekyll-picture-tag Demo!"
date:   2014-06-21 16:32:19
categories: jekyll update
---

{% picture jekyll shift-process-001.jpg alt="An unsual picture" %}

What was the narrative that this representation was meant to embellish and complete? As I regarded the work, I slowly sensed that the underlying tale was the picture itself. The painting wasn’t the extension of a story at all, it was something in its own right.

### Variations

With a preset specified:  
{% picture gallery shift-process-002.jpg alt="An unsual picture" data-downloadable="true" %}


{% picture shift-process-003.jpg alt="An unsual picture" %}
{% picture half shift-process-004.jpg alt="An unsual picture" %}
{% picture gallery shift-process-005.jpg alt="An unsual picture" %}

With an alternate source images:  
{% picture shift-process-006.jpg source_lrg: shift-process-002.jpg source_med: shift-process-003.jpg alt="An unsual picture" data-downloadable="true" %}