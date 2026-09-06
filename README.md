# GxPChat - Single Page Marketing Website

Single standalone HTML marketing page for [GxPChat](https://gxpchat.com).

## Overview
- **File**: `index.html` (Standalone, zero dependencies)
- **Aesthetic**: Clean serif headings (`Playfair Display`), monospace typography (`Roboto Mono`), dark/light theme switching with instant localStorage persistence.
- **Demo Videos & System Previews**: Embedded live demos (`gxpchat-2026-08-31.mp4`, `gxpchat-dashboard.mov`, `gxpchat-submit-it-ticket.mp4`, and `gxpchat-add-asset.mp4`) along with interactive high-resolution GxP Suite application screenshot showcases (`enterprise-qms.png`, `asset-management.png`, `it-help-desk.png`, `it-validation.png`, and `backup-disaster-recovery.png`).
- **Core Value Proposition**: Extending AI beyond drug discovery into document-heavy GxP operations (SOP drafting, Computer System Validation, GxP Audit Readiness, Regulated IT Help Desk, Regulatory Asset Management, and Backup & Disaster Recovery).
- **Compliance**: Built for 21 CFR Part 11, EU Annex 11, ISPE GAMP 5, FDA CSA, and ALCOA+ data integrity via secure Model Context Protocol (MCP) servers.

## Unique Demo URLs, Screenshots & Deep Links

Every video demo and application preview has direct deep-link anchors, standalone clean URLs, and high-resolution screenshot previews with full-screen lightbox inspection:

| Demo / Platform Module | Anchor URL | Clean Page URL | Media Asset URL |
| :--- | :--- | :--- | :--- |
| **Interactive Suite Explorer** | `https://gxpchat.com/#screenshots` | — | Tabbed high-res browser |
| **Overview & Validation** | `https://gxpchat.com/#overview` | `https://gxpchat.com/overview/` | `https://files.gxpchat.com/gxpchat-2026-08-31.mp4` |
| **Enterprise QMS & System of Record** | `https://gxpchat.com/#dashboard` | `https://gxpchat.com/dashboard/` | `/screenshots/enterprise-qms.png` / Direct MOV |
| **IT Help Desk & GxP Service Desk** | `https://gxpchat.com/#ticket` | `https://gxpchat.com/ticket/` | `/screenshots/it-help-desk.png` / Direct MP4 |
| **GxP Asset Governance** | `https://gxpchat.com/#asset` | `https://gxpchat.com/asset/` | `/screenshots/asset-management.png` / Direct MP4 |
| **CSV / CSA Validation Governance** | `https://gxpchat.com/#validation` | `https://gxpchat.com/validation/` | `/screenshots/it-validation.png` |
| **Backup & Disaster Recovery Console** | `https://gxpchat.com/#backup` | `https://gxpchat.com/backup/` | `/screenshots/backup-disaster-recovery.png` |

- **Interactive Screenshot Explorer**: Tabbed switcher at `#screenshots` to seamlessly inspect all 5 GxP Suite modules with instant zoom.
- **Lightbox Inspection**: Clicking on any screenshot or "View Screenshot" link opens a zero-dependency, full-resolution lightbox with keyboard navigation (`Esc`, `ArrowLeft`, `ArrowRight`).
- **One-Click Copy**: Each showcase card on the homepage includes an interactive `Copy Link` button that copies the direct deep link (`#screenshots`, `#overview`, `#dashboard`, `#ticket`, `#asset`, `#validation`, `#backup`) to your clipboard.
- **Visual Target Highlighting**: When navigating to a deep link anchor, the targeted container highlights with a smooth gold/dark glow animation.

## Quick Start
Open `index.html` directly in any web browser, or serve it with any static web server:

```bash
# Python
python3 -m http.server 8080

# Or serve with npx
npx serve .
```
