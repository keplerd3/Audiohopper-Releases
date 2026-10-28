# Third-party licenses and notices

The distributed application contains the version-matched notices, license texts
and applicable source materials under:

`Audiohopper.app/Contents/Resources/licenses/`

The following public sources and materials describe the fixed v0.1.0-beta.1
artifact. These records are provided for attribution and source access; they do
not grant rights in user-supplied audio, documents, or dictionaries.

## Electron, Chromium and Node.js

The application uses Electron 44.7.0. Electron's official release record lists
Chromium 152.0.7977.130 and Node.js 24.21.0. The unmodified Electron license
and Chromium third-party notices are included in the app.

- Electron release: <https://releases.electronjs.org/release/v44.7.0>
- Electron source license: <https://github.com/electron/electron/blob/v44.7.0/LICENSE>
- Node.js license: <https://github.com/nodejs/node/blob/v24.21.0/LICENSE>

## Python, MLX and Whisper

The bundled Python runtime is CPython 3.12.14. Its supplied license and the
license records carried by packaged libraries remain in the app. The release
uses MLX 0.32.3, mlx-metal 0.32.3 and mlx-whisper 0.4.3.

The fixed model is `mlx-community/whisper-large-v3-turbo-q4` revision
`660c343bbf4e52ac257f0b7d952e5388e6f93bef`. It is a 4-bit MLX conversion of
OpenAI Whisper Large-v3-turbo. The OpenAI Whisper MIT notice and MLX examples
MIT notice are included in the app.

- Model card: <https://huggingface.co/mlx-community/whisper-large-v3-turbo-q4/tree/660c343bbf4e52ac257f0b7d952e5388e6f93bef>
- Upstream model card: <https://huggingface.co/openai/whisper-large-v3-turbo>
- OpenAI Whisper MIT license: <https://github.com/openai/whisper/blob/main/LICENSE>
- MLX examples license: <https://github.com/ml-explore/mlx-examples/blob/main/LICENSE>
- CPython license: <https://docs.python.org/3/license.html>

## FFmpeg

The bundled standalone ARM64 FFmpeg CLI is based on FFmpeg 8.0.3 and was built
with GPL and nonfree features disabled. It is distributed under LGPL 2.1 or
later. The app includes the source archive, its checksum, the LGPL text, and
build information.

- Source archive: <https://ffmpeg.org/releases/ffmpeg-8.0.3.tar.xz>
- Archive SHA-256: `6136812ea6d4e68bdba27e33c2a94382711cdf4f8602ffef056ff792bd6f9818`
- Licensing information: <https://ffmpeg.org/legal.html>

## SciPy and GCC runtime libraries

The bundled SciPy 1.18.1 ARM64 wheel includes dynamically linked
`libgcc_s.1.1.dylib`, `libgfortran.5.dylib`, and `libquadmath.0.dylib`. The app
includes the applicable license records, GNU GCC 13.4.0 source archive and a
relinking notice. `libgcc` and `libgfortran` use the GCC Runtime Library
Exception; `libquadmath` is LGPL-2.1-or-later.

- GCC 13.4.0 source: <https://ftpmirror.gnu.org/gcc/gcc-13.4.0/gcc-13.4.0.tar.xz>
- GCC source SHA-256: `9c4ce6dbb040568fdc545588ac03c5cbc95a8dbf0c7aa490170843afb59ca8f5`
- GCC licensing: <https://www.gnu.org/licenses/gcc-exception-3.1.html>
- SciPy license: <https://github.com/scipy/scipy/blob/v1.18.1/LICENSE.txt>

## Fonts, Unicode and JavaScript packages

Bundled Merriweather, Source Serif 4 and Literata fonts retain their SIL Open
Font License files in the application. The included Unicode notice is Unicode
License v3. Production JavaScript dependency notices are generated from the
packages actually included in the app.

User-provided MDX/MDD dictionaries are data files and are not part of this
distribution. Do not redistribute a dictionary unless its own license permits
it.
