---
layout: page
title: Syllabus
nav_order: 1
description: An embedded Google Calendar displaying the weekly event schedule.
---

# Syllabus

**Please note:** This schedule is still tentative, and is likely to change.

{% for module in site.modules %}
{{ module }}
{% endfor %}
