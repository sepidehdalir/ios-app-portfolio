# Phrasevale: Audio Shadowing

**Development — not submitted or released. Consumer brand provisional pending App Store Connect reservation.**

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

An unsigned Universal iOS15 Release archive compiled with Xcode26.5; no iOS15 runtime was installed. Physical microphone/headphone/interruption verification, genuine Sandbox, explicit signing, archive validation, upload and App Review remain open. TestFlight is skipped by publisher instruction. No App Store availability or learning outcome is claimed.

The ten marketing frames use actual native UI and original-text demo audio rendered locally. No private speaker recordings or commercial source are published.

[Public showcase](https://github.com/sepidehdalir/phrasevale-showcase) · [Full visual case study](https://sepidehdalir.github.io/phrasevale-showcase/) · [www.arvinify.com](https://www.arvinify.com) · [hello@arvinify.com](mailto:hello@arvinify.com)
