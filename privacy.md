---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy — Gantt Chart for Sheets

**Last updated: 28 September 2026**

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

## How your data is protected

### In transit

Your spreadsheet data never leaves Google's infrastructure. The add-on runs as Google Apps
Script, on Google's servers, beside the spreadsheet it is reading; the chart it produces is
written back into the same file. Every connection between your browser and that script is
made by Google over TLS.

The add-on does not hold the `script.external_request` permission, so it has no ability to
open a network connection to anywhere — not to us, not to anyone. This is a property of the
deployed script's manifest, which Google enforces at runtime. It is not a promise about our
intentions; it is a permission we do not have.

### At rest

We keep no copy of your spreadsheet data. There is no server of ours for it to be copied to,
no database, and no log file that records spreadsheet contents. Task names, dates, owners and
everything else are read into memory while a chart is being built and are gone when it
finishes.

The only two values that are stored — your display preferences and your licence key, if you
have one — are held in Google's own `PropertiesService`, which lives inside your Google
account and is encrypted at rest by Google. We cannot read them.

### Access control

No person at Slowgrain can access your spreadsheet data, because there is no system through
which to access it. There are no employees, no contractors and no third-party processors with
a route to it. The Apps Script project that carries the add-on's code is owned by a single
Google account, and publishing a new version of the add-on requires signing in to it.

The secret used to sign licence keys is never committed to our source repository and is not
present in any copy of the code we publish. It exists only in the deployed script and in an
offline backup encrypted with AES-256.

### Retention and deletion

- **Spreadsheet data** is not retained at all. Nothing to delete.
- **Preferences and licence key** are deleted by Google when you uninstall the add-on. You
  can also clear the licence key yourself at any time: Extensions → Gantt Chart for Sheets →
  Licence → leave the box empty → OK.
- **Purchase records** — an order reference and the email address a key was sent to — are
  kept only as long as tax law requires us to keep them, and then deleted. Write to the
  address at the bottom of this page to have them deleted sooner where the law allows.

### The chart itself

The chart is written into a tab of your own spreadsheet, so it inherits that file's sharing
settings. Anyone you have shared the spreadsheet with can see the chart, exactly as they can
see the task list it was built from. Nothing about the chart is published or shared by us.

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
