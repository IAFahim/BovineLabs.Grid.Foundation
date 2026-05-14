# Grid Foundation

[![CI](https://github.com/IAFahim/com.bovinelabs.grid.foundation/actions/workflows/ci.yml/badge.svg)](https://github.com/IAFahim/com.bovinelabs.grid.foundation/actions)

> Grid Foundation

**Build outside Unity. Ship as Unity package.**

```bash
dotnet test -c Release
git push
```

## Install

Add to `Packages/manifest.json`:

```json
"com.bovinelabs.grid.foundation": "https://github.com/IAFahim/com.bovinelabs.grid.foundation.git"
```

Or Unity → Package Manager → Add from git URL.

## Dev

```bash
dotnet restore
dotnet test -c Release
```

Source: `com.bovinelabs.grid.foundation.Runtime/`  Tests: `com.bovinelabs.grid.foundation.Tests/`

MIT © 2026 Vex Interactive
