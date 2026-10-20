# Dateborne: Photo Date Editor

Give family photos and film scans their own moment. Import a JPEG or HEIC still, choose an explicit capture date and fixed UTC offset, create a separate copy, then read back the embedded dates before sharing.

[Product and support](https://sepidehdalir.github.io/dateborne/) · [Public case study](https://github.com/sepidehdalir/dateborne) · [Privacy policy](https://sepidehdalir.github.io/dateborne/privacy.html)

**Current status — October 20, 2026:** App 1.0 (1) rejected under Guideline 4.3(a) on October 20, 2026; Lifetime Pro Ready for Review. Recovery in progress; no new binary resubmission, approval or release. Earlier submission and QA milestones are historical; no new recovery-test pass is claimed.

<img src="https://raw.githubusercontent.com/sepidehdalir/dateborne/main/assets/phone-01.png" width="250" alt="Dateborne: Give memories their moment"><img src="https://raw.githubusercontent.com/sepidehdalir/dateborne/main/assets/phone-02.png" width="250" alt="Choose explicit date and UTC offset"><img src="https://raw.githubusercontent.com/sepidehdalir/dateborne/main/assets/phone-03.png" width="250" alt="Read the exported embedded date">

## Product

The full single-photo workflow is free. Lifetime Pro is a one-time upgrade for bounded batches up to 50 photos, up to 20 saved date/offset presets, and exported batch verification summaries. No subscription, account, backend or external AI. Originals are unchanged. Session copies must be explicitly saved before closing or starting again.

## Engineering

SwiftUI with native ImageIO container copying and strict Gregorian/fixed-offset date rules. Files are reopened to check required capture/digitized/modified dates and offsets; dimensions and orientation are checked separately. Supported JPEG coding data and HEIC HEVC item extents are compared independently. Unknown layouts report that comparison as unverified. No promise covers every metadata field or receiving-app behavior.

A native HEIC experiment found stale dates despite a successful write result; replacement metadata plus output validation fixed it. An independent binary TIFF/EXIF parser verifies fixture fields without relying on ImageIO metadata synthesis. Tests also caught an upright JPEG without a TIFF directory; preserving orientation materializes the directory before dates are written.

Native tests passed on small iPhone/iOS17, iPad/iOS17 and current iPhone/iOS26.5. Actual UI tests saved and reopened copies through Photos and Files. Other checks covered a 50-photo batch, original byte identity, cancellation, preset persistence, large type/Dark Mode/landscape, and automated accessibility contrast/clipping/hit targets. StoreKitTest passed locally on iOS17; iOS26.5's test service failed and is recorded separately. iOS15 compilation is verified; that runtime was unavailable. The publisher reported successful physical real-photo saved-copy matching and genuine Sandbox purchase/restore on the connected iPhone running iOS26.1. Those owner reports are separate from automated native evidence; no production paid transaction is claimed.

Commercial source is privately backed up; public assets contain authentic app UI and an original generated example photograph. No customer photos, signing files or credentials are published.

By **Sepideh Javanbakht Dalir** · [arvinify.com](https://www.arvinify.com)
