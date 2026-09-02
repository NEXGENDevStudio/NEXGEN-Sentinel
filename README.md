# NEXGEN Sentinel

NEXGEN Sentinel is a privacy-focused browser extension that helps users understand the security and privacy signals of installed browser extensions.

It analyzes extension metadata, declared permissions, website access, enabled state, and other available browser information to provide clear health indicators, risk signals, and actionable recommendations.

> **NEXGEN Sentinel v1.0.0**

---

## Overview

NEXGEN Sentinel gives users a clear view of the extensions installed in their browser and highlights extensions that may deserve additional review.

The goal is simple: make browser-extension security information easier to understand without presenting the results as a definitive security verdict.

---

## Features

- Browser Health overview
- Extension inventory and filtering
- Risk and health indicators
- Permission and website-access analysis
- Extension investigation details
- Extension Protection controls
- Recent Changes tracking
- Configurable notifications
- Privacy-focused local-first design
- Chromium-based browser support
- Clean and explainable security assessments

---

## Dashboard

The Dashboard provides an overall view of browser extension health, including security and privacy indicators, extensions worth reviewing, broad website access, and the most recent scan information.

 <img width="1105" height="1372" alt="Screenshot_2-9-2026_105552_jfbfgipbpkkhcdhiijomlkkjbmokijia" src="https://github.com/user-attachments/assets/9fdaf4f2-6ce4-4fe2-88c6-0a7a32f0a043" />

---

## Extensions

The Extensions section provides an organized inventory of installed browser extensions.

Users can filter extensions by categories such as:

- All
- Needs Review
- High Risk
- Moderate Risk
- Low Risk
- Protected
- Protection Off

Each extension can be opened for more detailed information and investigation.

<img width="1064" height="1955" alt="Screenshot_2-9-2026_105640_jfbfgipbpkkhcdhiijomlkkjbmokijia" src="https://github.com/user-attachments/assets/1a4067ff-64ac-492c-a1a7-81bdb1b7ff05" />

---

## Investigation

The Investigation view provides more context about an individual extension and the signals that contributed to its assessment.

Sentinel is designed to make these signals understandable rather than presenting a simple unexplained security score.

---

## Extension Protection

Sentinel can provide protection controls for supported browser extensions.

Where browser capabilities allow an action, Sentinel uses the available browser extension-management functionality and remains subject to browser security restrictions and permissions.

---

## Recent Changes

Sentinel can show relevant changes involving installed extensions, helping users understand when extension states or other supported extension information has changed.

---

## Settings

The Settings area provides controls for Sentinel's available preferences, including:

- Theme
- Notifications
- Extension Protection settings
- Developer diagnostics
- About and legal information

<img width="1087" height="1909" alt="Screenshot_2-9-2026_105656_jfbfgipbpkkhcdhiijomlkkjbmokijia" src="https://github.com/user-attachments/assets/e4c730f0-e600-4d03-aa7e-190e5fe914f9" />
---

## Browser Popup

The browser popup provides a quick overview of the current Sentinel status without opening the full Sentinel interface.

It includes the current Browser Health score, attention indicators, extension review information, and a shortcut to open Sentinel.

<img width="597" height="577" alt="Screenshot 2026-09-02 104549" src="https://github.com/user-attachments/assets/1bc01d5c-19f3-438e-9e39-1e9d3006e544" />

---

## Supported Browsers

NEXGEN Sentinel is designed for Chromium-based browsers that support the required extension APIs.

Supported browsers include:

- Google Chrome
- Microsoft Edge
- Brave
- Opera
- Vivaldi

Browser API availability may vary between browsers and versions.

---

## How Sentinel Works

NEXGEN Sentinel uses supported browser extension APIs to inspect available extension information.

Depending on browser support, this can include:

- Extension name and identifier
- Extension version
- Enabled or disabled state
- Extension type
- Installation information
- Declared permissions
- Declared website access
- Other available extension metadata

Sentinel uses these observable signals to generate explainable assessments.

---

## Understanding Sentinel Assessments

Sentinel's scores and risk indicators are **informational assessments**.

They are not:

- A guarantee that an extension is safe
- A guarantee that an extension is malicious
- A vulnerability scan
- A complete malware analysis
- An official browser security verdict
- A probability that an extension is malicious

An extension may have broad permissions for legitimate reasons, while a low-risk assessment does not guarantee that an extension is completely safe.

Users should always review extensions carefully before installing or enabling them.

---

## Permission References

Sentinel's analysis is based on information exposed through supported browser extension APIs.

For Chrome Extensions API documentation, see the official:

- [Chrome Extensions API Reference](https://developer.chrome.com/docs/extensions/reference/api)
- [Chrome Extensions Documentation](https://developer.chrome.com/docs/extensions)

Browser APIs and supported capabilities may change over time.

---

## Notifications

Notifications are optional and controlled through Sentinel's settings.

When enabled, Sentinel may notify users about supported extension changes such as:

- Extension installation
- Extension enable/disable changes
- Extension removal

Notifications are intended to keep users informed about changes involving installed extensions.

---

## Privacy

NEXGEN Sentinel follows a local-first privacy approach.

The extension analyzes available browser extension information for its security and privacy features.

For more information, see:

- [Privacy Policy](PRIVACY.md)
- [Terms of Service](TERMS-OF-SERVICE.md)

---

## Installation

NEXGEN Sentinel v1.0.0 is distributed as an official release package.

### Install from a Release Package

1. Download the NEXGEN Sentinel release package.
2. Extract the package.
3. Open your browser's extension management page.
4. Enable **Developer mode**.
5. Select **Load unpacked**.
6. Choose the extracted NEXGEN Sentinel extension directory.
7. Open Sentinel from the browser toolbar.

The exact extension-management interface may vary between supported Chromium-based browsers.

---

## Release Package

The public repository contains the official release/distribution materials and project documentation.

The proprietary source code is not included in the public repository.

The official release package is provided for installation and use under the accompanying proprietary license.

---

## License

NEXGEN Sentinel is proprietary software owned by NEXGEN DevStudio.

See the accompanying [LICENSE.md](LICENSE.md) for the complete license terms.

Copyright © 2026 NEXGEN DevStudio. All rights reserved.

---

## Terms of Service

Use of NEXGEN Sentinel is subject to the accompanying [Terms of Service](TERMS-OF-SERVICE.md).

---

## Security

If you discover a security issue involving NEXGEN Sentinel, please contact the NEXGEN DevStudio support team.

For general support and bug reports:

**Support:** support.nexgen.devstudio@gmail.com

---

## Support

For questions, bug reports, or support requests:

**Support:** support.nexgen.devstudio@gmail.com

**Business:** nexgen.devstudio@gmail.com

---

## Project Information

**Product:** NEXGEN Sentinel  
**Version:** 1.0.0  
**Release:** First Official Release  
**Developer:** NEXGEN DevStudio  
**Platform:** Chromium-based browsers  
**License:** Proprietary

---
