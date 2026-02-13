# 🔍 Schulweg-Detektive

Eine Web-App für Kinder, um Gefahrenstellen und sichere Orte auf ihrem Schulweg zu dokumentieren.

**Ein Gemeinschaftsprojekt von Jugendpflege der Gemeinde Kirkel und 2Rat Planungsbüro für Radverkehr**

---

## ℹ️ Über das Projekt

Dieses Projekt ist:
- ✅ **Kostenlos** – keine versteckten Kosten
- ✅ **Werbefrei** – keine Werbung, kein Tracking
- ✅ **Ohne Gewinnabsicht** – rein gemeinnützig

Die App entstand im Rahmen eines **Schülerpraktikums** bei der Jugendpflege Kirkel – komplett ohne Programmierkenntnisse, **ausschließlich mit Hilfe von KI**.

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
- 🗺️ **Live-Karte mit allen Meldungen** (direkt in der App)
- 📊 Statistik-Übersicht (inkl. Verkehrsmittel)
- 📥 Export als GeoJSON (für QGIS) oder CSV (für Excel)
- 🔐 Passwortgeschützter Bereich

---

## 🗺️ Ergebnisse sichtbar machen

Nach dem Projekttag können die Ergebnisse auf verschiedene Arten veröffentlicht werden:

### Option 1: Karte direkt in der App
Im Lehrer-Bereich werden alle Meldungen automatisch auf einer OpenStreetMap-Karte angezeigt:
- 🔴 Rot = Gefahrenstellen
- 🟢 Grün = Gute Stellen
- Klick auf Marker zeigt Details

### Option 2: Online-Karte mit uMap (kostenlos)
1. Im Lehrer-Bereich auf **"Alle Meldungen (GeoJSON)"** klicken
2. Auf [umap.openstreetmap.fr](https://umap.openstreetmap.fr/de/) gehen
3. **"Karte erstellen"** klicken
4. Rechts auf **"Daten importieren"** → GeoJSON-Datei hochladen
5. Karte speichern und **Link teilen**

→ Die Karte kann auf der Schulwebsite eingebettet oder per Link geteilt werden!

### Option 3: Google My Maps
1. GeoJSON exportieren
2. Auf [google.com/mymaps](https://www.google.com/mymaps) neue Karte erstellen
3. **"Importieren"** → GeoJSON hochladen
4. Karte freigeben

### Option 4: QGIS (für Profis)
1. GeoJSON exportieren
2. In QGIS als Layer laden
3. Stil anwenden (QML-Datei verfügbar)
4. Als PDF/Bild exportieren für Präsentationen

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
- **Entwickelt mit KI-Unterstützung**

---

## 👥 Projektbeteiligte

| Rolle | Person/Organisation |
|-------|---------------------|
| **Projektträger** | Jugendpflege der Gemeinde Kirkel |
| **Technische Umsetzung** | 2Rat Planungsbüro für Radverkehr |
| **Mitarbeit (Praktikum)** | Moritz Gessner |
| **Ansprechpartner** | Armin Jung |

### Kontakt
- 📞 06841-809860
- 📧 a.jung@kirkel.de
- 🌐 [2rat.org](https://2rat.org)

---

## 📄 Lizenz

Frei nutzbar für Bildungszwecke.

---

*Ein Gemeinschaftsprojekt von Jugendpflege der Gemeinde Kirkel & 2Rat Planungsbüro für Radverkehr, 2026*
