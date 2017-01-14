---
layout: page
title:  "Lululemon Web Experience Redesign"
date:   2016-04-15 12:00:00 -0800
categories: projects
navigation_weight: 2
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes.

{% if page.next_in_category != nil %}
	<a href="{{page.next_in_category.url}}" class="next-link">Older Post</a>
{% endif %}
{% if page.previous_in_category != nil %}
	<a href="{{page.previous_in_category.url}}" class="previous-link">Newer Post</a>
{% endif %}
