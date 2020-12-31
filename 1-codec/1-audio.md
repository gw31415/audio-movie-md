# 音声コーデック

## 無劣化、可逆圧縮

コーデック | ffmpeg での識別子 | ライセンス / 特許 | 圧縮
--- | --- | --- | ---
PCM 16bit | `pcm_s16le` | - | なし
PCM 24bit | `pcm_s24le` | - | なし
FLAC | `flac` | オープン.<br/>ライブラリが修正BSD. | 50~100% <br/> (9段階)
ALAC | `alac` | Apache 2.0 | 50~70% <br/> (固定)

## 非可逆圧縮

上から品質がいいと言われている順

コーデック | ffmpeg での識別子 | ライセンス / 特許
--- | --- | ---
Opus | `opus` | オープン. <br/> ライブラリが修正BSD.
AAC | `aac` | 特許あり
Vorbis| `vorbis` | オープン. <br/> ライブラリが修正BSD.
MP3 | `mp3` <br/> `libmp3lame` | ライセンス問題があり.