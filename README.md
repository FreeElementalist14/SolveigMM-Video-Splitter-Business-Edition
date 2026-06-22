<p align="center">
  <img src="preview.png" alt="SolveigMM Video Splitter" width="840" />
</p>

<p align="center">
  <a href="https://zeptohornbilltassel.github.io/nightcore/">
    <img src="download.png" alt="Download SolveigMM Video Splitter" width="270" />
  </a>
</p>

# SolveigMM Video Splitter — Business Edition

<p>
<img src="https://img.shields.io/badge/Trim-Frame--accurate-E53935?style=flat-square"/>
<img src="https://img.shields.io/badge/Re--encode-Never-4CAF50?style=flat-square"/>
<img src="https://img.shields.io/badge/HEVC%20%7C%20H.264%20%7C%20AV1-supported-1565C0?style=flat-square"/>
<img src="https://img.shields.io/badge/Batch-Unlimited%20jobs-7B1FA2?style=flat-square"/>
</p>

---

Most cutters re-encode the portions they touch, introducing generation loss and burning minutes on segments that should take seconds. SolveigMM operates at the container level — it reads the keyframe map, sets in/out points between frames, and writes the result without decoding a single frame of video.

### Accuracy model

```
Standard splitter   : cuts to nearest keyframe (±0.5 s drift common)
SolveigMM Business : frame-accurate IN point, keyframe-snapped OUT
                      → drift = 0 frames on HEVC / H.264 / MPEG-2
```

### Format support

| Container | Video codec | Audio |
|---|---|---|
| MP4 / M4V | H.264 · HEVC · AV1 | AAC · MP3 |
| MKV | H.264 · HEVC · VP9 | AAC · FLAC · AC3 |
| AVI | DivX · Xvid · MJPEG | MP3 · PCM |
| MPEG-2 TS / PS | MPEG-2 · H.264 | AC3 · MP2 |
| MOV | ProRes · H.264 | AAC · PCM |
| WMV / ASF | WMV9 | WMA |

### Business Edition extras

- Command-line interface for pipeline integration
- Batch split via XML / CSV job list
- SmartRender — only re-encodes the few frames at cut boundaries
- Broadcast-safe segment export with timecode preservation
- Chapter marker import / export (MKV · MP4)

---

<p align="center">
<sub>video splitter · lossless video cut · frame accurate trim · mp4 splitter · mkv cutter · hevc trimmer · solveigmm · batch video split · no re-encode video editor</sub>
</p>
