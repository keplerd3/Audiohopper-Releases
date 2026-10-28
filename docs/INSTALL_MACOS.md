# Install Audiohopper on macOS

## Requirements

- An Apple Silicon Mac (M-series)
- A macOS version capable of running this ARM64 application
- Enough free disk space for the app and its bundled offline recognition model

## Install

1. Check the downloaded DMG against `SHA256SUMS.txt`.
2. Open `Audiohopper-0.1.0-beta.1-macOS-arm64.dmg`.
3. Drag `Audiohopper.app` to Applications, then eject the DMG.
4. Open Audiohopper from Applications.

## Gatekeeper message

This Beta has an ad-hoc signature and is not notarized by Apple. If macOS says
it cannot verify the developer, do not turn off Gatekeeper for the whole Mac.
Instead, find Audiohopper in Applications, Control-click it, choose **Open**,
then confirm **Open** in the next dialog. macOS may require this once.

If macOS reports that the app is damaged, or the checksum does not match, stop
and download a fresh copy from this release.

## First use

Import a document, audio, or video from the library. Original source files
remain in their original folders. For audio and video, wait for local
recognition to finish before choosing **Continue review**. Review the text,
select **Complete review**, then start dictation when the material is ready.
