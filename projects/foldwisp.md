# Foldwisp: Booklet Printing

**A PDF on your device. A little book in your hands.**

Foldwisp arranges supported PDFs onto A4 or US Letter sheets for a nested, folded booklet. It combines a sheet-pair preview, intended reading-order preview and a physical manual-duplex calibration workflow, so users can test their printer's reload direction before printing the full stack.

**Current status — October 20, 2026:** App 1.0 (1) rejected under Guideline 4.3(a) on October 20, 2026; Lifetime Pro Ready for Review. Recovery in progress; no new binary resubmission, approval or release. Earlier submission and QA milestones are historical; no new recovery-test pass is claimed. First app-specific clarification sent October20,2026; concrete feedback pending. No binary resubmission.

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

Independent imposition/output checks, persistence/cancellation regressions, local StoreKit lifecycle tests and simulator sample/export/relaunch flows have dated results. The physical iPhone 17 Pro Max/iOS 26.1 run passed all 19 core checks, including hardware file protection; a subsequent physical UI run passed reading preview, native export/share, saved-job relaunch, background/resume and live Apple price loading. No purchase was attempted. Physical printer output and genuine Sandbox remain distinct from those results. Selected native Light/Dark contrast and control-description audits passed after correcting text, modal buttons and Form headings. The final source also passed the iOS 17 small-phone sample/reading/export/relaunch flow. Ten refreshed dedicated phone/tablet marketing frames and the IAP reviewer screenshot are accepted in App Store Connect. The iOS 15 runtime is unavailable on the current host; the requested physical VoiceOver flow subsequently passed by explicit publisher report, without claiming exhaustive accessibility coverage.

The app has no account, analytics SDK, external AI or developer-operated document upload. Explicit user-selected Files providers, share destinations and printers retain their own behavior. Commercial source and private verification records remain in an independent private repository. The public showcase contains original product visuals and technical summaries.

**App Store record:** 6824577159 · **Version:** 1.0 (1), Rejected — recovery in progress.

Built by [Sepideh Javanbakht Dalir](https://www.arvinify.com) · [hello@arvinify.com](mailto:hello@arvinify.com)

**Development checkpoint — October25,2026:** A saved booklet print desk is implemented in the private recovery branch: paper/copy estimates, manual or automatic duplex, staged user checks, a complete sheet map and a separate instruction PDF. This is UNVERIFIED SOURCE WORK, not a tested or submitted build. Native verification is blocked by insufficient Mac storage; existing screenshots remain unchanged and do not show the new UI. No new upload, approval or4.3 resolution is claimed.
