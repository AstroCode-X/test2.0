# 🌙 Dancing with SARS — Lunar SAR & CLPS Landing Control Dashboard

**NASA Space Apps Challenge 2026**  
**Team:** `00000000A_LAGRANGE_NEXUS`  

Dieses Repository enthält exakt die **6 essenziellen Projektdateien**, die du für den reibungslosen Betrieb und die Präsentation deines Lunar-Control-Center-Projekts benötigst.

---

## 📂 Die 6 notwendigen Projektdateien

1. **`index.html`** — Das interaktive Kontrollzentrum (Single-File Dashboard mit Leaflet-GIS, NASA LROC-Kacheln, Three.js 3D-Mond mit Echtzeit-Rotation, SAR-Radarebenen und Gemini AI Copilot).
2. **`generate_data.py`** — Die Python-Datenpipeline zur Berechnung von Kraterkoordinaten, PSR-Eisdepots und Gefahrenzonen.
3. **`data.json`** — Der strukturierte Datensatz im GeoJSON-Format.
4. **`worker.js`** — Das serverlose Edge-Skript für den sicheren Cloudflare Worker API-Proxy (`https://nexus.elias256.workers.dev/`).
5. **`worker_script_anleitung.md`** — Die Schritt-für-Schritt-Anleitung zur Einrichtung des Cloudflare Workers und des Secrets.
6. **`README.md`** — Diese vollständige Dokumentation inkl. wissenschaftlicher Formeln (CPR) und Installationsanleitung.

---

## 🚀 Installations- und Einrichtungsanleitung

### Schritt 1: Python-Datenpipeline ausführen
```bash
python3 generate_data.py
```
Dies generiert die kompakte `data.json` mit allen Landezielen.

### Schritt 2: Dashboard starten
Öffne die Datei `index.html` direkt in deinem Webbrowser oder starte sie über einen lokalen Server. Alle Radarebenen, Zielpunkte und der rotierende 3D-Mond sind voll einsatzbereit!