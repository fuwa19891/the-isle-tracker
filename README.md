# The Isle - Apex Kill Counter

[Deutsch](#deutsch) | [English](#english)

---

## Deutsch

Ein interaktiver Kill-Tracker im Fossil- und Bernstein-Design für **The Isle**, optimiert für den Einsatz als eigenständiges App-Fenster (PWA) auf dem Desktop oder direkt im Browser.

### Features

- **Startmenü & Dino-Auswahl:** Wähle vor oder während der Jagd deinen gespielten Dino (**T-Rex**, **Deino**, **Trike** oder **Stego**) inklusive passendem Hintergrundfossil und Rahmenmuster.
- **Spielmodi:** Unterstützt **Solo**, **Duo** und **Trio** mit anpassbarem Team-/Spielernamen direkt im Score-Header.
- **Zweisprachig (DE / EN):** Nahtloser Wechsel zwischen Deutsch und Englisch im Startmenü sowie im aktiven Tracker.
- **Beute-Tracking nach Kategorie:** Schnelles Zählen von **Carnivore**, **Herbivore** und **Snack** über Bernstein-Buttons:
  - **Linksklick:** `+1` Kill
  - **Rechtsklick:** `-1` Kill (Korrektur)
  - **`Z`-Taste oder Undo-Button:** Letzte Aktion rückgängig machen
- **Effekte & Killfeed:** Visuelle Schlitzer-Effekte bei Kills, epischer Meilenstein-Effekt bei jedem 5. Kill eines Ziels sowie ein Live-Killfeed (die letzten 4 Einträge).
- **Discord-Export:** Kopiert eine formatierte Kill-Übersicht inklusive Modus, Namen, gespieltem Dino und Gesamtzahlen direkt in die Zwischenablage.
- **Sound & Reset:** Audio-Feedback umschaltbar und vollständiges Zurücksetzen aller Kills per Reset-Button.
- **App-Installation (PWA):** Kann über Chrome/Edge als eigene App (Standalone-Fenster im Format `605px x 998px`) installiert werden.

### Nutzung & App-Installation

1. Öffne die HTML-Anwendung über einen lokalen Server oder gehostet (z. B. über GitHub Pages).
2. Wähle im Startmenü deinen Dino, den Modus (**Solo**, **Duo**, **Trio**) und die Sprache (**DE** / **EN**) und klicke auf **JAGD STARTEN**.
3. **Als App installieren:** Klicke in Chrome oder Edge in der Adressleiste auf das **Installieren-Symbol** bzw. über das Browser-Menü auf **Diese Seite als App installieren**.

### Benötigte Dateien im Projektordner

Damit alle Grafiken und App-Icons sauber laden, sollten folgende Dateien im selben Verzeichnis liegen:

- `index.html` (bzw. deine HTML-Datei)
- `icon.png`
- `amber-stone.png`
- `evolution.png`
- `t-rex_background.png`, `deino_background.png`, `trike_background.png`, `stego_background.png`
- Schädel- und Snack-Grafiken (`t-rex_skull.png`, `deino_skull.png`, `Allo_skull.png`, `cera_skull.png`, `dilo_skull.png`, `carno_skull.png`, `omni_skull.png`, `trike_skull.png`, `stego_skull.png`, `kentro_skull.png`, `maia_skull.png`, `teno_skull.png`, `pachy_skull.png`, `snack.png`)

---

## English

An interactive kill tracker styled with fossil and amber aesthetics for **The Isle**, built to run smoothly in the browser or as an installable standalone app window (PWA).

### Features

- **Start Menu & Dino Selection:** Choose your played dinosaur (**T-Rex**, **Deino**, **Trike**, or **Stego**) before or during a hunt, complete with matching background fossils and frame motifs.
- **Game Modes:** Supports **Solo**, **Duo**, and **Trio** with an editable player/team name right in the score header.
- **Bilingual (DE / EN):** Switch effortlessly between German and English from both the start menu and the tracker view.
- **Prey Tracking by Tier:** Track **Carnivore**, **Herbivore**, and **Snack** targets using amber buttons:
  - **Left-click:** `+1` kill
  - **Right-click:** `-1` kill (correction)
  - **`Z` key or Undo button:** Revert the last action
- **Effects & Killfeed:** Claw slash animations on kills, an epic milestone effect on every 5th kill of a target, and a live killfeed showing the latest 4 events.
- **Discord Export:** Copies a formatted kill summary—including mode, name, played dinosaur, and totals—to your clipboard.
- **Sound & Reset:** Toggle sound effects on/off and reset all tracked kills with a single click.
- **Installable App (PWA):** Can be installed in Chrome or Edge as a standalone app window (`605px x 998px`).

### Usage & App Installation

1. Open the HTML file via a local web server or hosted page (such as GitHub Pages).
2. Pick your dinosaur, mode (**Solo**, **Duo**, **Trio**), and language (**DE** / **EN**) on the start screen, then click **START HUNT**.
3. **Install as App:** Click the **Install** icon in the Chrome/Edge address bar or choose **Install page as app** from the browser menu.

### Project Assets

Make sure the following asset files are placed alongside your HTML file:

- `index.html` (or your main HTML file)
- `icon.png`
- `amber-stone.png`
- `evolution.png`
- `t-rex_background.png`, `deino_background.png`, `trike_background.png`, `stego_background.png`
- Skull & snack images (`t-rex_skull.png`, `deino_skull.png`, `Allo_skull.png`, `cera_skull.png`, `dilo_skull.png`, `carno_skull.png`, `omni_skull.png`, `trike_skull.png`, `stego_skull.png`, `kentro_skull.png`, `maia_skull.png`, `teno_skull.png`, `pachy_skull.png`, `snack.png`)
