# linux-releases

Releases **natives** publiques pour **Crypto Tracker** (pas de sources).

**Pas de Flatpak ici.** → https://github.com/Mr-Aurevo-X/linux-flatpak-releases

**UtilKit** et **Gest Linux Pro** : Flatpak sur [UtilKit](https://github.com/Mr-Aurevo-X/UtilKit) et [Gest_Linux_Pro](https://github.com/Mr-Aurevo-X/Gest_Linux_Pro).

| App | Dernier tag | Fichiers |
| --- | --- | --- |
| **Crypto Tracker** | [`crypto-tracker-v1.2.17`](https://github.com/Mr-Aurevo-X/linux-releases/releases/tag/crypto-tracker-v1.2.17) | zips Binaire / Portable |

## Crypto Tracker 1.2.17

**Binaire** — graphes inclus (matplotlib) :

```bash
unset SSL_CERT_FILE SSL_CERT_DIR REQUESTS_CA_BUNDLE CURL_CA_BUNDLE
curl -fL -O https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.2.17/CryptoTracker-Linux-Binaire-20260818.zip
unzip -o CryptoTracker-Linux-Binaire-20260818.zip
cd CryptoTracker-Linux-Binaire
chmod +x CryptoTracker
./CryptoTracker
```

- `CryptoTracker-Linux-Binaire-20260818.zip` — graphes inclus (matplotlib)
- `CryptoTracker-Portable-Linux-20260818.zip` — `bash LANCER.sh` si crash GLIBC

Si tu avais le zip Mail, installe Binaire par-dessus (même dossier ou nouveau) ; le portefeuille n’est pas dans le zip, il reste dans `~/.local/share/crypto-tracker/`.

Mise à jour : notification au démarrage (commandes copiables), ou Paramètres → Vérifier les mises à jour.  
Données : `~/.local/share/crypto-tracker/`

### Mentions légales Crypto Tracker (CGU / RGPD)

- **Copyright © 2026 Mr-Aurevo-X.** Logiciel propriétaire.
- **CGU :** fourni « en l’état » ; pas un conseil en investissement ; pas de copie / redistribution sans autorisation.
- **RGPD :** aucune collecte par Mr-Aurevo-X. Fichiers locaux `~/.local/share/crypto-tracker/`. Prix : CoinGecko / Binance. MAJ GitHub (désactivable).
- Texte complet : [`LEGAL-Crypto-Tracker.md`](https://github.com/Mr-Aurevo-X/linux-releases/blob/main/LEGAL-Crypto-Tracker.md) et [`LEGAL.md`](https://github.com/Mr-Aurevo-X/linux-releases/releases/download/crypto-tracker-v1.2.17/LEGAL.md) (joint à la release). App : Paramètres → CGU / RGPD.

© 2026 Mr-Aurevo-X. Crypto Tracker : propriétaire.
