---
layout: page
title: Announcements
nav_exclude: false
description: A feed containing all of the class announcements.
order: 2
---

# Announcements

All course related announcements are made here.

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
