# TacticalFlatpak

📦 Flatpak Package of Tactical Math Returns for Linux

## Installing

I'm hosting this Flatpak on my own Flatpak Repo. You can install it from there like this:

```bash
flatpak install https://flatpak.nils.moe/repo/appstream/com.DaRealRoyal.TacticalMathReturns.flatpakref
```

## Building

```bash
flatpak-builder --install-deps-from=flathub --force-clean build-dir com.DaRealRoyal.TacticalMathReturns.yml
```
