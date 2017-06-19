# sample-rate  [![stable](https://img.shields.io/badge/stability-stable-brightgreen.svg)](http://github.com/badges/stability-badges) [![Build Status](https://img.shields.io/travis/audiojs/sample-rate.svg)](https://travis-ci.org/audiojs/sample-rate)

List of common sample rates.

| Sample rate | Meaning |
|---|---|
| 8,000 Hz | Adequate for human speech but without sibilance. Used in telephone/walkie-talkie. |
| 11,025 Hz | Used for lower-quality PCM, MPEG audio and for audio analysis of subwoofer bandpasses. |
| 16,000 Hz | Used in most VoIP and VVoIP, extension of telephone narrowband. |
| 22,050 Hz | Used for lower-quality PCM and MPEG audio and for audio analysis of low frequency energy. |
| 44,100 Hz | Audio CD, most commonly used rate with MPEG-1 audio (VCD, SVCD, MP3). Covers the 20 kHz bandwidth. |
| 48,000 Hz | Standard sampling rate used by professional digital video equipment, could reconstruct frequencies up to 22 kHz. |
| 88,200 Hz | Used by some professional recording equipment when the destination is CD, such as mixers, EQs, compressors, reverb, crossovers and recording devices. |
| 96,000 Hz | DVD-Audio, LPCM DVD tracks, Blu-ray audio tracks, HD DVD audio tracks. |
| 176,400 Hz | Used in HDCD recorders and other professional applications for CD production. |
| 192,000 Hz | Used with audio on professional video equipment. DVD-Audio, LPCM DVD tracks, Blu-ray audio tracks, HD DVD audio tracks. |
| 352,800 Hz | 	Digital eXtreme Definition. Used for recording and editing Super Audio CDs. |
| 384,000 Hz | Highest sample rate available for common software. Allows for precise peak detection. |

[![npm install sample-rate](https://nodei.co/npm/sample-rate.png?mini=true)](https://npmjs.org/package/sample-rate/)

```js
const rates = require('sample-rate')

rates // [8000, 11025, ... 384000]
```

See [sample rates table](https://en.wikipedia.org/wiki/Sampling_(signal_processing)).
