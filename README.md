# TacticalFlatpak


```bash
flatpak-builder --repo=repo --force-clean build-dir com.DaRealRoyal.TacticalMathReturns.yml --gpg-sign=7E56B236E04AD5F0
```


```bash
rclone sync ~/Documents/Flatpak/TMR/com.DaRealRoyal.TacticalMathReturns/repo NilsVPS:/var/www/flatpak.nils.moe/repo --progress
```