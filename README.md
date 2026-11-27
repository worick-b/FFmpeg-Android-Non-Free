# FFmpeg & FFprobe 8.1 Non-Free for Android
~Should I Stay or Should I Go

## Features

- **Offline & Ready-to-Package:**
  * Compiled without network protocols (`--disable-network`)
  * Static binaries packaged as `libffmpeg.so` and `libffprobe.so` (`arm64-v8a` and `armeabi-v7a`, API 28+)
- **Audio:**
  * `libfdk-aac` (**HE-AAC v2** `aac_he_v2`, `aac_he`, and `aac_lc`)
  * `libopus` (Opus)
  * `libmp3lame` (MP3)
- **Video:**
  * `MediaCodec` (Hardware-accelerated `h264_mediacodec` and `hevc_mediacodec`)
  * `libopenh264` (Universal software H.264 / AVC fallback under BSD license)
  * `libvpx` (VP8 and VP9 / WebM)
- **Native Filters and Formats:**
  * Native decoding for H.265 (HEVC), AV1, AVIF, WebP, MKV, MP4, AVI, OGV, FLAC, WAV, OGG, and WMA
  * Native video and audio filters (`scale`, `aresample`, `crop`, `fps`, etc.)
- **It's:** `A personal project, don't expect a dev master blaster (12" Version)`.
