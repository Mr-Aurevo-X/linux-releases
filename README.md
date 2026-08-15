# linux-releases

Releases **natives** publiques pour **toutes** les apps Linux Mr-Aurevo-X (pas de sources).  
Apps actuelles : **Crypto Tracker** + **Gest Linux Pro** + **MrAurevoX Kit** (ne pas retirer une app de ce README).

**Pas de Flatpak ici.** → https://github.com/Mr-Aurevo-X/linux-flatpak-releases

| App | Dernier tag | Fichiers |
| --- | --- | --- |
| **Crypto Tracker** | [`crypto-tracker-v1.2.9`](https://github.com/Mr-Aurevo-X/linux-releases/releases/tag/crypto-tracker-v1.2.9) | zips Mail / Binaire / Portable |
| **Gest Linux Pro** | [`Gest_Linux_Pro-v1.4.10`](https://github.com/Mr-Aurevo-X/linux-releases/releases/tag/Gest_Linux_Pro-v1.4.10) | `tar.gz` + `install.sh` (`.deb` optionnel) |
| **MrAurevoX Kit** | [`MrAurevoX-Kit-v0.2.6`](https://github.com/Mr-Aurevo-X/linux-releases/releases/tag/MrAurevoX-Kit-v0.2.6) | `tar.gz` + `install.sh` |

## Crypto Tracker 1.2.9

**Mail** — léger, pas de graphes :

```bash
unset SSL_CERT_FILE SSL_CERT_DIR REQUESTS_CA_BUNDLE CURL_CA_BUNDLE
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.2.9/CryptoTracker-Linux-Mail-20260815.zip
unzip -o CryptoTracker-Linux-Mail-20260815.zip
cd CryptoTracker-Linux-Mail
chmod +x CryptoTracker
./CryptoTracker
```

**Binaire** — graphes inclus (matplotlib) :

```bash
unset SSL_CERT_FILE SSL_CERT_DIR REQUESTS_CA_BUNDLE CURL_CA_BUNDLE
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.2.9/CryptoTracker-Linux-Binaire-20260815.zip
unzip -o CryptoTracker-Linux-Binaire-20260815.zip
cd CryptoTracker-Linux-Binaire
chmod +x CryptoTracker
./CryptoTracker
```

- `CryptoTracker-Linux-Mail-20260815.zip` — léger, pas de graphes (glibc Ubuntu 22.04+)
- `CryptoTracker-Linux-Binaire-20260815.zip` — graphes inclus (matplotlib)
- `CryptoTracker-Portable-Linux-20260815.zip` — `bash LANCER.sh` si crash GLIBC

Mise à jour : auto au démarrage, ou Paramètres → Vérifier les mises à jour.  
Données : `~/.local/share/crypto-tracker/`

### Mentions légales Crypto Tracker (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Logiciel propriétaire.
- **CGU :** fourni « en l’état » ; pas un conseil en investissement ; pas de copie / redistribution sans autorisation.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Fichiers locaux `~/.local/share/crypto-tracker/`. Prix : CoinGecko / Binance. MAJ GitHub (désactivable).
- Texte complet : [`LEGAL-Crypto-Tracker.md`](https://github.com/Mr-Aurevo-X/linux-releases/blob/main/LEGAL-Crypto-Tracker.md) et [`LEGAL.md`](https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.2.9/LEGAL.md) (joint à la release). App : Paramètres → CGU / RGPD.

## Gest Linux Pro 1.4.10

**© 2026 Mr-Aurevo-X** · GPL-3.0-or-later · 100 % local (sauf vérif MAJ GitHub, désactivable)

```bash
cd ~
wget -O Gest_Linux_Pro-1.4.10.tar.gz \
  https://github.com/Mr-Aurevo-X/linux-releases/releases/download/Gest_Linux_Pro-v1.4.10/Gest_Linux_Pro-1.4.10.tar.gz
tar -xzf Gest_Linux_Pro-1.4.10.tar.gz
cd Gest_Linux_Pro-1.4.10
bash install.sh
```

Cible native promise : **CachyOS uniquement** (`pacman` / `bash install.sh`).  
**Linux Mint / Ubuntu 22.04 native : non supporté pour le moment** — utilisez le [Flatpak](https://github.com/Mr-Aurevo-X/linux-flatpak-releases).

Lancer `tar` depuis `~`, pas depuis un dossier déjà extrait. `wget` suffit (pas besoin de `curl`).

Sur CachyOS, `install.sh` installe GTK4 / Libadwaita / Python via **pacman**.  
Mise à jour auto au démarrage : nouveau tarball + `install.sh --skip-deps`.

Autres distros → Flatpak.

### Mentions légales Gest Linux Pro (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Code sous GPL-3.0-or-later.
- **CGU :** logiciel « en l’état » ; vous êtes responsable des actions système (pkexec, services, pare-feu, clichés, paquets). Redistribution sous GPL.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Fichiers locaux `~/.config/gest-linux-pro/`, `~/.local/share/gest-linux-pro/`. MAJ GitHub désactivable.
- Texte complet : [`LEGAL-Gest-Linux-Pro.md`](https://github.com/Mr-Aurevo-X/linux-releases/blob/main/LEGAL-Gest-Linux-Pro.md).

## MrAurevoX Kit 0.2.6

**© 2026 Mr-Aurevo-X** · GPL-3.0-or-later · 100 % local (sauf vérif MAJ GitHub, désactivable)

```bash
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/MrAurevoX-Kit-v0.2.6/MrAurevoX_Kit-0.2.6.tar.gz
tar -xzf MrAurevoX_Kit-0.2.6.tar.gz
cd MrAurevoX_Kit-0.2.6
bash install.sh
```

Recherche, pipette, rename, hash (SHA-256/512/BLAKE2), images/EXIF, PDF, atelier (texte / encode / QR). Launcher : `mraurevox-kit`.  
Données : `~/.config/mraurevox-kit/`, `~/.local/share/mraurevox-kit/`.

### Mentions légales MrAurevoX Kit (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Code sous GPL-3.0-or-later.
- **CGU :** logiciel « en l’état » ; vous êtes responsable des fichiers que vous renommez, redimensionnez ou ouvrez. Redistribution sous GPL.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Pas de télémétrie. MAJ GitHub désactivable.
- Texte complet : [`LEGAL-MrAurevoX-Kit.md`](https://github.com/Mr-Aurevo-X/linux-releases/blob/main/LEGAL-MrAurevoX-Kit.md).

© 2026 Mr-Aurevo-X. Crypto Tracker : propriétaire. Gest Linux Pro et MrAurevoX Kit : GPL-3.0-or-later.
