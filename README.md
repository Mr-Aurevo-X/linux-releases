# linux-releases

Releases **natives** publiques pour **toutes** les apps Linux Mr-Aurevo-X (pas de sources).  
Apps actuelles : **Crypto Tracker** + **Gest Linux Pro** (ne pas retirer une app de ce README).

**Pas de Flatpak ici.** → https://github.com/Mr-Aurevo-X/linux-flatpak-releases

| App | Dernier tag | Fichiers |
| --- | --- | --- |
| **Crypto Tracker** | [`crypto-tracker-v1.2.6`](https://github.com/Mr-Aurevo-X/linux-releases/releases/tag/crypto-tracker-v1.2.6) | zips Mail / Binaire / Portable |
| **Gest Linux Pro** | [`Gest_Linux_Pro-v1.4.5`](https://github.com/Mr-Aurevo-X/linux-releases/releases/tag/Gest_Linux_Pro-v1.4.5) | `tar.gz` + `install.sh` (`.deb` optionnel) |

## Crypto Tracker 1.2.6

```bash
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.2.6/CryptoTracker-Linux-Mail-20260815.zip
unzip CryptoTracker-Linux-Mail-20260815.zip
./CryptoTracker-Linux-Mail/CryptoTracker
```

- `CryptoTracker-Linux-Mail-*.zip` — léger (glibc Ubuntu 22.04+)
- `CryptoTracker-Linux-Binaire-*.zip` — graphiques inclus
- `CryptoTracker-Portable-Linux-*.zip` — `bash LANCER.sh` si crash GLIBC

Mise à jour : auto au démarrage, ou Paramètres → Vérifier les mises à jour.  
Données : `~/.local/share/crypto-tracker/`

### Mentions légales Crypto Tracker (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Logiciel propriétaire.
- **CGU :** fourni « en l’état » ; pas un conseil en investissement ; pas de copie / redistribution sans autorisation.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Fichiers locaux `~/.local/share/crypto-tracker/`. Prix : CoinGecko / Binance. MAJ GitHub (désactivable).
- Texte complet : [`LEGAL-Crypto-Tracker.md`](https://github.com/Mr-Aurevo-X/linux-releases/blob/main/LEGAL-Crypto-Tracker.md) et [`LEGAL.md`](https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.2.6/LEGAL.md) (joint à la release). App : Paramètres → CGU / RGPD.

## Gest Linux Pro 1.4.5

**© 2026 Mr-Aurevo-X** · GPL-3.0-or-later · 100 % local (sauf vérif MAJ GitHub, désactivable)

```bash
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/Gest_Linux_Pro-v1.4.5/Gest_Linux_Pro-1.4.5.tar.gz
tar -xzf Gest_Linux_Pro-1.4.5.tar.gz
cd Gest_Linux_Pro-1.4.5
bash install.sh
```

`install.sh` installe GTK4 / Libadwaita / Python depuis **vos** dépôts (apt/dnf/pacman/zypper/apk).  
Mise à jour auto au démarrage : nouveau tarball + `install.sh --skip-deps`.

Si votre distro n’a pas GTK4 → utilisez le Flatpak.

### Mentions légales Gest Linux Pro (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Code sous GPL-3.0-or-later.
- **CGU :** logiciel « en l’état » ; vous êtes responsable des actions système (pkexec, services, pare-feu, clichés, paquets). Redistribution sous GPL.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Fichiers locaux `~/.config/gest-linux-pro/`, `~/.local/share/gest-linux-pro/`. MAJ GitHub désactivable.
- Texte complet : [`LEGAL-Gest-Linux-Pro.md`](https://github.com/Mr-Aurevo-X/linux-releases/blob/main/LEGAL-Gest-Linux-Pro.md).

© 2026 Mr-Aurevo-X. Crypto Tracker : propriétaire. Gest Linux Pro : GPL-3.0-or-later.
