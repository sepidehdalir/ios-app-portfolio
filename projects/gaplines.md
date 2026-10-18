# GapLines: Scene Rehearsal

**Status — October18,2026:** release QA; build1.0(3) passed Apple validation and uploaded. Not yet submitted or released.

[Product showcase and support](https://sepidehdalir.github.io/gaplines/) · [Public project](https://github.com/sepidehdalir/gaplines) · [Privacy](https://sepidehdalir.github.io/gaplines/privacy.html)

<img src="https://raw.githubusercontent.com/sepidehdalir/gaplines/main/assets/iphone-01-room-for-your-reply.png" width="240" alt="Real recorded-scene player in the Room for your reply campaign"> <img src="https://raw.githubusercontent.com/sepidehdalir/gaplines/main/assets/iphone-02-record-the-other-side.png" width="240" alt="Native recording and speaker-label editor"> <img src="https://raw.githubusercontent.com/sepidehdalir/gaplines/main/assets/iphone-03-your-pace.png" width="240" alt="A paused timed reply gap">

Actors need partner cues and room to answer. GapLines stores recorded dialogue and explicit, editable silence in one scene. Record a cue, label the speaker, add a reply gap and rehearse in order. Pause, seek, skip or repeat. Export a playable WAV or a validated portable backup containing recordings, labels and timing.

One complete scene, single-scene export and backup/restore are free. A one-time Lifetime Pro upgrade adds multiple scenes, saved gap presets and batch export. No subscription, account, AI voice or supplied licensed script.

## Product and engineering work

- Native SwiftUI scene editor and dedicated iPad library/workspace layout.
- AVFoundation microphone recording and playback, monotonic gap clocks, actual player-clock reconciliation, pause preservation and guarded callbacks.
- Immutable validated takes and atomic versioned manifests preserve committed work during failures.
- Bounded, staged backup validation checks paths, identifiers, media and timing before a deliberate keep-both or replacement restore.
- Streamed PCM WAV export renders the real recorded sequence and complete final silence; cancellation leaves source scenes intact.
- StoreKit2 signed entitlement handling, explicit paid boundaries and access to existing work after an entitlement changes.

<img src="https://raw.githubusercontent.com/sepidehdalir/gaplines/main/assets/ipad-01-room-for-your-reply.png" width="760" alt="Distinct iPad campaign with the native scene library and player side by side">

The final core/local-purchase/capture suite passed32 tests. Physical-iPhone objective QA recorded and fully decoded144015 nonzero microphone frames, reopened the saved library/model, completed Speaker playback through the final gap, exported188115 WAV frames and restored a portable backup. These checks do not imply subjective listening quality or real phone-call/headphone-unplug verification. Native UI checks cover phone/tablet workflows, landscape, small screens, large text and dark appearance.

The release bundle targets Universal iPhone+iPad15+ with the current SDK; an iOS15 runtime was unavailable locally. Remote product lookup is verified, while final remote Sandbox purchase verification and App Review submission remain pending. The public project contains reviewed campaigns, engineering context and support/privacy pages. Commercial source and private recordings remain private.

Created by [Sepideh Javanbakht Dalir](https://www.arvinify.com). [Back to portfolio](../README.md).
