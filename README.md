# scoop-bucket

[![Tests](https://github.com/Zyrecx/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Zyrecx/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Zyrecx/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Zyrecx/scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for [Ombra](https://github.com/Zyrecx/ombra), lightweight instant
replay for Windows.

```pwsh
scoop bucket add zyrecx https://github.com/Zyrecx/scoop-bucket
scoop install zyrecx/ombra
```

Quit Ombra from its tray icon before `scoop update ombra` or `scoop uninstall ombra`. New releases
reach the bucket automatically within a few hours.
