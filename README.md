# 🔍 Schulweg-Detektive

Eine Web-App für Kinder, um Gefahrenstellen und sichere Orte auf ihrem Schulweg zu dokumentieren.

**Ein Projekt der Jugendpflege Kirkel**

---

## 🎯 Was ist das?

Kinder werden zu "Schulweg-Detektiven" und melden per Smartphone:
- ⚠️ **Gefährliche Stellen** (z.B. schnelle Autos, Autos im Weg, fehlende Überwege)
- 👍 **Gute Stellen** (z.B. Zebrastreifen, Ampeln, Schülerlotsen)

Die App speichert automatisch den GPS-Standort. Am Ende zeigen die Kinder einen QR-Code, der vom Lehrer gescannt wird. Die Ergebnisse können direkt auf einer Karte betrachtet oder als GeoJSON/CSV exportiert werden.

---

## 📱 App öffnen

**👉 [https://009aj.github.io/schulweg-check/](https://009aj.github.io/schulweg-check/)**

### Als App installieren (offline nutzbar)
| Gerät | Anleitung |
|-------|-----------|
| **Android** | Menü (⋮) → "Zum Startbildschirm hinzufügen" |
| **iPhone** | Teilen-Button → "Zum Home-Bildschirm" |

---

## 🚀 Funktionen

### Für Kinder
- ✅ Einfache Bedienung: **2 Klicks zum Melden**
- ✅ GPS-Standort wird automatisch gespeichert
- ✅ Angabe von Verkehrsmittel und Schulweg-Richtung
- ✅ QR-Code zum Teilen mit dem Lehrer

### Für Lehrer
- 📷 QR-Code-Scanner zum Sammeln aller Meldungen
- 🗺️ **Karte mit allen Meldungen** (OpenStreetMap)
- 📊 Statistik-Übersicht (inkl. Verkehrsmittel)
- 📥 Export als GeoJSON (für QGIS) oder CSV (für Excel)
- 🔐 Passwortgeschützter Bereich

---

## 📋 Kategorien

### ⚠️ Gefahrenstellen
| Emoji | Kategorie |
|-------|-----------|
| 🚗 | Zu schnelle Autos |
| 🚙 | Auto im Weg |
| 🚶 | Kein Gehweg |
| 🚦 | Schwer zu überqueren |
| 👀 | Schlecht zu sehen |
| 🌙 | Zu dunkel |
| 🚧 | Baustelle |
| ❓ | Etwas anderes |

### 👍 Gute Stellen
| Emoji | Kategorie |
|-------|-----------|
| 🚦 | Gute Ampel |
| 🦓 | Zebrastreifen |
| 🧑‍🦺 | Schülerlotse |
| 🛣️ | Breiter Gehweg |
| 🐌 | Tempo 30 |
| ⭐ | Etwas anderes |

---

## 🔒 Datenschutz

- ✅ Alle Daten bleiben **lokal auf dem Gerät**
- ✅ **Keine Server-Übertragung** – Daten werden nur per QR-Code geteilt
- ✅ Keine Registrierung oder E-Mail nötig
- ✅ Keine Wohnadressen oder Bewegungsprofile
- ✅ Daten können jederzeit gelöscht werden

---

## 🛠️ Technologie

- Progressive Web App (PWA)
- Vanilla HTML/CSS/JavaScript
- Leaflet.js für Kartenanzeige
- Offline-fähig nach erstem Laden
- Keine externen Abhängigkeiten für Kernfunktionen

---

## 📄 Lizenz

Frei nutzbar für Bildungszwecke.

---

*Entwickelt von der Jugendpflege Kirkel & 2Rat – Büro für Radverkehrsplanung, 2026*


