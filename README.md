# GxPChat - Single Page Marketing Website

Single standalone HTML marketing page for [GxPChat](https://gxpchat.com).

## Overview
- **File**: `index.html` (Standalone, zero dependencies)
- **Aesthetic**: Clean serif headings (`Playfair Display`), monospace typography (`Roboto Mono`), dark/light theme switching with instant localStorage persistence.
- **Demo Videos**: Embedded live demos (`gxpchat-2026-08-31.mp4`, `gxpchat-dashboard.mov`, `gxpchat-submit-it-ticket.mp4`, and `gxpchat-add-asset.mp4`).
- **Core Value Proposition**: Extending AI beyond drug discovery into document-heavy GxP operations (SOP drafting, Computer System Validation, GxP Audit Readiness, Regulated IT Help Desk, and Regulatory Asset Management).
- **Compliance**: Built for 21 CFR Part 11 and ALCOA+ data integrity via secure Model Context Protocol (MCP) servers.

## Unique Video URLs & Deep Links

Every video demo has direct deep-link anchors and standalone clean URLs:

| Demo Video | Anchor URL | Clean Page URL | Direct File URL |
| :--- | :--- | :--- | :--- |
| **Overview & Validation** | `https://gxpchat.com/#overview` | `https://gxpchat.com/overview/` | `https://files.gxpchat.com/gxpchat-2026-08-31.mp4` |
| **QMS Dashboard** | `https://gxpchat.com/#dashboard` | `https://gxpchat.com/dashboard/` | `https://files.gxpchat.com/gxpchat-dashboard.mov` |
| **Submit IT Ticket** | `https://gxpchat.com/#ticket` | `https://gxpchat.com/ticket/` | `https://files.gxpchat.com/gxpchat-submit-it-ticket.mp4` |
| **Add Regulated Asset** | `https://gxpchat.com/#asset` | `https://gxpchat.com/asset/` | `https://files.gxpchat.com/gxpchat-add-asset.mp4` |

- **One-Click Copy**: Each video showcase card on the homepage includes an interactive `Copy Link` button that copies the direct deep link (`#overview`, `#dashboard`, `#ticket`, `#asset`) to your clipboard.
- **Visual Target Highlighting**: When navigating to a deep link anchor, the targeted video container highlights with a smooth gold/dark glow animation.

## Quick Start
Open `index.html` directly in any web browser, or serve it with any static web server:

```bash
# Python
python3 -m http.server 8080

# Or serve with npx
npx serve .
```
