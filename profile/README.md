<picture>
  <source media="(prefers-color-scheme: dark)" srcset="viewgum-lockup-dark.svg">
  <img src="viewgum-lockup-light.svg" alt="viewgum" height="44">
</picture>

ViewGum makes vertical short videos from a topic: script, voice, pictures, captions and sound, sized for TikTok, Instagram Reels,
YouTube Shorts and Facebook Reels. You edit them in chat or on a timeline, or from your AI assistant.

| Repository | What it is |
|---|---|
| [short-form-video-specs](https://github.com/viewgum/short-form-video-specs) | Safe zones in pixels for TikTok, Shorts and Reels, length and caption limits, PNG overlay templates, a JavaScript module and a CLI, with each figure's source and the date it was read. Free, works offline |
| [shortform-preflight](https://github.com/viewgum/shortform-preflight) | Checks a video file against the upload limits TikTok, YouTube Shorts, Instagram Reels and Facebook Reels publish, with the source for each figure: a CLI, a GitHub Action and a JavaScript module on ffprobe. Free |
| [skills](https://github.com/viewgum/skills) | Agent skills and the ViewGum MCP connector for Claude Code, Codex, Gemini CLI and other agents. Seven skills work with no account (specs, scripts, hooks, post copy, upload checks, AI labels); making videos needs a paid ViewGum plan and credits |
| [business-video-skills](https://github.com/viewgum/business-video-skills) | Short video plans for small businesses: twelve skills that turn a few lines about a business into 15 video ideas and a 30-day calendar, with 35 ad and claim rules by industry, each with its source, and a claim checker. Free, no account |
| [ffmpeg-vertical-video](https://github.com/viewgum/ffmpeg-vertical-video) | Tested FFmpeg commands for 9:16 video: 16:9 to 9:16, one export for every app's upload specs, captions inside the safe zone, compression to a size, loudness and more, each run in CI on generated clips. Also an agent skill |
| [short-form-captions](https://github.com/viewgum/short-form-captions) | Word timestamps from Whisper and other speech-to-text tools to SRT, WebVTT or ASS captions inside the safe zone, with word highlighting, and a caption checker against Netflix and BBC subtitle guidelines. A CLI, a JavaScript module and an agent skill |
| [awesome-small-business-video](https://github.com/viewgum/awesome-small-business-video) | Official, free resources for small businesses making short vertical videos: each app's business help, music a business may use, the rules for ads, endorsements, fake reviews and AI labels, and free editing apps, each with a quote and the day it was read |
| [awesome-short-form-video](https://github.com/viewgum/awesome-short-form-video) | A list of open tools and official docs for making vertical video with code, the command line or agents, every link checked |
| [short-form-script-benchmark](https://github.com/viewgum/short-form-script-benchmark) | An open method for testing how AI models write 30 to 60 second scripts for TikTok, Shorts and Reels: briefs, rubric, checks, scoring and a runner |

[viewgum.com](https://viewgum.com) · [Free tools](https://viewgum.com/tools) · [Connect an AI assistant](https://viewgum.com/agents) ·
[X](https://x.com/getviewgum)
