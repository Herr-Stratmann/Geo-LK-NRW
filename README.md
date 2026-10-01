# Geographie LK – Modelle & Begriffe

Interaktive Lernplattform für den Geographie-Leistungskurs der Qualifikationsphase (NRW).
Die Startseite (`index.html`) gliedert die Inhalte in sechs Themenfelder und führt zu den Modellseiten. Ein Register erklärt die Fachbegriffe.

| Themenfeld | Modellseiten |
|---|---|
| 1 Globale Disparitäten und Lösungsansätze | `strategien.html` Entwicklungsstrategien im Wandel · `oben-unten.html` Entwicklung von oben und unten · `fragmentierung.html` Fragmentierende Entwicklung |
| 2 Tourismus | – |
| 3 Bevölkerungsentwicklung und Migration | – |
| 4 Stadtgeographie | – |
| 5 Wirtschaftsgeographie | – |
| 6 Landwirtschaft | – |

## Veröffentlichen mit GitHub Pages

1. Neues Repository anlegen (z. B. `geo-lk`) und die sechs Dateien hochladen.
2. Im Repository: **Settings → Pages → Build and deployment → Source: „Deploy from a branch“**, Branch `main`, Ordner `/ (root)`, speichern.
3. Nach ein bis zwei Minuten ist die Seite erreichbar unter `https://<benutzername>.github.io/geo-lk/`.

Für GitHub Pages muss das Repository öffentlich sein (außer bei kostenpflichtigen Konten).

## Direktlinks

Bereiche einer Modellseite lassen sich direkt verlinken, z. B.:

- `oben-unten.html#simulation`, `#modelle`, `#vergleich`, `#ueben`
- `fragmentierung.html#global`, `#lokal`, `#dynamik`, `#ueben`
- `index.html#register` (Begriffsregister), `index.html#disparitaeten` (Themenfeld vorauswählen)

## Datenschutz

- Die Seiten laden keine externen Skripte, Schriften oder Tracker. Die Schriften stecken in `schriften.css` (SIL Open Font License).
- Es werden keine Eingaben gespeichert oder übertragen.
- GitHub Pages wird von GitHub (USA) betrieben und protokolliert technisch bedingt IP-Adressen der Besucher. Vor dem Einsatz im Unterricht mit der/dem Datenschutzbeauftragten der Schule abstimmen. Alternativ lässt sich der Ordner unverändert auf jedem anderen Webspace ablegen, z. B. dem Server der Schule.

## Neue Modellseite ergänzen

1. HTML-Datei in den Hauptordner legen und direkt nach `<body>` die Navigationsleiste („← Modelle & Begriffe“) aus einer bestehenden Modellseite übernehmen.
2. In `index.html` im Skript den Eintrag unter `MODELS` ergänzen (Themenfeld, Titel, Datei, Bereiche, Fachbegriffe) und die Begriffe unter `TERMS` eintragen. Die Reihenfolge des Lernpfads steht unter `PATH`.
