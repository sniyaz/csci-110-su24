---
layout: page
title: Office Hours + Schedule
description: The weekly event schedule.
---

## Office Hours Instructions

**Zoom link** for office hours: click [here](https://mtsac-edu.zoom.us/j/86701836775?pwd=K05tM3BJdUFuNUVtQS9xd0RiWk5MUT09).

To queue for office hours, see the `office-hours` channel on Discord. Please post in this channel with a short description of the question you have. For example:

`Lab 1: Getting a Strange Compilation Error`

You can submit these questions starting **15 minutes** before the start of each office hour. When an instructor is helping you, they will react with a 💬 emoji. They will also call your name and move you to a breakout room in Zoom. Once the instructor is done helping, you'll see your question marked with a ✅ emoji.

Don't worry if you don't see the instructor in the main Zoom call: they are helping another student in a breakout room.

## Weekly Schedule

(Make sure to **scroll** to view the entire page!)

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
