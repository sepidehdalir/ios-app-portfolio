# Obscut: Censor Video

**Cover a private phrase on screen and mute it in the same clip.**

Obscut is an iPhone and iPad prototype for creators and sellers who share short screen recordings. The editor looks for a phrase in sampled video frames and spoken audio. The user reviews the findings before rendering a separate copy.

## Product decisions

- One search phrase for both channels, with an optional spoken variant for details read aloud.
- A review step before sharing because fast-moving text and unclear speech can be missed.
- A free watermarked preview and a one-time purchase for saving or sharing a clean MP4.

## Engineering

SwiftUI handles import and review. Vision proposes on-screen regions, Speech supplies timestamped candidates on supported devices and languages, and AVFoundation and Core Image apply the selected masks and mute ranges. StoreKit 2 verifies clean-export access.

The prototype uses a synthetic clip with a phrase shown on screen and spoken aloud. The packaged project and fixture were checked, with iPhone rendering, speech recognition and purchase testing pending.

## Release status

In development as of November 27, 2026. App Store submission pending.

[← All iOS projects](../README.md)
