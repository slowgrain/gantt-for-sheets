---
layout: default
title: Gantt Chart for Sheets
permalink: /
---

# Gantt Chart for Sheets

A Gantt chart add-on for Google Sheets that draws the chart **into your spreadsheet**
rather than into a sidebar panel.

That one decision is the product. A sidebar is an iframe served from another origin, and
when a browser has several Google accounts signed in it is routinely attributed to the wrong
one — which is why the established add-ons ship help pages about reloading and waiting.
A chart written into a tab has nothing to attribute: it works with any number of accounts
signed in, in every browser, and it is still there when the add-on is not running. It
prints, it shares, and it survives.

## What it asks for

Two permissions:

| Permission | What it allows |
|---|---|
| See, edit, create and delete only the specific Google Sheets file you use it with | Read your task list and write the chart into a tab of that same file |
| Display and run third-party web content in prompts and sidebars | Show the add-on's menu and dialog boxes |

Google's install screen adds your name and email address to that list. Every Marketplace
add-on requests those and a developer cannot remove them; the add-on itself never reads them.

It has **no permission to access the internet**, so nothing in your spreadsheet can leave
it. See the [privacy policy](privacy/) for what that means in practice.

## Free and Pro

Free charts up to 50 tasks, with no limit on how long the project runs — the timeline
changes scale instead, so a two-week sprint and a five-year programme both fit on a screen.

Pro removes the task limit and adds dependency labels, custom chart colours, and no
watermark.

## Links

- [Support and troubleshooting](support/)
- [Privacy policy](privacy/)
- [Terms of service](terms/)
