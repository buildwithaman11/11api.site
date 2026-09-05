# 11API — Voiceover Timeline

A free, in-browser AI voiceover tool. Write lines and generate voice instantly, or drop in a video and pin voice lines to the exact second you need them — all running client-side, with nothing ever uploaded to a server.

## ✨ Features

- **Two modes, one click apart**
  - 🎙 **Voiceover only** — write a line, generate the voice, download the audio. No video needed.
  - 🎬 **Video + Voiceover** — load a video, play it, pause where you want a line, and pin it to that exact timestamp on a visual timeline. Drag either edge of a marker to adjust timing, or drag the middle to move it.
- **Bring your own API key(s)** — works with **ElevenLabs** or **Gemini** TTS. Save multiple API keys per provider, label them, and switch between them anytime — no sign-in, no re-authentication, ever.
- **Live connection status** — a simple indicator shows whether your active API key is connected and working.
- **Quota tracking** — see remaining ElevenLabs character quota or Gemini token usage at a glance, so you know before you hit a limit.
- **Voice preview** — audition any voice before generating your full line.
- **Fast audio export** — download your generated voice lines as a zipped set of audio files, named by order (and by timestamp in video mode), ready to drop into any video editor.
- **100% client-side** — your video file and API keys never leave your browser. Keys are stored only in local storage and sent directly to the provider's API.
- **Change video anytime** — swap out the loaded video without losing your existing voice lines.

## 🚀 Getting started

1. Open `index.html` in any modern browser (or host it as a static site).
2. Click **⚙ Voice engine settings**, choose ElevenLabs or Gemini, and add your API key.
3. Pick **🎙 Voiceover only** to just generate lines, or **🎬 Video + Voiceover** to sync them to a video.
4. Generate your voice lines, preview them, and download the audio when you're ready.

No build step, no dependencies to install — it's a single static HTML file.

## 🔒 Privacy

- No backend, no analytics, no tracking.
- Videos are processed entirely in your browser and never uploaded anywhere.
- API keys are stored only in your browser's local storage and sent directly to ElevenLabs/Google — never to any server of ours (there isn't one).

## 🛠 Built with

- Vanilla JavaScript (no framework)
- [ElevenLabs API](https://elevenlabs.io/) / [Google Gemini API](https://ai.google.dev/) for text-to-speech
- [JSZip](https://stuk.github.io/jszip/) for packaging audio downloads

## 📄 License

MIT License

Copyright (c) 2026 Aman Babu Singh (buildwithaman11)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
