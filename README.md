# linux-releases

Releases **natives** publiques (tar.gz / .deb) pour les apps Linux Mr-Aurevo-X.

**Pas de Flatpak ici.** Flatpak : https://github.com/Mr-Aurevo-X/linux-flatpak-releases

## Gest Linux Pro 1.4.0 (natif)

```bash
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/Gest_Linux_Pro-v1.4.0/Gest_Linux_Pro-1.4.0.tar.gz
tar -xzf Gest_Linux_Pro-1.4.0.tar.gz
cd Gest_Linux_Pro-1.4.0
bash install.sh
```

`install.sh` installe GTK4 / Libadwaita / Python depuis **vos** dépôts (apt/dnf/pacman/zypper/apk).  
Mise à jour auto au démarrage : télécharge le nouveau tarball et relance `install.sh --skip-deps` (terminal visible).

Si votre distro n’a pas GTK4 → utilisez le Flatpak.
