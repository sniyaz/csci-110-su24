---
layout: page
title: Weekly Schedule
description: The weekly event schedule.
---

## Live Class Instructions

For the **Zoom link** for "live" classes and office hours, please see **Canvas** or **Discord** (I don't want to post the link publicly).

To queue for help during live classes and office hours, see the `live-help` channel on Discord. Please post in this channel with a short description of the question you have. For example:

`Lab 1: Getting an Error in Part A`

You can submit these questions starting **15 minutes** before the start of each live class or office hour. When an instructor is helping you, they will react with a 💬 emoji. They will also call your name and move you to a breakout room in Zoom. Once the instructor is done helping, you'll see your question marked with a ✅ emoji.

Don't worry if you don't see the instructor in the main Zoom call: they are helping another student in a breakout room.

## Weekly Schedule

(Make sure to **scroll** to view the entire page!)

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
