---
title: "Recueil"
gloss: "collection"
weight: 3
family: recherche
icon: icon-recueil.svg
repo: "etabli-dev/etabli-recueil"
summary: "Gather. Verify. Map. A self-hosted document and reference manager."
etymology: "A recueil is a collection: texts gathered and bound together in one volume."
platforms: "Server · Web · Desktop client"
stack: "TypeScript · Node 22 · Tauri"
licence: "AGPL-3.0"
release: 0
---

## What it does

Recueil is an API-first document and reference manager with built-in reference
verification, bibliometrics and a systematic-review workflow.

- Gathers documents from the browser, mail, scanner, WebDAV and camera into a
  content-addressed library with a bibliographic facet.
- Verifies and enriches references against the open scholarly graph.
- Exposes the whole library to R, Python and LLMs as data.
- Treats systematic reviews and bibliometric mapping as native workflows, not
  exports.

## Where it stands

Phases 1 and 2 are in the tree, unreleased. It builds and runs from a source
checkout. A Tauri desktop client for a running server exists; its Linux build
has been launched, and the Windows and macOS builds have not yet run in CI.
Mobile clients are planned for a later phase.
