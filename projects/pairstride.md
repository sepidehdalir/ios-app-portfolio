# Pairstride: Compare Videos

One moment. Two points of view. Pairstride aligns two short local SDR videos at a manually marked event, then plays, scrubs and exports their common overlap on one timeline.

**Submitted October 20, 2026 at 00:36 PDT: Pairstride 1.0 (1) and Lifetime Pro are Waiting for Review.** Submission ID `362f8ccc-8ced-48cf-90e4-a1758f8a1826`. Local/native and owner-reported physical/Sandbox QA, signed archive, Apple validation/upload, processed build, published privacy and premium iPhone/iPad campaign completed. V1 is frozen. Not released. TestFlight skipped at the publisher's instruction.

[Product and support](https://sepidehdalir.github.io/pairstride/) · [Public showcase](https://github.com/sepidehdalir/pairstride) · [Privacy policy](https://sepidehdalir.github.io/pairstride/privacy.html)

<img src="https://raw.githubusercontent.com/sepidehdalir/pairstride/main/assets/iphone-01.png" width="250" alt="Pairstride: one moment, two points of view"><img src="https://raw.githubusercontent.com/sepidehdalir/pairstride/main/assets/iphone-02.png" width="250" alt="Manual matching moments"><img src="https://raw.githubusercontent.com/sepidehdalir/pairstride/main/assets/iphone-03.png" width="250" alt="A checked aligned comparison movie">

## Product

A complete free workflow includes two-clip manual alignment, linked playback, 1× / ½× / ¼× speed, labels, one available source audio or mute and labeled 720p side-by-side export. A separate checked movie can be reviewed, saved to Files or Photos, or shared. Original clips remain unchanged.

Optional non-consumable Lifetime Pro adds up to 10 saved local projects with owned media, recoverable Trash, stacked portrait layout, 1080p export and up to 20 label/output presets. Active and trashed media share a 2 GB limit. No subscription, account, backend or tracking/analytics upload.

## Engineering

SwiftUI, AVFoundation, Core Image, Core Text, PhotosUI and StoreKit 2. A single composition and custom renderer drive both preview and export. The overlap plan makes retained source ranges explicit; completed output is checked for dimensions, duration, audio and decodable frames before atomic publication. Durable projects own their source copies and verify SHA-256 manifests on reopen.

Native tests independently decode paired event flashes, compare rotated source corners to exported pixels, measure selected-source audio frequencies and slow-speed pitch, cancel in-flight exports and check original hashes. Storage tests cover relaunch/recovery, corruption preservation and Trash. Small iPhone / iOS 17, iPad / iOS 17 and current iPhone / iOS 26.5 workflows passed. Large type and Dark Mode were inspected; one exact-heading automated clipping false positive was manually documented. iOS 15 compilation is verified; that runtime was unavailable. The publisher reported the physical real-video import/alignment/audio/export/save workflow passed on iOS 26.1. The publisher also reported Apple-confirmed Sandbox purchase, saved-pair relaunch/reopen and restore passed. These reports are distinct from automated evidence; no production paid transaction is claimed.

Public materials are source-free; commercial code is privately backed up. Original illustrative motion and authentic final app UI underpin a dedicated graphite, ivory, cobalt and burnt-orange campaign. Supported inputs and manual alignment / 30 fps SDR limitations are explicit.

By **Sepideh Javanbakht Dalir** · [arvinify.com](https://www.arvinify.com) · [hello@arvinify.com](mailto:hello@arvinify.com)
