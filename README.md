<picture><source media="(prefers-color-scheme: dark)" srcset="assets/icon-github-dark.png"><img src="assets/icon-github.png" width="128" alt="offline-stt icon: the microphone of the dictation key"></picture>

# Offline STT

Turns audio or video into text or subtitles offline with local speech models, and keeps a dictation dictionary accurate.

## Install

Terminal agents:

```sh
npx skills add geragarazagh/offline-stt -g
```

Claude Code:

```sh
claude plugin marketplace add geragarazagh/offline-stt
claude plugin install offline-stt@offline-stt
```

Gemini CLI:

```sh
gemini extensions install https://github.com/geragarazagh/offline-stt
```

Any other agent: paste the text of [`SKILL.md`](skills/offline-stt/SKILL.md) into its instructions.
