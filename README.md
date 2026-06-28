# My THRIVE-Belize Training

A mobile-first, privacy-preserving web companion for the two University of Arizona Global Health Institute (GHI) students supporting the **THRIVE-Belize** feasibility study in Punta Gorda, Toledo District, Belize.

**Live app:** https://yeridu.github.io/My-THRIVE-Belize-GHI-Training/

It is a *review and field companion* - not a replacement for the protocol, the Staff Safety Training Guide, the supplements, or the full manual.

## What it covers

1. **Introduction** - Belize, the Toledo District, Punta Gorda, languages, and how to work respectfully as a guest.
2. **The Protocol** - what the feasibility study is, who is surveyed, and what data is collected (with an audio reading option).
3. **Supplements (by importance)** - Data Management (D) and Safeguarding (G) as high priority, Instruments (A) and Consent (E) as medium, Trial Registration (B) and Schedule (C) as lower; the full manual (F) is linked separately. The Confidentiality Agreement (Supplement H) is available to download where it is referenced in the Data Management section.

A persistent **Get Help** pathway, trauma-informed safeguards, interactive quizzes with hints, on-device progress tracking, and downloadable source documents are available throughout.

## Privacy and technical notes

- Single self-contained `index.html` (inline CSS/JavaScript/SVG). Source documents are embedded as base64 for client-side download.
- **No network requests on load.** No cookies, analytics, trackers, external fonts, or CDNs. Progress is stored only in the browser's local storage on the user's own device.
- Audio and video are served from the same repository and load only when the user presses play (`preload="none"`), so the page makes no requests until then.
- Content is drawn faithfully from the THRIVE-Belize study documents; background on Belize is cited (Moberg 2020; Grant 2022; Rich 2017) and not redistributed.

## Before student use

- Confirm all referral phone numbers are current at the start of fieldwork.
- A school counsellor name and number were not in the source documents and are intentionally not listed; route school follow-up through the Designated Safeguarding Lead and Hillside Health Care.
- The trial registration (NCT) number is shown as pending until assigned.
