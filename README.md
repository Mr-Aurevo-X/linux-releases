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
