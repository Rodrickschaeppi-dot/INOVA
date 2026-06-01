# Invora – Online-Shop

Statische Single-Page-Website (Damenmode & Accessoires), bereit für Vercel.

## Inhalt
- `index.html` – komplette Website (HTML/CSS/JS in einer Datei)
- `vercel.json` – Vercel-Konfiguration

## Deployment auf Vercel

### Variante A – ohne Installation (Drag & Drop)
1. Auf https://vercel.com einloggen
2. Diesen Ordner (entpackt) per Drag & Drop ins Dashboard ziehen
3. Vercel erkennt das statische Projekt automatisch → "Deploy"

### Variante B – Vercel CLI
```bash
npm i -g vercel
cd invora-vercel
vercel          # Vorschau-Deployment
vercel --prod   # Live-Deployment
```

### Variante C – via GitHub
1. Ordnerinhalt in ein GitHub-Repo pushen
2. Auf Vercel "New Project" → Repo importieren → Deploy

## Hinweise
- Keine Build-Schritte nötig (reines statisches HTML).
- Die Produktbilder werden von Unsplash geladen → Internetverbindung erforderlich.
- Rechtstexte (AGB, Impressum etc.) sind Mustervorlagen und vor dem Live-Gang mit echten Firmendaten zu ersetzen.

Gruppe: Rodrick Schäppi · Marina Gnehm
