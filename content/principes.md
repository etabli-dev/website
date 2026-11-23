---
title: "Principes"
description: "How the Établi tools are built: local first, no tracking, stated scope."
lede: "The rules every tool on the bench follows, and where each repository documents how it meets them."
---

## Your device, your server

The suite has no shared hosted account and no Établi backend. Server clients
(Courrier, Doc, Table, Projet, Nuage) connect only to the services you configure
and need your own credentials. How credentials are stored, what is cached,
how backups behave and which hosts are contacted is documented per repository.

## No tracking

The suite has no analytics service of its own. This
website uses self-hosted, cookie-free statistics; see the
[privacy notice](../datenschutz/).

## Offline where it can be

Games, Plume's reference and the bundled examples in Atelier and Vitrine run
without a network. Imported scripts, Shiny apps and checked web pages can
request external resources: Atelier and Vitrine are not sandboxes for untrusted
code.

## Stated scope

Each README says what is implemented, what has been verified, on which platform,
and what is not. Development builds on GitHub Releases are snapshots; they are
not store-approved releases and do not include later source changes. App Store,
Google Play and F-Droid publication are separate steps that have not happened
yet.

## One family

The tools share the Coder design system: the green tile with one white
line-glyph, restrained borders, monospaced values, and light, dark and system
themes. A shared design does not mean identical features; platform behaviour
and accessibility are checked per app.

## Licences

Since 22 November 2026 the apps (Atelier, Vitrine, Courrier, Doc, Table,
Projet, Nuage, Focus, Plume, BranchXO and Lattttice) are dual-licensed: the
GNU Affero General Public License, version 3 only (AGPL-3.0-only), or a
commercial licence from the copyright holder (etabli.dev@outlook.com). Recueil
is proprietary, all rights reserved. Versions published earlier remain
available under their earlier licences (Apache-2.0; AGPL-3.0 for Recueil). Third-party components
keep their own licences; Atelier and Vitrine list WebR (GPL)
and the other runtime components in `THIRD_PARTY.md`. Always check
a repository's `LICENSE` and `NOTICE`.
