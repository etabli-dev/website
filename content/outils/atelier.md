---
title: "Atelier"
gloss: "workshop"
weight: 1
family: recherche
icon: icon-atelier.svg
repo: "etabli-dev/etabli-atelier"
site: "https://etabli-dev.github.io/etabli-atelier/"
summary: "Run R and Python on your phone, fully offline."
etymology: "An atelier is a workshop: the room where the actual making happens."
platforms: "Android · iOS"
stack: "Flutter · WebR · Pyodide"
licence: "Apache-2.0"
release: 1
---

## What it does

Atelier is an offline polyglot workspace. R (through WebR) and Python
(through Pyodide) run as switchable kernels inside an embedded runtime and
share one virtual filesystem.

- numpy, pandas, scipy, matplotlib and scikit-learn come bundled.
- Base-R and matplotlib plots can be captured as PNG.
- Scripts and data stay on the device.

## Where it stands

Android development builds are produced from source. Unsigned iOS simulator and
device Release builds have been verified. App Store, Google Play and F-Droid
releases are planned. Desktops are not a target: they already have native R
and Python.

Runtime licences (WebR is GPL) are listed in the repository's `THIRD_PARTY.md`.
