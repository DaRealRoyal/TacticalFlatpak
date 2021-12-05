# TacticalFlatpak

📦 Flatpak Package of Tactical Math Returns for Linux

## Installing

I'm hosting this Tactical Math Returns Flatpak on my own Flatpak Repo. You can install it from there like this:

```bash
flatpak install https://flatpak.nils.moe/com.DaRealRoyal.TacticalMathReturns.flatpakref
```

## Building

### Install SDK and Platform

```bash
flatpak install flathub org.freedesktop.Sdk//21.08
flatpak install flathub org.freedesktop.Platform//21.08
```

### Build

```bash
flatpak-builder --force-clean build-dir com.DaRealRoyal.TacticalMathReturns.yml
```

