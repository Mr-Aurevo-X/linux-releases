# linux-releases

Releases **natives** publiques pour **toutes** les apps Linux Mr-Aurevo-X (pas de sources).  
Apps actuelles : **Crypto Tracker** + **Gest Linux Pro** (ne pas retirer une app de ce README).

**Pas de Flatpak ici.** → https://github.com/Mr-Aurevo-X/linux-flatpak-releases

| App | Dernier tag | Fichiers |
| --- | --- | --- |
| **Crypto Tracker** | [`crypto-tracker-v1.1.8`](https://github.com/Mr-Aurevo-X/linux-releases/releases/tag/crypto-tracker-v1.1.8) | zips Mail / Binaire / Portable |
| **Gest Linux Pro** | [`Gest_Linux_Pro-v1.4.2`](https://github.com/Mr-Aurevo-X/linux-releases/releases/tag/Gest_Linux_Pro-v1.4.2) | `tar.gz` + `install.sh` (`.deb` optionnel) |

## Crypto Tracker 1.1.8

```bash
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.1.8/CryptoTracker-Linux-Mail-*.zip
unzip CryptoTracker-Linux-Mail-*.zip
./CryptoTracker-Linux-Mail/CryptoTracker
```

- `CryptoTracker-Linux-Mail-*.zip` — léger (glibc Ubuntu 22.04+)
- `CryptoTracker-Linux-Binaire-*.zip` — graphiques inclus
- `CryptoTracker-Portable-Linux-*.zip` — `bash LANCER.sh` si crash GLIBC

Mise à jour : auto au démarrage, ou Paramètres → Vérifier les mises à jour.  
Données : `~/.local/share/crypto-tracker/`

## Gest Linux Pro 1.4.2

```bash
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/Gest_Linux_Pro-v1.4.2/Gest_Linux_Pro-1.4.2.tar.gz
tar -xzf Gest_Linux_Pro-1.4.2.tar.gz
cd Gest_Linux_Pro-1.4.2
bash install.sh
```

`install.sh` installe GTK4 / Libadwaita / Python depuis **vos** dépôts (apt/dnf/pacman/zypper/apk).  
Mise à jour auto au démarrage : nouveau tarball + `install.sh --skip-deps`.

Si votre distro n’a pas GTK4 → utilisez le Flatpak.
