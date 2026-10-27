# Scoop bucket

[![Tests](https://github.com/LaurinSorgend/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/LaurinSorgend/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/LaurinSorgend/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/LaurinSorgend/scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) manifests for my apps.

| App | Description |
|---|---|
| `abs-desktop` | [ABS Desktop](https://github.com/LaurinSorgend/ABSDesktopApp), a desktop client for Audiobookshelf |

```pwsh
scoop bucket add laurin https://github.com/LaurinSorgend/scoop-bucket
scoop install laurin/abs-desktop
```

The Excavator workflow checks for new releases every four hours and updates the manifests.
