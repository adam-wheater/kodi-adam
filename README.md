<p align="center">
  <img src="tools/android/packaging/media/playstore.png" width="120" alt="Logo"/>
</p>

# Kodi Adam

A custom Android build of [Kodi](https://kodi.tv/) with a curated set of plugins and a custom skin pre-installed — ready to use out of the box.

## Download

**[https://is.gd/eiVWyF](https://is.gd/eiVWyF)**

Download the latest APK from the link above and sideload it onto your Android device or Fire TV Stick.

> Enable **Unknown Sources** (or **Install from Unknown Sources**) in your device settings before installing.

---

## What's included

### Skin
| Addon | Description |
|---|---|
| [FENtastic](https://github.com/ivarbrandt/skin.fentastic) | Clean Estuary-based skin designed for use with FENlight |

### Video
| Addon | Description |
|---|---|
| [FENlight](https://tikipeter.github.io/) | Lightweight real-debrid powered video addon |

### Scrapers
| Addon | Description |
|---|---|
| [CocoScrapers](https://github.com/CocoJoe2411/repository.cocoscrapers) | Multi-source scraper module |

### Subtitles
| Addon | Description |
|---|---|
| OpenSubtitles.com (Dual Subs) | Subtitles from OpenSubtitles.com with dual subtitle support |
| OpenSubtitles.org (Dual Subs) | Subtitles from OpenSubtitles.org with dual subtitle support |
| LocalSubtitle | Load subtitles from local storage |

### Utilities
| Addon | Description |
|---|---|
| [EZ Maintenance+](https://github.com/peno64/repository.peno64) | Cache clearing, log viewer, maintenance tools |
| RealDebrid | RealDebrid account management & context menu |
| RealDebrid VPN Info | Shows VPN status for RealDebrid |
| Fix IPTV Manager | Fixes IPTV Manager configuration issues |

---

## Build

The APK is built automatically via GitHub Actions on every push to `main` and released on version tags.

To cut a release:
```bash
git tag v1.0.0 && git push origin v1.0.0
```

[![Build Android APK](https://github.com/adam-wheater/kodi-adam/actions/workflows/build-android-apk.yml/badge.svg)](https://github.com/adam-wheater/kodi-adam/actions/workflows/build-android-apk.yml)

---

## License

Kodi is licensed under the [GPL v2](LICENSE.md). All bundled third-party addons retain their respective licenses.
