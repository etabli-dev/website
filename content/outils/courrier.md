---
title: "Courrier"
gloss: "mail"
weight: 4
family: services
icon: icon-courrier.svg
repo: "etabli-dev/etabli-courrier"
site: "https://etabli-dev.github.io/etabli-courrier/"
summary: "An offline workspace for mail, calendar, contacts, tasks, notes and feeds."
etymology: "Courrier is the post: letters that arrive, are read and are kept."
platforms: "Android · iOS · Linux · macOS · Windows"
stack: "Flutter · IMAP · Nextcloud DAV"
licence: "All rights reserved"
release: 1
---

## What it does

Courrier keeps a local copy of your communication and refreshes it from the
services you configure.

- **Mail:** TLS or STARTTLS IMAP; cached messages stay readable offline.
- **Calendar, contacts, tasks:** pulled from Nextcloud DAV collections, with
  source fields preserved; tasks can be completed.
- **Notes:** local or Nextcloud notes with checklists and per-note device
  authentication.
- **Reminders and feeds:** upcoming reminders and deadlines; RSS/Atom and
  Nextcloud News.

## Where it stands

Android and iOS are the mobile targets. The Linux desktop build runs and
packages as a `.deb`, there is an ad-hoc macOS preview, and Windows is a CI
target. Sending mail and Microsoft 365 sign-in are not available yet.
