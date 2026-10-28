# Source and relinking information

This page identifies the source materials supplied in the application and the
public locations from which recipients can obtain the corresponding source.

## FFmpeg

The application includes FFmpeg 8.0.3 source, LGPL text, archive checksum and
build information under `Contents/Resources/licenses/ffmpeg/`.

- Source: <https://ffmpeg.org/releases/ffmpeg-8.0.3.tar.xz>
- Signature: <https://ffmpeg.org/releases/ffmpeg-8.0.3.tar.xz.asc>
- SHA-256: `6136812ea6d4e68bdba27e33c2a94382711cdf4f8602ffef056ff792bd6f9818`

The app runs FFmpeg as a separate executable process. The recorded build uses
ARM64 Darwin settings and disables GPL and nonfree features.

## GCC runtime libraries carried by SciPy

The application includes GNU GCC 13.4.0 source, the relevant SciPy/GCC license
record and a relinking notice under `Contents/Resources/licenses/gcc/` and
`Contents/Resources/licenses/audiohopper/`.

- Source: <https://ftpmirror.gnu.org/gcc/gcc-13.4.0/gcc-13.4.0.tar.xz>
- SHA-256: `9c4ce6dbb040568fdc545588ac03c5cbc95a8dbf0c7aa490170843afb59ca8f5`

The runtime libraries are dynamically loaded from SciPy's `.dylibs` directory.
A compatible replacement must preserve the existing filenames and dynamic
install-name relationships. Modifying an installed app invalidates its original
code signature; a recipient who distributes a modified copy is responsible for
signing that modified copy appropriately. This does not require disabling macOS
security protections on the original app.

## Whisper model

The bundled MLX Whisper artifact and notices are identified in
[THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md). Its fixed revision and
file hashes are recorded there through public upstream links. The OpenAI Whisper
and MLX conversion-tool notices are included in the app.
