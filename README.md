# NWP Notfallkarte – Page

Öffentliche Download-Seite der **Notfallkarte Zweifel Chips & Snacks AG** für Apple Wallet und Google Wallet.

**Adresse (Ziel des QR-Codes):** https://zcsch.github.io/NWP_Notfallkarte_Page/

| Datei | Zweck |
|---|---|
| `index.html` | Weiche: iPhone → Apple-Karte, Android → Google-Karte, Computer → QR-Code |
| `Notfallkarte.pkpass` | Signierte Apple-Wallet-Karte |
| `qr.png` | QR-Code auf diese Seite |
| `robots.txt` | Seite nicht in Suchmaschinen aufnehmen |

## Karte ändern

Die Karte wird **nicht hier** bearbeitet. Quelle und Build-Skripte liegen im privaten Repository `ZCSCH/NWP_Notfallkarte`. Schlüssel und Zertifikate liegen auf keinem GitHub-Repository.
Nach einer Änderung die neu gebaute `Notfallkarte.pkpass` hier ersetzen und pushen. Adresse und QR-Code bleiben gleich.

## Wichtig

- **Nie** Schlüssel, Zertifikate (`*.pem`, `*.p12`, `*.cer`) oder Google-Dienstkonto-Dateien in dieses Repository legen. Es ist öffentlich.
- Apple-Pass-Zertifikat gültig bis **03.12.2027**, vorher erneuern.
