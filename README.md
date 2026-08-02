# DomiNations Tools - Game Script Utility 2026

> **Browser tools for DomiNations.** Look up war artifact and councilor bonuses, plan configurations, save local records, and share setups using standalone HTML pages.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bennyghall9254/dominations-tools-hub?style=flat-square)](https://github.com/bennyghall9254/dominations-tools-hub)

---

<p align="center">
  <a href="https://bennyghall9254.github.io/dominations-tools-hub/">
    <img src="https://img.shields.io/badge/Download-DomiNations%20Tools%20Script-brightgreen?style=for-the-badge" alt="Download DomiNations Tools Script">
  </a>
</p>

> **[Download DomiNations Tools](https://bennyghall9254.github.io/dominations-tools-hub/)**

---

[Download Latest Build](https://bennyghall9254.github.io/dominations-tools-hub/)

---

## What This Project Provides

DomiNations Tools is a set of browser-based utilities for researching DomiNations war artifacts and councilors. The artifact search tool locates Legendary War Artifact bonuses, and the setup builder lets you organize artifact choices for planning.

Additional tools cover War Chamber councilor searches and War Council planning for seven-seat arrangements. Artifact ownership and setup data can remain in browser local storage, while sharing strings provide a way to transfer configurations. Each utility is delivered as a standalone HTML page and does not require a separate application interface.

---

## Available Tools

- Look up Legendary War Artifact bonuses using the information available.
- Build, organize, and maintain artifact setups.
- Record owned artifacts in browser local storage.
- Search War Chamber councilors and inspect their bonuses.
- Plan War Council arrangements containing seven seats.
- Copy sharing strings for setup transfer or backup.
- Import previously copied sharing strings into the tools.
- Use the utilities as independent static HTML pages.
- Serve the pages locally with Python when desired.

---

## Getting Started

1. Visit the [latest build](https://bennyghall9254.github.io/dominations-tools-hub/).
2. Open the artifact or councilor utility in a supported web browser.
3. Save artifact ownership or setup details as required; local records are stored in browser local storage.
4. For local use, download the standalone HTML files from the repository and open the relevant page in a browser.

You can optionally start a local Python server:

```bash
python -m http.server
```

Use the local address printed by Python, then open the HTML page for the tool you want to use.

---

## Tool Settings and Actions

These utilities rely on browser-based records and sharing controls instead of mandatory command-line settings.

| Setting or action | Description |
|---|---|
| Artifact search | Find Legendary War Artifact bonuses |
| Artifact records | Store owned artifact information in browser local storage |
| War Council size | Plan a seven-seat council |
| Sharing strings | Copy or import setup information |
| Storage location | Browser local storage for tracked artifacts |
| Delivery format | Standalone static HTML pages |
| Local hosting | Optional Python HTTP server |

---

## Compatibility and Requirements

- **Target game:** DomiNations
- **Tool platform:** Web browser
- **Format:** Static HTML pages
- **Optional local runtime:** Python HTTP server
- **Planning support:** Seven-seat War Council setups
- **Storage:** Browser local storage

The project is intended for browser-based searching and planning. Local records belong to the browser profile and storage area used to open the pages. If site data is removed or a different browser is used, saved information may need to be restored with copied sharing strings.

---

## 2026 Changelog

- Documentation covers artifact searches, councilor lookup, setup planning, browser storage, and sharing strings.
- Usage of standalone HTML files and optional local Python hosting is documented.

---

## Frequently Asked Questions

### How do I use DomiNations Tools?

Open the [latest build](https://bennyghall9254.github.io/dominations-tools-hub/) in your browser and choose the artifact or councilor planning utility you need.

### Is a hosted page required?

No. The utilities are standalone static HTML pages. Open downloaded files directly, or run them through a local Python server.

### Where does the tool save owned artifacts?

Owned artifact information is saved in the browser's local storage associated with the page in use.

### How do I transfer a setup?

Copy the setup's sharing string using the available controls. You can load that string later in another session where the tools are available.

### Does the War Council planner support custom arrangements?

Yes. It can be used to assemble a War Council configuration with seven seats.

### Where can I find new versions?

Review the project repository or the [latest build](https://bennyghall9254.github.io/dominations-tools-hub/) for refreshed HTML files and documentation.

### Is Python mandatory?

No. Python is only an optional way to serve the pages locally. The HTML files can also be opened directly in a browser.

### What if browser storage is deleted?

Records kept in local storage may disappear when browser data is cleared. To retain or move a setup, save a copy of its sharing string.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
