# Limbo – Downloads

Fertige Pakete von **Limbo**, der Erweiterung für Pterodactyl, die ungenutzte Server in
externen Speicher auslagert und beim Aufwecken vollständig wiederherstellt.

Dieses Repository enthält nur die Release-Dateien. Für den Betrieb ist eine Lizenz nötig.

## Installation (Panels ohne Blueprint, z. B. mit Arix)

```bash
curl -fsSLO https://github.com/theredstonee/limbo-releases/releases/latest/download/limbo-install.sh
sudo bash limbo-install.sh
```

Das Skript fragt nach dem Lizenzschlüssel, prüft ihn, lädt erst dann das aktuelle Paket,
kontrolliert dessen Prüfsumme und installiert es. Über dasselbe Skript lässt sich Limbo
aktualisieren und deinstallieren.

Ohne Rückfragen:

```bash
sudo bash limbo-install.sh install /var/www/pterodactyl --key=TRS-XXXX-XXXX-XXXX
sudo bash limbo-install.sh uninstall /var/www/pterodactyl
```

Nach einem Update des Panels oder des Themes das Skript erneut ausführen.
