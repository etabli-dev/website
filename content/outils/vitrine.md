---
title: "Vitrine"
gloss: "showcase"
weight: 2
family: recherche
icon: icon-vitrine.svg
repo: "etabli-dev/etabli-vitrine"
site: "https://etabli-dev.github.io/etabli-vitrine/"
summary: "Run interactive Shiny apps entirely on your device."
etymology: "A vitrine is a shop window: the place where finished work is put on show."
platforms: "Android · iOS"
stack: "Flutter · WebR · shinylive"
licence: "Apache-2.0"
release: 1
---

## What it does

Vitrine bundles WebR and shinylive-R so that interactive R Shiny applications
run on the device, without a Shiny server.

- Import Shiny source or shinylive bundles, including through the system share
  sheet.
- Sample apps are included and work offline.
- Imported apps may need extra packages or network access. Vitrine is not a
  sandbox for untrusted code.

## Where it stands

Android development builds are produced from source. Unsigned iOS simulator and
device Release builds have been verified. Store releases are planned. Desktops
run Shiny natively and are not a target.
