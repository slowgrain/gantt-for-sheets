---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy — Gantt Chart for Sheets

**Last updated: 15 September 2026**

## The short version

Gantt Chart for Sheets has no permission to access the internet. Your spreadsheet data is
read, turned into a chart, and written back into the same spreadsheet. None of it is
transmitted anywhere, because the add-on has no ability to transmit anything.

We do not collect, store, sell, or share your personal information.

## What the add-on can access

It requests exactly two permissions:

| Permission | Scope | What it allows |
|---|---|---|
| See, edit, create and delete only the specific Google Sheets file you use it with | `spreadsheets.currentonly` | Read your task list and write the chart into a tab of that same file |
| Display and run third-party web content in prompts and sidebars | `script.container.ui` | Show the add-on's menu and dialog boxes |

It does **not** request permission to:

- access your Google Drive, or any spreadsheet other than the one you are working in
- access your email, contacts, or calendar
- connect to any external website or service

The last point is the important one. The add-on does not hold the `script.external_request`
permission, so it cannot make network requests of any kind. Even if we wanted to send your
data somewhere, the add-on could not do it.

### What Google's install screen asks for on top of that

When you install anything from the Google Workspace Marketplace, Google adds
`userinfo.email` and `userinfo.profile` to the install screen — your name and your account's
email address. That is Google's Marketplace requirement for every listed add-on and it is not
removable by the developer; we tried to take it off the listing and Google puts it back.

The add-on's own code does not read either of them: its script manifest declares only the two
scopes in the table above, and nothing else is available to it at runtime. We do not receive
your name or email address from an install, and we do not store them.

## What is stored, and where

Two things are saved using Google's own storage for add-ons, which lives inside your Google
account and is not visible to us:

1. **Your display preferences** — whether to skip weekends and whether to highlight the
   critical path. Stored per spreadsheet.
2. **Your licence key, if you have one** — stored against your Google user so that a
   purchase applies in every spreadsheet you open. The key contains a plan name, an expiry
   date, and the payment reference from your purchase. It does not contain your name or
   email address.

Both are removed when you uninstall the add-on. You can clear the licence key yourself at
any time: Extensions → Gantt Chart for Sheets → Licence → leave the box empty → OK.

## What we receive when you buy a licence

Purchases are handled by our payment provider, not by this add-on. When you buy Pro, the
payment provider processes your payment details and gives us an order reference and the
email address to send your licence key to. We never see your card details.

We keep the order reference and email address only to issue your key, reissue it if you lose
it, and meet the record-keeping we are legally required to do. We do not use them for
marketing, and we do not share them with anyone.

## Google Workspace APIs and AI models

Gantt Chart for Sheets does not use any Google Workspace API data to develop, improve, or
train generalised or non-personalised AI or machine-learning models. It does not use AI or
machine learning at all — scheduling is ordinary arithmetic.

## Limited Use disclosure

The use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Children

This add-on is a business tool and is not directed at children under 13.

## Changes

If this policy changes, the "last updated" date above changes with it, and the current
version is always published at this URL.

## Contact

Questions about privacy, or a request to delete anything we hold:

**slowgrain.dev@gmail.com**

We reply within five working days.
