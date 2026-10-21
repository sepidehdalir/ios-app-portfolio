<img src="https://raw.githubusercontent.com/sepidehdalir/stagetap/main/assets/icon.png" width="92" alt="StageTap icon">

# StageTap: Theatre Sound Cues

**Give every sound its moment.** A native iPhone and iPad workspace for small school and community-theatre rehearsals. Prepare owned local audio, read operator notes and deliberately fire one sound at a time.

Status — October21,2026: **submitted at12:47PDT. App1.0(1) and Lifetime Pro both Waiting for Review; V1 frozen. Not released.** Apple accepted identity6825117733. TestFlight is skipped by publisher instruction. The publisher confirmed the real-audio/ZIP and Apple Sandbox Pro workflows. Signed Universal archive/export, fifteen App Store campaign uploads and approved privacy publication are complete. Apple validation and upload passed at12:31PDT. Build1 processed, selected and submitted with Lifetime Pro. Apple receipt45f34265-959d-4cca-8977-b4fc9a49bcc2.

[Product and case study](https://sepidehdalir.github.io/stagetap/) · [Support and original demo show](https://sepidehdalir.github.io/stagetap/support.html) · [Privacy](https://sepidehdalir.github.io/stagetap/privacy.html) · [Showcase repository](https://github.com/sepidehdalir/stagetap)

| The next cue | Build the running order | Fade and advance |
| --- | --- | --- |
| ![Ready cue](https://raw.githubusercontent.com/sepidehdalir/stagetap/main/assets/campaign-01.png) | ![Cue preparation](https://raw.githubusercontent.com/sepidehdalir/stagetap/main/assets/campaign-02.png) | ![Fade and next](https://raw.githubusercontent.com/sepidehdalir/stagetap/main/assets/campaign-03.png) |

[Dedicated iPad campaign](https://raw.githubusercontent.com/sepidehdalir/stagetap/main/assets/ipad-01.png)

## Product and engineering

- SwiftUI, AVAudioPlayer and AVAudioSession with a separate tested transport state machine, rapid-tap cooldown and stale-callback tokens. Stop holds the cue; natural completion and Fade & next advance. Rehearsal repeats the selected cue. Interruptions and disconnected output require manual rearming.
- Native full decoding of WAV/AIFF/MP3/M4A before adoption; streamed hashes, bounded copies, atomic manifests, staging and recoverable show Trash.
- Portable ZIP STORE backups contain cue names, notes, settings and original encoded audio. CRC, path, schema, bounds, SHA256 and audio validation precede restoration with fresh identities.
- Free one show, ten cues and full backup. StoreKit2 Lifetime Pro expands to ten shows, one hundred cues per show and ten setting templates; attach audio separately. No subscription.
- Universal iOS/iPadOS15 target with Xcode26.5. Actual execution evidence starts at17 because no15runtime is available. Dedicated iPad workspace and original campaigns preserve authentic native UI.
- No developer backend, tracking or analytics upload; Apple manages purchases. Cloud Files destinations and device backups follow the user’s provider/settings.

## Dated verification

Twenty-two targeted core, native media/playback and local StoreKit tests passed on iOS17. Native Files MP3 import, recoverable malformed-audio error and phone/iPad playback flows ran on26.5. A five-cue show was saved through Files, moved to recoverable Trash, then the actual saved ZIP restored through Files. Independent verification confirmed CRC, original manifest equality, all encoded audio bytes/hashes, five cues and fresh show/cue IDs. Initial location/filename test-selector failures are retained separately, not claimed as passes.

Simulator checks do not establish audible hardware behavior. Separately, on October20 the publisher confirmed the real-audio/ZIP workflow and Apple Sandbox purchase, second show, cue-setting template, relaunch and Restore Purchases. External route/interruption hardware coverage is not separately itemized. The signed Universal15 archive and App Store export passed local checks; Apple server validation/upload passed October21; processing/build selection and actual joint App Review submission completed. Apple receipt45f34265-959d-4cca-8977-b4fc9a49bcc2 confirms both items Waiting for Review at12:47PDT; not approved or released. All fifteen premium campaign frames are uploaded, and the Data Not Collected label was published with StageTap-specific approval. Commercial source is backed up in an independent private repository. This source-free case study presents product work, original illustrative stage imagery and original synthetic demo audio.

**Sepideh Javanbakht Dalir** · [Arvinify](https://www.arvinify.com)
