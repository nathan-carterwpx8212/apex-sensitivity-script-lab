# Apex Sensitivity Lab - Game Script Utility 2026

> **A browser-based Apex Legends sensitivity workspace for aim drills, sensitivity conversion, and individualized settings review.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathan-carterwpx8212/apex-sensitivity-script-lab?style=flat-square)](https://github.com/nathan-carterwpx8212/apex-sensitivity-script-lab)

---

<p align="center">
  <a href="https://nathan-carterwpx8212.github.io/apex-sensitivity-script-lab/">
    <img src="https://img.shields.io/badge/Download-Apex%20Sensitivity%20Lab%20Script-brightgreen?style=for-the-badge" alt="Download Apex Sensitivity Lab Script">
  </a>
</p>

> **[Download Apex Sensitivity Lab](https://nathan-carterwpx8212.github.io/apex-sensitivity-script-lab/)**

---

[Download Latest Build](https://nathan-carterwpx8212.github.io/apex-sensitivity-script-lab/)

---

## What It Does

Apex Sensitivity Lab is an offline, single-page browser application for examining and improving mouse sensitivity in Apex Legends. Its aim exercises use Canvas and browser pointer-lock controls to assess several forms of mouse control: full-turn calibration, tracking moving targets, clicking targets, transferring between targets, recoil handling, and rapid stopping.

Alongside the practice modes, the tool calculates eDPI and cm/360 values, converts sensitivity between games, and includes a collection of professional player configurations. Test performance and entered settings can inform personalized recommendations, while Apex-specific tools help manage related game options. All configuration information stays in browser-local storage and can be transferred through JSON import and export.

---

## Included Capabilities

- Five-part sensitivity testing covering multiple aim situations
- Full 360-degree calibration to determine required mouse movement
- Drills for following moving targets
- Target-clicking and emergency-stop practice
- Tests for switching between multiple targets
- Recoil-control assessment
- Recommendations tailored to recorded test results
- eDPI and cm/360 calculation and conversion
- Sensitivity conversion between supported games
- Reference library of professional player settings
- Tools for optimizing Apex Legends settings
- JSON import and export for configurations
- Browser-local data storage with no configuration uploads

---

## Getting Started

1. Visit the [latest build](https://nathan-carterwpx8212.github.io/apex-sensitivity-script-lab/).
2. Use a current desktop web browser to open the application.
3. Approve pointer-lock permission when an aim test requests it.
4. Pick a test, enter your sensitivity values, and start the exercise.
5. Inspect the results and apply any useful changes to your Apex Legends setup.

A local browser session is all that is needed to run the tool. To serve the files yourself, open the primary HTML file from the project directory or use a local static server for the directory.

For example:

```bash
python -m http.server
```

After starting the server, browse to `http://localhost:8000/`.

---

## Available Options

| Option | Purpose |
|---|---|
| Aim test mode | Choose calibration, tracking, clicking, transfer, recoil, or emergency-stop exercises |
| Sensitivity values | Provide the settings used for calculations and recommendations |
| 360 calibration | Determine how much mouse movement produces a complete turn |
| Conversion tools | Work out eDPI, cm/360, and sensitivity values for other supported games |
| Pro configurations | Review example settings from the included professional player library |
| JSON import | Restore exported settings and test information |
| JSON export | Back up or move locally stored configurations |
| Local browser storage | Retain tool data in the current browser without sending it to a server |

When a pointer-lock exercise is running, use the available browser or application exit control to release the pointer. Emergency-stop testing is its own exercise: it measures fast stopping ability and is not the same action as ending pointer lock.

---

## Compatibility and Requirements

- **Target game:** Apex Legends
- **Platform:** Desktop web browser
- **Application type:** Offline single-page HTML tool
- **Input focus:** Mouse sensitivity and aim-control testing
- **Storage:** Browser-local storage with JSON import and export

This utility does not replace Apex Legends or modify its settings directly. The usefulness of its results depends on the values entered, the selected exercise, browser input handling, and the user's hardware. Canvas aim exercises require browser support for pointer lock. Sensitivity conversions between games are reference calculations and may not produce identical results across different input systems or scaling models.

---

## Common Questions

### How can I begin with Apex Sensitivity Lab?

Open the [latest build](https://nathan-carterwpx8212.github.io/apex-sensitivity-script-lab/) in a desktop browser, select an exercise, enter your current settings, and approve the pointer-lock request when it appears.

### Is an internet connection needed?

The application is built for offline use once its page and files are available locally. It keeps configurations and test results in the browser rather than uploading them.

### Where does the tool keep my settings?

The current site's browser local storage contains your settings and related data. Clearing that storage or switching browser profiles can make saved values unavailable, so export JSON when you need a backup.

### Can I transfer settings between browsers?

Yes. Export the configuration to a JSON file, then import that file in the other browser or installation.

### How frequently does the tool receive updates?

Future updates may add or extend testing flows, conversion support, configuration references, or Apex optimization functions. The latest build link provides access to the current version.

### Can the sensitivity recommendations be adjusted?

Run the test modes that match your preferred control style and enter your own Apex settings to generate results around that setup. You can also export configurations to preserve and compare multiple arrangements.

### Is the tool compatible with all games?

Apex Legends is the main target. Conversion workflows are available for supported games, but equivalent sensitivity values are not guaranteed because games can use different settings systems and input scaling.

### What should I check if pointer lock fails?

Make sure the tool is open in a desktop browser, click within the test area, and accept the permission request. Browser restrictions or an unsupported input environment can still prevent pointer lock from functioning properly.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
