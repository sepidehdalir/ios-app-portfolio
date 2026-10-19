# Foldwisp: Booklet Printing

**A PDF on your device. A little book in your hands.**

Foldwisp arranges supported PDFs onto A4 or US Letter sheets for a nested, folded booklet. It combines a sheet-pair preview, intended reading-order preview and a physical manual-duplex calibration workflow, so users can test their printer's reload direction before printing the full stack.

**Status — October 19, 2026:** in production, not yet uploaded, submitted or released. An earlier 1.0 (1) candidate passed native archive validation; the final accessibility corrections are now signed/exported and awaiting repeat validation/upload. Device/accessibility verification, physical folded-output proof, genuine Sandbox purchase verification and the app-specific privacy certification remain open gates. TestFlight is intentionally skipped by publisher instruction.

[Public product showcase](https://github.com/sepidehdalir/foldwisp-showcase) · [Support](https://sepidehdalir.github.io/foldwisp-showcase/)

<img src="https://raw.githubusercontent.com/sepidehdalir/foldwisp-showcase/main/assets/iPhone/01-foldwisp.png" alt="Foldwisp booklet printing campaign with the original field-guide sample" width="280"> <img src="https://raw.githubusercontent.com/sepidehdalir/foldwisp-showcase/main/assets/iPad/02-foldwisp.png" alt="Dedicated iPad workspace with a saved-job shelf beside the complete sheet preview" width="360">

## Product

- Free complete booklet export through eight source pages; blank-page padding to a multiple of four.
- A4/Letter vector PDF output, with combined or separate front/back passes.
- Sheet and reading previews; user-confirmed reload notes, reverse-back-stack and 180° back rotation.
- Protected local saved jobs; native sharing, Save to Files and system printing.
- One non-consumable Lifetime Pro purchase for 120 source pages, eight reusable printer presets and five separate PDF jobs per batch.

## Engineering

Native SwiftUI, PDFKit, CoreGraphics and StoreKit 2. Universal iPhone/iPad deployment targets iOS/iPadOS 15 using the installed 26.5 SDK. Staged imports publish atomically, cancellation preserves existing work, and bounded page/file/image-resource checks precede rendering. Corrupt saved records are retained and reported. StoreKit-verified entitlements govern Pro without deleting saved content on entitlement loss.

Independent imposition/output checks, persistence/cancellation regressions, local StoreKit lifecycle tests and simulator sample/export/relaunch flows have dated results. Physical printer output and genuine Sandbox remain distinct from those results. Selected native Light/Dark contrast and control-description audits passed after correcting text, modal buttons and Form headings. The final source also passed the iOS 17 small-phone sample/reading/export/relaunch flow. Ten refreshed dedicated phone/tablet marketing frames and the IAP reviewer screenshot are accepted in App Store Connect. The iOS 15 runtime is unavailable on the current host; no complete physical-device VoiceOver pass is claimed.

The app has no account, analytics SDK, external AI or developer-operated document upload. Explicit user-selected Files providers, share destinations and printers retain their own behavior. Commercial source and private verification records remain in an independent private repository. The public showcase contains original product visuals and technical summaries.

**App Store record:** 6824577159 · **Version:** 1.0 (1), in production.

Built by [Sepideh Javanbakht Dalir](https://www.arvinify.com) · [hello@arvinify.com](mailto:hello@arvinify.com)
