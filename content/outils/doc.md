---
title: "Doc"
gloss: "document"
weight: 5
family: services
icon: icon-doc.svg
repo: "etabli-dev/etabli-doc"
site: "https://etabli-dev.github.io/etabli-doc/"
summary: "Search your Paperless-ngx documents from your phone."
etymology: "Short for document: the paper itself, filed and findable."
platforms: "Android · iOS"
stack: "Kotlin · Swift"
licence: "AGPL-3.0-only, or a commercial licence"
release: 1
---

## What it does

Doc searches document metadata on your own Paperless-ngx server and combines
tag, correspondent and document-type filters.

- Shows titles, dates, original filenames and tags.
- On iOS, downloaded originals open in Quick Look.
- Needs your own HTTPS server and API token.

## Where it stands

A debug-signed Android development APK (v0.1.0) is on GitHub Releases. iOS
builds from source. Uploading, deleting and editing documents are not
implemented. Desktops are not a target; use the Paperless-ngx web interface.
