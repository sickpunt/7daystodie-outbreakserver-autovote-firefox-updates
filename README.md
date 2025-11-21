# 7 Days to Die Auto Voter - Update Manifest

This repository contains the public update manifest for the **7 Days to Die Auto Voter** Firefox extension.

## Purpose

This repo hosts only the `updates.json` file that Firefox uses to check for extension updates. The main extension development happens in a separate private repository.

## Installation

To install the extension:

1. Download the latest `.xpi` file from the [main project releases](https://github.com/sickpunt/7daystodie-outbreakserver-autovote-firefox/releases)
2. Open Firefox and drag the `.xpi` file into the browser
3. Click "Add" when prompted

## Updates

The extension automatically checks this manifest for updates. When a new version is available, Firefox will download it from the GitHub releases page.

## Update Manifest URL

The update manifest is served via GitHub Pages at:
```
https://sickpunt.github.io/7daystodie-outbreakserver-autovote-firefox-updates/updates.json
```

## Privacy

This is a public repository containing only the update manifest. The extension source code is maintained separately.
