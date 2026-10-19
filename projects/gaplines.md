# GapLines: Scene Rehearsal

**Status — October 19, 2026:** app 1.0 (3) Rejected under Guideline 4.3(a); Lifetime Pro Ready for Review. App-specific clarification/reconsideration response sent and verified. Not released.

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
- StoreKit 2 signed entitlement handling, explicit paid boundaries and access to existing work after an entitlement changes.

<img src="https://raw.githubusercontent.com/sepidehdalir/gaplines/main/assets/ipad-01-room-for-your-reply.png" width="760" alt="Distinct iPad campaign with the native scene library and player side by side">

The final core/local-purchase/capture suite passed 32 tests. Physical-iPhone objective QA recorded and fully decoded 144,015 nonzero microphone frames, reopened the saved library/model, completed Speaker playback through the final gap, exported 188,115 WAV frames and restored a portable backup. These checks do not imply subjective listening quality or real phone-call/headphone-unplug verification. Native UI checks cover phone/tablet workflows, landscape, small screens, large text and dark appearance.

The release bundle targets Universal iPhone+iPad 15+ with the current SDK; an iOS 15 runtime was unavailable locally. Remote product lookup is verified. Remaining genuine Sandbox purchase verification was skipped by publisher instruction, with no pass claimed. App 1.0 (3) was submitted with Lifetime Pro on October 18. App Review rejected the app under Guideline 4.3(a) on October 19. An app-specific response explains the implemented workflow and requests clarification; no resubmission is claimed. The public project contains reviewed campaigns, engineering context and support/privacy pages. Commercial source and private recordings remain private.

Created by [Sepideh Javanbakht Dalir](https://www.arvinify.com). [Back to portfolio](../README.md).
