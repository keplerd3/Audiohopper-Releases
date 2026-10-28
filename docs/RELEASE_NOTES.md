# Audiohopper v0.1.0-beta.1 — macOS Apple Silicon Beta

Audiohopper is an offline-first desktop English dictation tool for documents,
audio, and video. This Beta is for Apple Silicon Macs.

## Included

- Import EPUB, text-layer PDF, MOBI, plain text, common audio, and common
  video files.
- Review extracted text before practice, then practise sentence by sentence
  with playback, Peek, progress, scoring, and local dictionaries.
- Audio and video are transcribed locally. Imported source files remain at
  their original locations rather than being copied into the app library.

## Known Beta limitations

- Repeating local recognition may remove orange `//` sentence-break markers.
  The current workaround is to remove and re-import that article.
- After you manually change sentence breaks, the audio boundary for an edited
  sentence may not be exact.

## Build identity

The verified software artifact was built from private development commit
`ac4f01b`. This public distribution repository contains release records and
public materials only; it does not contain the private development source
history.

## macOS security notice

This Beta is ad-hoc signed and is not Apple-notarized. macOS may show a
Gatekeeper warning when it is first opened. Follow the installation guide; do
not disable Gatekeeper system-wide.
