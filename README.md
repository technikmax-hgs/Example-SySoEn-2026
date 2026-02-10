# Website Ordnerstruktur

## 📁 Verzeichnisübersicht

```
website/
│
├── index.html          # Haupt-HTML-Datei
│
├── css/                # CSS Stylesheets
│   ├── reset.css       # Browser Reset Styles
│   ├── style.css       # Hauptstyles
│   └── responsive.css  # Mobile/Responsive Styles
│
├── js/                 # JavaScript Dateien
│   └── main.js         # Haupt-JavaScript
│
├── images/             # Bilder und Grafiken
│   ├── logo/           # Logo-Dateien
│   ├── hero/           # Hero-Section Bilder
│   ├── services/       # Service-Bilder
│   └── icons/          # Icons und kleine Grafiken
│
└── fonts/              # Webfonts (optional)
```

## 🎨 CSS Dateien

- **reset.css**: Setzt Browser-Standardstyles zurück
- **style.css**: Alle Hauptstyles für die Website
- **responsive.css**: Media Queries für mobile Geräte

## 📸 Images Ordner

Empfohlene Unterordner für bessere Organisation:
- `logo/` - Dein Logo in verschiedenen Größen
- `hero/` - Große Hintergrundbilder für Hero-Section
- `services/` - Bilder für Service-Cards
- `icons/` - Kleine Icons und Grafiken

## 💡 Verwendung

1. Bilder in den entsprechenden Ordner legen
2. In HTML referenzieren: `<img src="images/logo/logo.png" alt="Logo">`
3. CSS anpassen nach Bedarf
4. JavaScript in `js/main.js` erweitern

## 🚀 Erweiterungen

Weitere Ordner können hinzugefügt werden:
- `videos/` - Für Videodateien
- `documents/` - Für PDFs und Downloads
- `assets/` - Für sonstige Medien
