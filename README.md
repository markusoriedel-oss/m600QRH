# M600 QRH

Das Quick Reference Handbook der Piper M600 als klickbare, offline lauffähige App
fürs iPhone. Grundlage ist das M600 QRH Book Version 1.3.

**Live: https://markusoriedel-oss.github.io/m600QRH/**

Aktueller Stand: QRH v.1.3, APP v.0.4

## Aufs iPhone legen

Die App wird nicht aus dem App Store installiert, sondern direkt aus Safari auf
den Home-Bildschirm gelegt. Danach läuft sie im Vollbild und ohne Netz.

1. **Safari** öffnen und https://markusoriedel-oss.github.io/m600QRH/ aufrufen.
   Safari ist Pflicht: Chrome und Firefox können auf dem iPhone keine App
   ablegen, die offline funktioniert.
2. **Einmal komplett laden lassen**, am besten im WLAN. Es sind rund 17 MB, weil
   alle Original-QRH-Seiten als Bilder mitgeliefert werden. Ein paar Sekunden
   warten, bis die Startseite steht.
3. Auf das **Teilen-Symbol** tippen (Quadrat mit Pfeil nach oben), dann
   **Zum Home-Bildschirm**, dann **Hinzufügen**.
4. Die App **einmal vom Home-Bildschirm starten, solange noch Netz da ist.**
   Erst dabei legt sie alle Dateien dauerhaft lokal ab.

Fertig. Ab jetzt startet sie auch im Flugmodus.

## Offline prüfen

iPhone in den Flugmodus, App vom Home-Bildschirm starten, eine Checkliste öffnen
und unten „Show original QRH page" antippen. Erscheint die eingescannte
Originalseite, liegt wirklich alles lokal.

Zeigt die App stattdessen eine leere oder halbe Seite: Netz wieder einschalten,
App öffnen, eine Minute geöffnet lassen, dann erneut im Flugmodus testen.

## Updates

Es genügt, die App mit Netz zu starten. Sie erkennt eine neue Version an ihrer
App-Nummer und lädt sie im Hintergrund. Beim übernächsten Start ist der neue
Stand aktiv. Die Version steht oben im Kopf der Startseite (`QRH v.1.3 · APP v.0.4`).

Wenn eine Version einmal hängen bleibt: App vom Home-Bildschirm löschen und die
vier Schritte oben wiederholen. Es gehen keine Daten verloren, die App speichert
nichts, was der Nutzer eingegeben hat.

## Farben der CAS-Meldungen

Die App gibt die drei Darstellungen des QRH unverändert wieder:

| Stufe | Darstellung |
|---|---|
| Warning | roter Hintergrund, weiße Schrift |
| Caution | schwarzer Hintergrund, gelbe Schrift |
| Advisory | schwarzer Hintergrund, weiße Schrift |

Die Stufe hängt an der Fundstelle, nicht am Namen der Meldung. `T/O CONFIG`
erscheint auf ein und derselben QRH-Seite einmal als Advisory und einmal als
Warning, ebenso wechseln `FUEL QTY`, `CHECK GEAR`, `GEAR SYS` und `HYDR PUMP ON`
je nach Situation zwischen Warning und Caution. Die Farben sind deshalb direkt
aus dem PDF ausgelesen und nicht abgeleitet.

## Hinweis

Private Lesehilfe, kein zugelassenes Dokument. Verbindlich sind allein das an
Bord mitgeführte QRH und das POH.
