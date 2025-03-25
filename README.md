# netwatch
Netzwerküberwachung für macOS: erkennt VPNs, IP-Wechsel, WLAN-Signal, Bandbreite. Push via Pushover, Logging in Text und JSON. Läuft automatisch per LaunchAgent.
# 🛰️ netwatch

Kompaktes Netzwerküberwachungs-Tool für macOS.  
Erkennt Interface-Wechsel, IP-Änderungen, VPN-Verbindungen, WLAN-Signalstärke und schätzt die aktuelle Bandbreite. Optional werden Push-Benachrichtigungen über Pushover verschickt.

---

## Funktionen

- Anzeige aktiver Netzwerkverbindung (Interface, IP-Adresse)
- Erkennung von VPN-Tunneln (utunX)
- WLAN-SSID und Signalstärke (dBm und Prozent)
- Leichter Bandbreitentest (Upload/Download in KB/s)
- Push-Benachrichtigungen via Pushover
- Logging im Text- und JSON-Format
- Automatischer Hintergrundbetrieb über LaunchAgent
- Ressourcenfreundlich und lokal ausführbar

---

## Installation

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/DEINUSERNAME/netwatch/main/netwatch-install.sh)
