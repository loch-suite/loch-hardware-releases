# loom-hardware-releases

Public release artifacts for [Loom Hardware](https://github.com/loom-suite/loom-hardware).

This repo hosts installers and the `latest.json` update manifest consumed by the app's auto-updater.

## Installing

Download the latest installer from the [Releases](https://github.com/loom-suite/loom-hardware-releases/releases) page.

## Auto-updates

Installed copies of Loom Hardware check this endpoint on launch:

```
https://raw.githubusercontent.com/loom-suite/loom-hardware-releases/refs/heads/main/latest.json
```
