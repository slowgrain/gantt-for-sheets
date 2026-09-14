---
layout: default
title: Support
permalink: /support/
---

# Support — Gantt Chart for Sheets

**Email: slowgrain.dev@gmail.com** — we reply within five working days.

## Getting started

1. Open the spreadsheet containing your task list.
2. **Extensions → Gantt Chart for Sheets → Build Gantt chart**.
3. A tab named **Gantt** appears with your chart. Your task list is not modified.

Re-run it whenever the plan changes; the chart is rebuilt from scratch each time.

## How to lay out your task list

Your table does not have to start at cell A1, and column order does not matter. Headings are
recognised automatically:

| Column | Recognised headings | Required? |
|---|---|---|
| Task name | Task, Name, Title, Activity, Description, 작업, 작업명 | Yes |
| Start date | Start, Start Date, Begin, From, 시작, 시작일 | Yes* |
| End date | End, End Date, Finish, Due, 종료, 종료일 | One of End or Duration |
| Duration | Duration, Days, Length, 기간, 일수 | One of End or Duration |
| Dependencies | Predecessors, Dependencies, Depends On, Blocked By, 선행작업 | No |
| Progress | % Complete, Progress, Completion, 진행률 | No |
| Outline level | Level, Outline Level, Indent, 레벨 | No |
| Owner | Owner, Assignee, Resource, Team, 담당자 | No |
| Task ID | ID, Task ID, WBS, No | No |

\* A task without a start date is fine if it has a dependency to derive one from, or if it is
a summary row with children.

## Common questions

**A task is missing from the chart.**
It will be listed below the chart under "Not shown on the chart", with the reason. Use
**Extensions → Gantt Chart for Sheets → What can't be scheduled?** to see the full list.

**Dates are being read the wrong way round (03/04 read as 4 March, not 3 April).**
The day/month order is inferred from your sheet. Include at least one unambiguous date — any
date with a day above 12, like 25/04/2026 — and the whole sheet will be read that way. Using
ISO dates (2026-04-03) removes the ambiguity entirely.

**How do I write a dependency?**
Put the predecessor's ID in the Predecessors column. `12` means "start after task 12
finishes". `12+3` adds three days of lag. `12-1` starts a day early. Separate several with
commas: `12, 14`.

**How do I make phases?**
Add a Level column: `0` for a phase, `1` for its tasks, `2` for sub-tasks. Phase rows need no
dates — they span their children automatically. A Parent column with the parent's ID works
too.

**Weekends are being counted.**
Turn on **Skip weekends** in the menu. To exclude specific holidays as well, contact support
— holiday lists are configured per sheet.

**"Circular dependency between…"**
Two or more tasks depend on each other, directly or through a chain. The named tasks are left
off the chart. Break the loop and rebuild.

**The chart is too wide to read.**
The timeline picks its own scale from the project length. A very long project is drawn in
weeks, months or quarters rather than days. There is no maximum project length.

**I have more than 50 tasks.**
That is the free limit. Pro removes it. Tasks beyond the limit are reported, not silently
dropped.

## Licence keys

**Entering a key:** Extensions → Gantt Chart for Sheets → Enter licence key.
**Removing a key:** open the same dialog, clear the box, press OK.

A key applies to your Google account, so it works in every spreadsheet you open — you only
enter it once.

**Lost your key?** Email support with the order reference from your receipt.

**Key rejected?** Keys begin with `GS1.` and contain no spaces. Check that the paste did not
pick up a trailing space or a line break. A key that fails is never saved, so your previous
state is untouched.

## Reporting a problem

Email **slowgrain.dev@gmail.com** with:

- what you expected and what happened instead
- a screenshot of the chart or the error
- if possible, a copy of the spreadsheet with any confidential content removed

The add-on cannot send us anything by itself, so nothing reaches us unless you attach it.
