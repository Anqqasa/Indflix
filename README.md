# VidriftStream — VidRift-first fork of IndStream, for SinemaKu

This repository is a fork of [dipender98/Indflix](https://github.com/dipender98/Indflix)
(IndStream v107, commit `9484d16`). It contains **only** the IndStream plugin,
renamed to **VidriftStream**, with one behaviour change: the VidRift server is
tried first for every title (2s head start); the remaining servers run only if
VidRift produces nothing. If VidRift fails, the plugin behaves exactly like
stock IndStream. See [FORK.md](FORK.md) for what changed, how to build, and
how the weekly upstream sync works.

Upstream code is Copyright © 2026 dipender98, licensed GPL-3.0 (see
[LICENSE](LICENSE) and [NOTICE](NOTICE)).

## About

Indflix is a [CloudStream](https://github.com/recloudstream/cloudstream)
provider plugin for movies, TV series, anime, and cartoons. It races
multiple independent stream servers per title and exposes
**multi-language audio** — Hindi, English, Tamil, Telugu, dubbed, dual-audio.

New to CloudStream? Start with the [CloudStream Wiki](https://cloudstream.miraheze.org).

## Join the Telegram Group
(https://t.me/+zWzCcoj9q143NTBl).

## Install

CloudStream → **Settings** → **Extensions** → **Add repository**:

```
https://raw.githubusercontent.com/Anqqasa/Indflix/builds/repo.json
```

## Features

- 🌐 **Multi-language audio** — Hindi, English, Tamil, Telugu, Kannada,
  Malayalam, Bengali, dual-audio; each stream is labelled with its
  actual audio language
- 📺 **Full media support** — Movies, TV series, anime, anime movies,
  cartoons
- 🎯 **Quality gate** — streams below 720p filtered out; up to 4K

## License

[GPL-3.0](LICENSE) · [Third-party notices](NOTICE)

## DMCA

This is a **provider plugin** for the open-source
[CloudStream](https://github.com/recloudstream/cloudstream) app.
It does **not** host, upload, or redistribute any copyrighted media.
All stream URLs are resolved at runtime from third-party APIs
independent of this project.

These extensions function like an ordinary browser that fetches
video files from the internet. The content accessed is not hosted
by this repository or the CloudStream app. It is the sole
responsibility of the user to comply with their country's or
state's laws. If you believe content is violating intellectual
property, please contact the actual file hosts — not the owners
of this repository.

If you are a copyright holder and believe that **source code** in
this repository infringes your copyright, open an
[issue](https://github.com/Anqqasa/Indflix/issues).

## Credits

- [CloudStream](https://github.com/recloudstream/cloudstream) · [recloudstream](https://github.com/recloudstream)
- [CSX CineStream](https://github.com/SaurabhKaperwan/CSX) · [CSX Utils](https://github.com/SaurabhKaperwan/Utils)
- [CloudstreamExtensions](https://github.com/CloudstreamExtensions)
- [enc-dec.app](https://enc-dec.app) decryption endpoints

