# Beadmora: Fuse Bead Patterns

**Your picture. A bead plan you can shape.**

Beadmora is a focused Universal iPhone and iPad app that turns an owned image into an editable fuse-bead chart, then exports a clear PDF with symbols, counts and labeled board sections.

**Status · October 22, 2026:** version 1.0(3) and Lifetime Pro were submitted together at 15:05 PDT and are Waiting for Review. The app is not yet released. TestFlight distribution is skipped by publisher instruction. This public repository is a product and engineering showcase. Commercial source remains private.

[Product showcase](https://sepidehdalir.github.io/beadmora/) · [Privacy policy](https://sepidehdalir.github.io/beadmora/privacy.html) · [Workflow and support](https://sepidehdalir.github.io/beadmora/support.html)

<p><img src="https://raw.githubusercontent.com/sepidehdalir/beadmora/main/assets/iphone-01.png" width="29%" alt="Original picture to an actual Beadmora bead chart"> <img src="https://raw.githubusercontent.com/sepidehdalir/beadmora/main/assets/iphone-02.png" width="29%" alt="Native photo framing and palette tools"> <img src="https://raw.githubusercontent.com/sepidehdalir/beadmora/main/assets/iphone-03.png" width="29%" alt="Actual PDF symbol chart and counts"></p>

## Product strategy

The job is to turn a picture into a practical plan that a maker can simplify and correct. Beadmora keeps that workflow local and focused: import, frame, reduce colors, preview, edit and export. There is no social feed, manufacturer catalog, remote AI processing or required account.

The free core includes one active project, charts up to 29 × 29, all cell and palette editing, PDF export and project backup. Optional Lifetime Pro is a one-time Apple purchase for charts up to 116 × 116, 50 active projects and 20 saved palettes. Existing work remains editable and exportable if Pro is unavailable.

## Native engineering

- SwiftUI with responsive phone, narrow iPad and wide iPad workspaces; UIKit tiled canvas, pinch/pan, grouped brush edits and undo/redo.
- ImageIO decoding and orientation handling, bounded image input, perceptual color reduction and stable chart symbols.
- Core Graphics and Core Text PDFs: A4/US Letter, overview, legend, exact chart counts, 29-cell sections, global coordinates and partial-section guides.
- Actor-serialized atomic local storage, strict bounded project backups, fresh identities on restore and recoverable Trash without automatic purging.
- StoreKit 2 product loading, verified access, purchase state handling, relaunch and restoration. Test configuration is excluded from the shipping app.
- Universal iOS/iPadOS 15+ build with current SDK. Native execution on installed 17 and 26.5 runtimes is recorded separately from minimum-OS compilation; an iOS15 runtime was unavailable.

## Verification and campaign

Dated private production evidence includes 29 native core/pipeline/local StoreKit tests on iOS17, actual PDF saving through Files, native drawing/undo checks, maximum 116 × 116 chart creation, saved palettes, backup restoration with unchanged chart values and a fresh identity, large-text/dark-mode checks and a narrow iPad workflow. Local StoreKit tests are not represented as live Apple Sandbox results. The publisher separately reported that the owned-photo/PDF/backup/relaunch and genuine Apple Sandbox purchase/restore checks passed. A prebuilt physical automated retry executed no tests because the device was unavailable. The joint submission receipt is 314dc9b2-b1c6-47af-990d-a7352fc43d90; V1 is frozen while awaiting review.

The campaign uses original generated botanical imagery processed through the actual app, authentic native UI captures and actual exported PDFs. Dedicated phone and iPad compositions tell the value, workflow and result before editing and premium scope. No simulated physical finished beadwork or unsupported matching/accuracy claim is used.

<p><img src="https://raw.githubusercontent.com/sepidehdalir/beadmora/main/assets/ipad-04.png" width="64%" alt="Real iPad canvas with side-by-side palette"> <img src="https://raw.githubusercontent.com/sepidehdalir/beadmora/main/assets/iphone-05.png" width="29%" alt="Lifetime Pro maximum-chart example"></p>

## Privacy and craft limitations

Photo processing, charts and palettes stay on the device. There is no developer backend, analytics uploader, tracking SDK or ad SDK. Apple manages purchases; users choose import and sharing destinations. Files providers, OS backups and GitHub-hosted web pages have their own settings and policies.

Small grids simplify detail. Display colors approximate real beads; match your own supplies. No manufacturer-color matching is provided. PDF charts are guides, not physical-scale placement templates. Keep backups outside the app before removing it or permanently deleting projects.

Designed and engineered by **Sepideh Javanbakht Dalir** · [Arvinify](https://www.arvinify.com) · [hello@arvinify.com](mailto:hello@arvinify.com)
