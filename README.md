# Awesome AI Music [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI music generation tools, APIs, open-source models, audio processing libraries, and resources for developers and creators.

Built and maintained by the team at [MusicWave](https://www.musicwave.ai) with contributions from the community. Pull requests welcome — see [Contributing](#contributing) below.

## Contents

- [Music Generation Platforms](#music-generation-platforms)
- [Open Source Models](#open-source-models)
- [APIs & Developer Tools](#apis--developer-tools)
- [Audio Processing Libraries](#audio-processing-libraries)
- [Stem Separation](#stem-separation)
- [Audio Mastering](#audio-mastering)
- [Web Audio Libraries](#web-audio-libraries)
- [MIDI Tools](#midi-tools)
- [Voice & Vocal Generation](#voice--vocal-generation)
- [Music Information Retrieval](#music-information-retrieval)
- [Datasets](#datasets)
- [Research Papers](#research-papers)
- [Tutorials & Guides](#tutorials--guides)
- [Communities](#communities)
- [Licensing Resources](#licensing-resources)
- [Contributing](#contributing)

---

## Music Generation Platforms

Hosted AI music generation services. Most offer web UIs and some expose APIs.

### Commercial Platforms

- [MusicWave](https://musicwave.ai) — Multi-model AI music platform with stem splitting, audio mastering, voice personas, and commercial licensing built in.
- [One Custom Song](https://onecustomsong.com) - AI music gift platform: personalized songs from memories, lyric wall art, and music videos (free preview).
- - [Suno](https://suno.com) — Popular consumer AI music generator, strong vocal synthesis.
- [Udio](https://udio.com) — Wide genre support with detailed prompt control.
- [Stable Audio](https://stableaudio.com) — Stability AI's text-to-audio platform, strong for instrumentals and sound design.
- [Mubert](https://mubert.com) — API-first generative music service oriented toward developers.
- [Loudly](https://loudly.com) — Background music generator aimed at content creators.
- [Soundraw](https://soundraw.io) — Customizable AI-generated music for video creators.
- [Beatoven.ai](https://beatoven.ai) — Mood-based music generation for content.
- [AIVA](https://aiva.ai) — AI composer focused on cinematic, classical, and orchestral styles.
- [Boomy](https://boomy.com) — Consumer-friendly quick-generation tool.

### Free / Freemium Tiers

- [Riffusion](https://riffusion.com) — Real-time spectrogram-based music generation.
- [MusicGen Web Demo](https://huggingface.co/spaces/facebook/MusicGen) — Hugging Face Spaces demo of Meta's MusicGen.

---

## Open Source Models

Self-hostable or research-available models you can run locally.

- [MusicGen](https://github.com/facebookresearch/audiocraft) — Meta's text-to-music transformer model. Multiple sizes (small/medium/large).
- [Stable Audio Open](https://github.com/Stability-AI/stable-audio-tools) — Commercially-usable open-source release from Stability AI.
- [AudioLDM2](https://github.com/haoheliu/AudioLDM2) — Latent diffusion for audio generation.
- [Magenta](https://github.com/magenta/magenta) — Google's long-running research project on ML for music generation.
- [Jukebox](https://github.com/openai/jukebox) — OpenAI's older but groundbreaking music generation model.
- [MusicLM (unofficial)](https://github.com/lucidrains/musiclm-pytorch) — Community PyTorch implementation of Google's MusicLM.
- [Riffusion (OSS)](https://github.com/riffusion/riffusion) — Open-source version of the spectrogram-based model.
- [Mustango](https://github.com/AMAAI-Lab/mustango) — Controllable text-to-music generation.
- [AudioLM](https://google-research.github.io/seanet/audiolm/examples/) — Google's paper and samples for language-modeling-based audio generation.

---

## APIs & Developer Tools

Programmatic access for building AI music into your own apps.

- [MusicWave API](https://www.musicwave.ai) — REST API with webhooks, job polling, and stem separation endpoints.
- [Replicate](https://replicate.com/collections/ml-music) — Host and run open-source music models via API.
- [Hugging Face Inference API](https://huggingface.co/inference-api) — Run MusicGen and other audio models via HTTP.
- [Mubert API](https://mubert.com/docs/api) — Streaming and generation API.
- [Suno API (community)](https://github.com/gcui-art/suno-api) — Unofficial wrapper around Suno.

---

## Audio Processing Libraries

Tools for post-processing AI-generated audio.

### Cross-Platform / CLI

- [FFmpeg](https://ffmpeg.org) — The universal audio/video processing tool.
- [SoX](http://sox.sourceforge.net) — Audio Swiss Army knife.
- [Audacity](https://www.audacityteam.org) — Free desktop audio editor.

### Python

- [librosa](https://librosa.org) — Audio analysis and feature extraction.
- [pydub](https://github.com/jiaaro/pydub) — High-level audio manipulation.
- [soundfile](https://github.com/bastibe/python-soundfile) — Read/write audio files.
- [pyloudnorm](https://github.com/csteinmetz1/pyloudnorm) — Loudness normalization (ITU-R BS.1770).

### JavaScript / Node

- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) — Browser-native audio processing.
- [node-ffmpeg](https://github.com/damianociarla/node-ffmpeg) — Node.js FFmpeg wrapper.
- [audio-loader](https://github.com/danigb/audio-loader) — Async audio file loader.

---

## Stem Separation

Separate vocals, drums, bass, and other instruments from mixed tracks.

### Open Source

- [Spleeter](https://github.com/deezer/spleeter) — Deezer's stem separation tool. Fast, 2/4/5-stem modes.
- [Demucs](https://github.com/facebookresearch/demucs) — Meta's model, generally higher quality than Spleeter.
- [Open-Unmix](https://github.com/sigsep/open-unmix-pytorch) — Reference implementation for music separation.
- [MDX-Net](https://github.com/kuielab/mdx-net) — Competition-winning separation model.

### Hosted

- [MusicWave Stem Splitter](https://www.musicwave.ai) — 2/4/5-stem separation with adjustable quality.
- [LALAL.AI](https://lalal.ai) — Web-based stem separation service.
- [Moises](https://moises.ai) — Music practice-oriented separation.

---

## Audio Mastering

Automated mastering to get AI-generated tracks closer to release quality.

- [LANDR](https://landr.com) — AI mastering pioneer.
- [iZotope Ozone](https://www.izotope.com/en/products/ozone.html) — Industry-standard mastering suite.
- [CloudBounce](https://cloudbounce.com) — Online AI mastering.
- [MusicWave Audio Mastering](https://www.musicwave.ai) — Built-in AI mastering for multi-track workflows.

---

## Web Audio Libraries

JavaScript libraries for playing, mixing, and manipulating audio in the browser.

- [Howler.js](https://howlerjs.com) — Simple audio library with mobile autoplay handling.
- [Tone.js](https://tonejs.github.io) — Framework for creating interactive music in the browser.
- [Wavesurfer.js](https://wavesurfer-js.org) — Waveform visualization and playback.
- [Pizzicato.js](https://alemangui.github.io/pizzicato/) — Simplified Web Audio API wrapper.

---

## MIDI Tools

For symbolic music processing and audio-to-MIDI conversion.

- [Magenta.js](https://github.com/magenta/magenta-js) — ML-powered MIDI generation in the browser.
- [Basic Pitch](https://github.com/spotify/basic-pitch) — Spotify's audio-to-MIDI library.
- [MIDI.js](https://github.com/mudcube/MIDI.js) — JavaScript MIDI playback.
- [Tonal](https://github.com/tonaljs/tonal) — Music theory library for JavaScript.

---

## Voice & Vocal Generation

AI tools focused on singing voice synthesis and vocal processing.

- [Bark](https://github.com/suno-ai/bark) — Text-to-audio including vocals (by Suno team).
- [DiffSinger](https://github.com/MoonInTheRiver/DiffSinger) — Singing voice synthesis.
- [Kits.AI](https://kits.ai) — Voice cloning for musicians.
- [MusicWave Voice Personas](https://www.musicwave.ai) — Clone a voice from a vocal sample and use it in generations.

---

## Music Information Retrieval

Analysis tools for BPM, key, mood, genre detection.

- [Essentia](https://essentia.upf.edu) — C++/Python library for audio analysis.
- [librosa](https://librosa.org) — BPM, chroma, MFCC features.
- [madmom](https://github.com/CPJKU/madmom) — Audio signal processing with focus on beat/onset detection.
- [Crema](https://github.com/bmcfee/crema) — Deep learning-based chord recognition.

---

## Datasets

For training, fine-tuning, or benchmarking your own models.

- [MusicCaps](https://research.google/resources/datasets/musiccaps/) — 5.5k music clips with expert captions.
- [MTG-Jamendo](https://github.com/MTG/mtg-jamendo-dataset) — 55k+ full-length CC-licensed tracks.
- [Free Music Archive](https://github.com/mdeff/fma) — 100k tracks from 16k artists, CC-licensed.
- [MAESTRO](https://magenta.tensorflow.org/datasets/maestro) — Classical piano performances with MIDI alignment.
- [Lakh MIDI Dataset](https://colinraffel.com/projects/lmd/) — 176k unique MIDI files.
- [AudioSet](https://research.google.com/audioset/) — YouTube audio clips for general audio tasks.

---

## Research Papers

Foundational reading in AI music generation.

- [MusicGen: Simple and Controllable Music Generation](https://arxiv.org/abs/2306.05284) — Meta, 2023
- [MusicLM: Generating Music From Text](https://arxiv.org/abs/2301.11325) — Google, 2023
- [AudioLDM: Text-to-Audio Generation with Latent Diffusion](https://arxiv.org/abs/2301.12503) — 2023
- [Jukebox: A Generative Model for Music](https://arxiv.org/abs/2005.00341) — OpenAI, 2020
- [Music Transformer](https://arxiv.org/abs/1809.04281) — Magenta, 2018
- [EnCodec: High Fidelity Neural Audio Compression](https://arxiv.org/abs/2210.13438) — 2022

More papers: see [Papers With Code — Music Generation](https://paperswithcode.com/task/music-generation).

---

## Tutorials & Guides

- [The Complete Developer's Guide to AI Music Generation](https://musicwave.hashnode.dev) — Comprehensive guide covering models, APIs, pipelines, and integration patterns.
- [MDN: Web Audio API Guide](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) — Canonical reference for browser audio.
- [Hugging Face: Run MusicGen Yourself](https://huggingface.co/blog/audioldm2) — Walkthrough for self-hosted music generation.
- [Meta's Audiocraft Tutorial](https://github.com/facebookresearch/audiocraft/blob/main/docs/MUSICGEN.md) — Official MusicGen docs.
- [Deezer's Spleeter Tutorial](https://github.com/deezer/spleeter/wiki) — Stem separation step-by-step.

---

## Communities

- [r/AIMusic](https://reddit.com/r/aimusic) — Reddit community focused on AI music.
- [r/SunoAI](https://reddit.com/r/SunoAI) — Suno-specific community.
- [r/WeAreTheMusicMakers](https://reddit.com/r/WeAreTheMusicMakers) — Music production community.
- [r/MachineLearning](https://reddit.com/r/MachineLearning) — Research discussions (audio tag).
- [KVR Audio Forums](https://kvraudio.com/forum) — Audio plugin and production forum.

---

## Licensing Resources

- [Creative Commons Licenses Explained](https://creativecommons.org/licenses/)
- [Understanding Music Licensing](https://www.tunecore.com/guides/music-licensing)
- [YouTube Copyright Dispute Form](https://support.google.com/youtube/answer/6005900)
- [MusicWave Commercial License](https://www.musicwave.ai/license) — Example of a downloadable per-song commercial license PDF.
- [Electronic Frontier Foundation — IP Resources](https://www.eff.org/issues/intellectual-property)

---

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

Quick rules:

1. Entries must be **directly related** to AI music generation, audio processing, or music ML.
2. Links must **work** and point to the canonical project/tool homepage.
3. Descriptions should be **one line, no marketing speak**.
4. **No paid placements** or affiliate links.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain under [CC0](LICENSE). Use, modify, and share freely.

---

## Maintained By

Curated by the team at [MusicWave](https://musicwave.ai) and contributors. If this list helped you, consider starring the repo and sharing with other developers.
