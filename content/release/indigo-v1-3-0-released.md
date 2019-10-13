---
title: "Indigo v1.3.0 released"
date: 2019-09-30T09:00:00-04:00
draft: false
categories: ["releases"]
tags: ["indigo"]
---

Indigo [v1.3.0] is a minor release that brings Indigo into better compliance with Hugo theme guidelines.

<!--more-->

From the [changelog]:

## Added

- Adds a `mainSection` configuration parameter to set preferred content name.

## Changed

- Updated **CONTRIBUTING.md** to reflect new contributions process.
- Bumped the minimum Hugo version requirement to 0.58 to account for breaking changes to list pages.

## Fixed

- As part of an audit of the theme's code:
  - Removed forward slashes (`/`) in URLs for better compatibility with sites that don't live at a domain root.
  - Fixed the location from which the theme's fonts are loaded.

## Removed

- GitHub issue and pull request templates removed from the repo.

[v1.3.0]: https://github.com/AngeloStavrow/indigo/releases/tag/v1.3.0
[changelog]: https://github.com/AngeloStavrow/indigo/blob/master/CHANGELOG.md#130
