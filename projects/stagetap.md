<img src="https://raw.githubusercontent.com/sepidehdalir/stagetap/main/assets/icon.png" width="92" alt="StageTap icon">

# StageTap: Theatre Sound Cues

**Give every sound its moment.** A native iPhone and iPad workspace for small school and community-theatre rehearsals. Prepare owned local audio, read operator notes and deliberately fire one sound at a time.

Status — October20,2026: **in production; not submitted or released.** Apple accepted identity6825117733. TestFlight is skipped by publisher instruction. Physical audio-route/long-rehearsal, Apple Sandbox, final signing and App Review submission remain open.

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

Simulator checks do not establish audible hardware gain/fade, real routes, long-rehearsal reliability or Apple Sandbox transactions. Those production gates remain open. Commercial source is backed up in an independent private repository. This source-free case study presents product work, original illustrative stage imagery and original synthetic demo audio.

**Sepideh Javanbakht Dalir** · [Arvinify](https://www.arvinify.com)
