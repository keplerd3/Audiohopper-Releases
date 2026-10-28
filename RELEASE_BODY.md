# Audiohopper v0.1.0-beta.1 — macOS Apple Silicon Beta

Audiohopper is an offline-first desktop English dictation tool for documents,
audio, and video. This Beta supports Apple Silicon Macs only.

## Download and verify

1. Download `Audiohopper-0.1.0-beta.1-macOS-arm64.dmg`.
2. Verify it against `SHA256SUMS.txt`.
3. Read `INSTALL_MACOS.md` before installation.

SHA-256:

`9387888fdc076beaaa05693560f715e76af014cc1a40ab6ad8ee5a1d0c09a64e`

## Important macOS notice

This Beta is ad-hoc signed and is **not Apple-notarized**. macOS may show a
Gatekeeper warning on first launch. Follow the per-app Control-click **Open**
instructions in `INSTALL_MACOS.md`; do not disable Gatekeeper system-wide.

## Known Beta issues

- Repeating local recognition can remove orange `//` sentence-break markers.
  Removing and re-importing that article is the current workaround.
- After manually changing sentence breaks, audio boundaries for edited
  sentences may be imperfect.

## Included public release material

- `SHA256SUMS.txt`
- `INSTALL_MACOS.md`
- `RELEASE_NOTES.md`
- `KNOWN_ISSUES.md`
- `THIRD_PARTY_LICENSES.md`
- `SOURCE_ACCESS.md`

The actual software build was produced from private development commit
`ac4f01b`. This public release repository deliberately does not mirror the
private development source history.
