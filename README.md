# Lila-Gelb Ticker

Live-Spielstände von der 1. Bundesliga bis zur Regionalliga, mit Halbzeit-Anzeige und einem Modell-Tipp fürs Tippspiel. Design in den Farben von Alemannia Aachen (Schwarz-Gelb) und dem VfL Osnabrück (Lila-Weiß).

## Ligen und Datenquellen

| Liga | Quelle | Key nötig |
|---|---|---|
| 1. und 2. Bundesliga, 3. Liga | OpenLigaDB | nein |
| Regionalliga Nord, Nordost | OpenLigaDB | nein |
| Regionalliga West, Südwest, Bayern | API-Football | ja, kostenlos (100 Abrufe pro Tag) |

OpenLigaDB wird von einer Community gepflegt und liefert keinen Live-Status. Spielminute und Halbzeit werden dort aus der Anstoßzeit geschätzt (angezeigt mit „~“). API-Football liefert Minute und Halbzeit direkt.

## Veröffentlichen mit GitHub Pages

1. Alle Dateien aus diesem Ordner ins Repository legen (oberste Ebene, `index.html` muss direkt im Repo liegen).
2. Im Repository: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, Branch `main`, Ordner `/ (root)`, speichern.
3. Nach ein bis zwei Minuten ist die App unter `https://<benutzername>.github.io/<repo-name>/` erreichbar.

## Auf dem Pixel installieren

Adresse in Chrome öffnen, oben rechts auf die drei Punkte tippen, dann **App installieren** (oder **Zum Startbildschirm hinzufügen**).

## API-Football-Key

Kostenlos registrieren auf dashboard.api-football.com, den Key kopieren und in der App unter Einstellungen eintragen. Der Key bleibt nur auf deinem Handy gespeichert.
