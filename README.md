<div align="center">
<a href="https://github.com/UnripePlum/SetupAgent/releases"><img src="assets/setup-agent-icon.png" width="200" height="200" alt="Setup Agent" align="center"/></a>

<h2>Setup Agent</h2>
<p>Launch and arrange your apps, browser, and terminal — hands-free — with a Korean wake word.</p>

<a href="https://github.com/UnripePlum/SetupAgent/releases/latest"><img src="https://img.shields.io/badge/⬇%20Download-macOS%2014+-2563EB?style=for-the-badge&logo=apple&logoColor=white" alt="Download for macOS"/></a><br/>
<sub>
<b>macOS 14 Sonoma or later.</b> Signed &amp; notarized — opens without a Gatekeeper warning.<br/>
<a href="https://github.com/UnripePlum/SetupAgent/releases">Browse all releases</a>
</sub>
</div>

<br/>

<div align="center">
<a href="https://github.com/UnripePlum/SetupAgent/releases"><img src="https://img.shields.io/github/downloads/UnripePlum/SetupAgent/total.svg?style=flat&color=blue" alt="downloads"/></a>
<a href="https://github.com/UnripePlum/SetupAgent/releases/latest"><img src="https://img.shields.io/github/v/release/UnripePlum/SetupAgent?style=flat&color=blue" alt="latest release"/></a>
<img src="https://img.shields.io/badge/platform-macOS-lightgrey.svg?style=flat&color=blue" alt="platform"/>
</div>

<br/>

## About Setup Agent

**Setup Agent** is a macOS menu bar app that listens for a Korean wake word — like **"자비스"** or **"지니야"** — and instantly launches and arranges the apps, browser tabs, and terminal you need. Set up a preset once, then bring up your whole workspace by voice, without touching the keyboard. It runs quietly from the menu bar and keeps itself up to date automatically.

<!-- Add a screenshot: drag an image into a GitHub issue to host it, copy the URL, and drop it here.
<div align="center">
<img width="832" src="PASTE_SCREENSHOT_URL" />
</div>
-->

## Key Features

- **Wake-word activation** — listens for your chosen Korean wake word and fires a preset on cue.
- **App & window orchestration** — launches a set of apps, browser, and terminal, and places each window on the display you want.
- **Presets** — define what a wake word opens once, then reuse it every day.
- **Double-tap / clap trigger** — optional: double-tap the MacBook body or clap near the mic to open a listening window.
- **Menu bar native** — no Dock icon, no clutter; live status right in the menu bar.
- **Signed & notarized** — Developer ID signed and Apple-notarized, so it opens without a Gatekeeper warning.
- **Automatic updates** — a built-in updater installs new versions for you (or check manually any time).
- **Bilingual UI** — English and 한국어.

## Installation

### Manual

1. Download the [latest release](https://github.com/UnripePlum/SetupAgent/releases/latest).
1. Open the `.dmg` and drag **Setup Agent** into your `/Applications` folder.
1. Launch it from Applications, Launchpad, or Spotlight.
1. Grant **Microphone** and **Accessibility** access when prompted — Setup Agent needs them to hear the wake word and arrange windows.
1. Use the **Setup Agent** icon in the menu bar to configure presets.

## Using the App

Open **Settings** from the menu bar (gear icon) to register wake-word models, build presets, pick your microphone, and manage general options. Your version and updates live under **Settings ▸ General ▸ Software Update** — or use **Check for Updates…** in the menu bar at any time.

## Compatibility

- **macOS 14 (Sonoma) or later** — Apple Silicon and Intel.
- Requires **Microphone** and **Accessibility** permissions.

## Updates

Setup Agent updates itself via [Sparkle](https://sparkle-project.org): it checks this repository's release feed, downloads the new signed &amp; notarized DMG, verifies its signature, and installs it in place. You can trigger a check any time from **Check for Updates…**.

## Support

Found a bug or have a request? [Open an issue](https://github.com/UnripePlum/SetupAgent/issues).

---

<sub>This repository hosts the public releases and Sparkle update feed for Setup Agent. The source code lives in a separate private repository.</sub>
