# 🚊 Intelligenter Routenvergleich mit Comfort Score

Eine innovative Web-App, die nicht nur die schnellste, sondern die **angenehmste Route** für Ihre Fahrten im öffentlichen Verkehr findet.

## ✨ Features

- **🎯 Comfort Score Bewertung** - Bewertet Routen nach Komfort statt nur nach Geschwindigkeit
- **🌦️ Wetter-Intelligenz** - Berücksichtigt Regen, Wind und Temperaturen bei der Bewertung
- **🔄 Umstiegs-Analyse** - Bevorzugt Direktverbindungen und optimale Umsteigezeiten
- **📱 Responsive Design** - Optimiert für Desktop und Mobile
- **⚡ Echtzeit-Daten** - Aktuelle Verbindungen und Wetterinformationen

## 🚀 Schnellstart

### Download & Direktstart

1. **Laden Sie die Datei herunter:**
   - Klicken Sie auf `Code` → `Download ZIP`
   - Entpacken Sie die ZIP-Datei
   - Öffnen Sie `index.html` direkt in Ihrem Browser

### 🎯 Sofort loslegen

1. **Öffnen Sie `index.html`** in Ihrem Webbrowser
2. **Geben Sie Start und Ziel ein** (z.B. "Zürich HB", "Zürich Oerlikon")
3. **Klicken Sie auf "Routen vergleichen"**
4. **Erhalten Sie die komfortabelste Route**

## 📊 Comfort Score System

Der Score (0-100 Punkte) bewertet Routen basierend auf:

| Faktor | Einfluss |
|--------|----------|
| 🔄 Umstiege | -8 Punkte pro Umstieg |
| 🌧️ Wetter | Bis zu -15 Punkte bei Regen |
| ⏱️ Reisedauer | -3 Punkte pro 10 Min. über 30 Min. |
| 👥 Stosszeiten | -10 Punkte bei hoher Auslastung |
| ⚠️ Knappe Umstiege | -12 Punkte bei <4 Min. |

**Bewertungsskala:**
- 🟢 **80-100** = Exzellent
- 🔵 **60-79** = Gut  
- 🟡 **40-59** = Akzeptabel
- 🔴 **0-39** = Schwierig

## 🛠️ Technologien

- **HTML5, CSS3, Vanilla JavaScript**
- **Transport.opendata.ch API** - ÖV-Verbindungen
- **Open-Meteo API** - Wetterdaten
- **CSS Grid & Flexbox** - Responsive Design

## 🌟 Beispiel-Stationen

- Zürich HB
- Zürich Oerlikon
- Zürich Stadelhofen  
- Zürich Altstetten
- Zürich Bellevue

## 📋 Systemvoraussetzungen

- **Moderner Webbrowser** (Chrome, Firefox, Safari, Edge)
- **Internetverbindung** (für API-Zugriff)
- **Keine zusätzliche Software** benötigt

## ❓ FAQ

**F: Funktioniert das offline?**  
A: Nein, Internetverbindung wird für Verbindungsdaten benötigt.

**F: Unterstützt es meine Stadt?**  
A: Derzeit fokussiert auf die Schweiz.

**F: Werden meine Daten gespeichert?**  
A: Nein, alle Berechnungen laufen lokal im Browser.

---

**💡 Einfach herunterladen, öffnen und loslegen!**

