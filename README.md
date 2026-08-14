# linux-releases

Releases **natives** publiques (tar.gz / .deb) pour les apps Linux Mr-Aurevo-X.

**Pas de Flatpak ici.** Flatpak : https://github.com/Mr-Aurevo-X/linux-flatpak-releases

## Gest Linux Pro (natif)

```bash
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/Gest_Linux_Pro-v1.3.4/Gest_Linux_Pro-1.3.4.tar.gz
tar -xzf Gest_Linux_Pro-1.3.4.tar.gz
cd Gest_Linux_Pro-1.3.4
bash install.sh
```

`install.sh` installe GTK4 / Libadwaita / Python depuis **vos** dépôts (apt/dnf/pacman/zypper/apk).  
Si votre distro n’a pas GTK4 → utilisez le Flatpak.

## Crypto Tracker (natif)

Zips validés Mint (glibc Ubuntu 22.04) : tag `crypto-tracker-v1.0.2` — **pas** 1.1.x.

```bash
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.0.2/CryptoTracker-Linux-Mail-20260810.zip
```

- `CryptoTracker-Linux-Mail-20260810.zip` — binaire léger (réf. Mint)
- `CryptoTracker-Linux-Binaire-20260810.zip` — graphiques inclus
- `CryptoTracker-Portable-Linux-20260810.zip` — `bash LANCER.sh` si crash GLIBC

Flatpak : https://github.com/Mr-Aurevo-X/linux-flatpak-releases/releases/tag/crypto-tracker-v1.1.0
