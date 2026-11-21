> [!IMPORTANT]
> **Replaced by [`@arraypress/waveform-astro`](https://www.npmjs.com/package/@arraypress/waveform-astro) 2.0.** Import from `@arraypress/waveform-astro/bar` instead — one package per framework, with a sub-path per component ([repo](https://github.com/WaveformPlayer/astro), [migration guide](https://docs.waveformplayer.com/getting-started/migrating-from-1x/)).
> This repository is archived and the npm package is deprecated; its 1.x releases keep working.

<div align="center">

# Waveform Bar for Astro

**Astro components for the Spotify-style persistent bottom-bar audio player.**
Mount the bar once in your layout, then drop play/queue triggers anywhere.

[![npm version](https://img.shields.io/npm/v/@arraypress/waveform-bar-astro?style=flat-square&labelColor=09090b&color=3f3f46)](https://www.npmjs.com/package/@arraypress/waveform-bar-astro)
[![license](https://img.shields.io/npm/l/@arraypress/waveform-bar-astro?style=flat-square&labelColor=09090b&color=3f3f46)](https://github.com/arraypress)

**[Documentation](https://docs.waveformplayer.com/)** · [npm](https://www.npmjs.com/package/@arraypress/waveform-bar-astro)

</div>

---

## Install

```bash
npm install @arraypress/waveform-bar-astro @arraypress/waveform-bar @arraypress/waveform-player
```

```astro
---
import { WaveformBar, WaveformBarTrigger } from '@arraypress/waveform-bar-astro';
---
<WaveformBarTrigger url="/audio/track.mp3" title="My Track" artist="Producer" />

<!-- Render once, in your root layout -->
<WaveformBar />
```

## Documentation

Full props, the imperative API, and setup notes live in the docs.

### -> [docs.waveformplayer.com](https://docs.waveformplayer.com/)

[Astro guide](https://docs.waveformplayer.com/frameworks/astro/) — install, props, the imperative API, and SSR notes. All four Astro wrappers (player / bar / playlist) are on that page.

## License

MIT © [ArrayPress](https://github.com/arraypress)
