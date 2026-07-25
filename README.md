# Zush — Scoop bucket

[![Tests](https://github.com/design-ninja/scoop-zush/actions/workflows/ci.yml/badge.svg)](https://github.com/design-ninja/scoop-zush/actions/workflows/ci.yml) [![Excavator](https://github.com/design-ninja/scoop-zush/actions/workflows/excavator.yml/badge.svg)](https://github.com/design-ninja/scoop-zush/actions/workflows/excavator.yml)

Official [Scoop](https://scoop.sh) bucket for **[Zush](https://zushapp.com)**, an AI file renamer
and batch rename tool for Windows that renames files by what they contain — PDFs, scans,
screenshots, photos, videos, audio and Office documents.

## Install

```pwsh
scoop bucket add zush https://github.com/design-ninja/scoop-zush
scoop install zush
```

## Update

```pwsh
scoop update zush
```

## Notes

- The package is the portable, self-contained build — no installer and no separate .NET runtime
  is required. Windows 10 version 2004 (build 19041) or newer; x64 and arm64 are both published.
- The archives are not code-signed, so Windows may show "Publisher: unknown" on first run. Zush is
  also on the Microsoft Store, where it is signed by Microsoft.
- Zush registers the `zush://` protocol for the current user on first launch so that returning from
  checkout activates your license automatically.
- Settings and logs live in `%LOCALAPPDATA%\Zush` and survive updates and uninstall.

## Links

- Website — <https://zushapp.com>
- Downloads — <https://github.com/design-ninja/zush-windows-releases/releases>
- Changelog — <https://zushapp.com/changelog/windows>
- Feature requests — <https://zush.canny.io>
- Support — support@zushapp.com

Zush is proprietary software; installing it means accepting the
[terms of service](https://zushapp.com/terms-of-service). The manifest in this repository is
published under the repository's [LICENSE](LICENSE); that license covers the packaging metadata
only, not the Zush application itself.
