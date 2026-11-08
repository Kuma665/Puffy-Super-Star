# [Spielname] – Projektregeln

## Vor jeder Arbeit
- Kurz, freundlich, auf Deutsch antworten. Nur ändern, worum ich bitte.
- Richtigen Ordner/Datei prüfen; bei mehreren Kopien nachfragen.
- Vor Änderungen `git status`; bei offenen Änderungen Sicherung außerhalb des Repos anlegen und Pfad nennen.
- Lokal committen nach jedem fertigen Feature („Spiel aktualisiert: …“). Pushen nur auf ausdrückliche Bitte.
- Nur nötige Codebereiche lesen, nie das ganze Skript ausgeben.
- Bei klarer Empfehlung direkt umsetzen und berichten; nur bei Geschmacksfragen oder Löschen vorher fragen.
- Ehrlich nennen, was geprüft wurde. Nie behaupten, gespielt/sicher behoben, wenn nicht geprüft.

## Projekt
- Spiel in einer HTML-Datei (`index.html`), Pfad: `C:\Users\arams\Documents\GitHub\[Spielname]`.
- Veröffentlicht über GitHub Pages.

## Schutzregeln
- Große Daten-Dateien (Base64, Musik) nie lesen, ausgeben oder bearbeiten.
- Suchen mit Perl/awk (kein Python), Zeilen über 20.000 Zeichen überspringen, Ausgaben kurz halten.
- Vor neuen Funktions-/Feldnamen prüfen, ob es sie schon gibt.
- Keine Pakete installieren, keine Subagenten oder langen Tests ohne Rückfrage.

## Spielgerät
- Handy (OnePlus 12, Browser) mit PS5-Controller. Kleiner Bildschirm: HUD sparsam. Handy-Leistung mitbedenken.

## Performance
- Viele gleiche Objekte als InstancedMesh; Geometrien/Materialien wiederverwenden, nichts pro Frame neu erzeugen.
- Entferntes mit `dispose()` freigeben. Effekte mit fester Obergrenze. DOM nicht jeden Frame ändern.
