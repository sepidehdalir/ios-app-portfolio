# Phrasevale: Audio Shadowing

**App 1.0 (1) rejected under Guideline4.3(a), October19,2026. Clarification response sent; Lifetime Pro Ready for Review. Not approved or released.**

Built by Sepideh Javanbakht Dalir. Select a phrase from audio you own, listen at your pace, leave a speaking gap, record a response and compare by ear. This source-region/paired-response workflow is distinct from authoring recorded dialogue sequences.

<img src="https://raw.githubusercontent.com/sepidehdalir/phrasevale-showcase/main/assets/icon.png" alt="Phrasevale icon" width="104">

<img src="https://raw.githubusercontent.com/sepidehdalir/phrasevale-showcase/main/assets/iPhone-01.png" alt="Phrasevale iPhone campaign" width="260"> <img src="https://raw.githubusercontent.com/sepidehdalir/phrasevale-showcase/main/assets/iPad-01.png" alt="Phrasevale dedicated iPad campaign" width="390">

## Product and engineering

- Native SwiftUI Universal iPhone/iPad15+ workspace with a source shelf, waveform and numeric region controls.
- AVAudioEngine sample-position scheduling and time-pitch speed adjustment; speaking pauses follow actual audio completion.
- Recording/playback/session work on a serial audio worker, logical cancellation and bounded UI startup/save deadlines. Blocking Apple IO cannot be forcibly cancelled; late results are discarded.
- UUID media and atomic persistence; portable recovery validates size, paths, references and decoded media before replacing data.
- Useful free one-source workflow; one-time Lifetime Pro for more sources, named collections and reusable presets. Local StoreKit2 verified entitlement, restore, offline/relaunch, pending, cancellation, failure and refund paths.
- On-device processing, no account, backend, AI, speech scoring or analytics SDK. Private commercial source is separately backed up.

## Evidence and remaining gates

Twenty-one local core/StoreKit checks passed on iOS17. After the serial audio-worker refactor, actual response recording/decoded-file/playback tests passed on both iOS17.0 and iOS26.5 simulators; the initial iOS17 HAL input failure is preserved in the engineering history. Native capture flows passed on current phone/tablet simulators. Maximum-Dynamic-Type dark portrait/landscape layouts were corrected and visually checked on compact phone/iPad.

Three tests passed on a physical iPhone17ProMax/iOS26.1: actual built-in microphone capture/decoded nonzero samples/completed speaker playback, playback-to-pause timing, and UI record/save/relaunch/background cancellation. The publisher confirmed clear speaker/headphone playback and that disconnect stops playback. Actual incoming-call interruption and spoken VoiceOver focus checks are deferred/non-blocking.

A signed Universal iOS15 Release archive compiled with Xcode26.5 and passed Apple’s native App Store validation; no iOS15 runtime was installed. Explicit development and App Store distribution profiles match the bundle. Version 1.0 (1) completed native upload for App Store Connect app 6824353458. Apple accepted app1.0(1)and LifetimePro on October18,2026 at11:28PM America/Vancouver; submission f9bc4456-6159-44f2-94ca-b62a9f73e92d. On October19, Apple rejected app1.0(1) under Guideline4.3(a); Lifetime Pro is Ready for Review. An app-specific clarification with a reproducible demo workflow was sent and verified at4:20PM America/Vancouver. The comparison app or concrete defect has not been identified; no corrected build or resubmission is claimed. The owner-approved Data Not Collected declaration and final public privacy policy are published. The real Apple catalog/paywall loaded; an account-permission error prevented a verified Sandbox purchase, and the publisher explicitly skipped the remaining purchase/restore/relaunch checks. No genuine Sandbox purchase pass is claimed. TestFlight is skipped by publisher instruction. No App Store availability or learning outcome is claimed.

The ten marketing frames use actual native UI and original-text demo audio rendered locally. No private speaker recordings or commercial source are published.

[Public showcase](https://github.com/sepidehdalir/phrasevale-showcase) · [Full visual case study](https://sepidehdalir.github.io/phrasevale-showcase/) · [www.arvinify.com](https://www.arvinify.com) · [hello@arvinify.com](mailto:hello@arvinify.com)
