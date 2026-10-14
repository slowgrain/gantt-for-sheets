---
layout: default
title: Hilfe
lang: de
home_path: /de/
support_path: /de/support/
privacy_path: /de/privacy/
terms_path: /de/terms/
permalink: /de/support/
---

# Support — Gantt Chart for Sheets

**E-Mail: slowgrain.dev@gmail.com** — wir antworten innerhalb von fünf Werktagen.

## Erste Schritte

1. Öffnen Sie die Tabelle mit Ihrer Aufgabenliste.
2. Wählen Sie **Erweiterungen → Gantt Chart for Sheets → Gantt-Diagramm erstellen**.
3. Das Diagramm erscheint im Tabellenblatt **Gantt**. Ihre Aufgabenliste bleibt unverändert.

Führen Sie das Add-on erneut aus, wenn sich der Plan ändert. Das Diagramm wird jedes Mal neu erstellt.

## Eine vorhandene Aufgabenliste verbinden

Die Tabelle kann an beliebiger Stelle beginnen und die Spalten können in jeder Reihenfolge stehen. Überschriften in Englisch, Deutsch, Französisch, Spanisch, Portugiesisch, Japanisch und Koreanisch werden erkannt.

Wenn die automatische Zuordnung nicht passt, wählen Sie **Gantt-Tools → Aufgabenliste verbinden und Vorschau anzeigen**. Legen Sie die Überschriftenzeile fest und ordnen Sie die Spalten zu. Vor dem Speichern sehen Sie bis zu sechs echte Aufgaben, berechnete Termine und die Anzahl der Aufgaben ohne Startdatum oder ohne Termin. Die Zuordnung wird pro Tabellenblatt gespeichert. **Nicht verwenden** verhindert, dass ein Feld automatisch erkannt wird.

| Feld | Beispiele für Überschriften | Erforderlich |
|---|---|---|
| Aufgabenname | Task, Aufgabe, Tarea, 作業 | Ja |
| Start | Start, Beginn, Anfang, Inicio | Ja* |
| Ende oder Dauer | End, Ende, Dauer, Durée | eines von beiden |
| Vorgänger | After, Predecessors, Vorgänger | Nein |
| Fortschritt | Progress, Fortschritt, Progreso | Nein |
| Verantwortliche | Owner, Verantwortliche, Ressourcen | Nein |
| WBS / übergeordnete Aufgabe | Level, Parent, Ebene | Nein |
| Aufwand und Tageskapazität | Total effort, Hours per day | Nein |

* Ein Startdatum kann fehlen, wenn es aus einem Vorgänger berechnet werden kann oder die Zeile eine Phase mit untergeordneten Aufgaben enthält.

## Datumswerte

Verwenden Sie ISO-Daten wie 2026-04-03 oder echte Datumszellen, um Mehrdeutigkeiten zu vermeiden. Bei Zahlenformaten wie 03/04 erkennt das Add-on die Reihenfolge anhand eindeutiger Datumswerte im Blatt. Fehlen solche Hinweise, gilt die übliche Reihenfolge der Sprache.

## Vorgänger eintragen

Tragen Sie die ID der vorherigen Aufgabe in die Vorgängerspalte ein. 12 beginnt nach dem Ende von Aufgabe 12. 12+3 fügt drei Tage Puffer hinzu; 12-1 bedeutet einen Tag Vorlauf. Mehrere IDs werden durch Kommas getrennt.

## Auslastung und Stunden

Tragen Sie Verantwortliche ein, um parallele Aufgaben und die Tageskapazität zu sehen. **Gesamtaufwand (Stunden)** wird gleichmäßig auf Personen und geplante Arbeitstage verteilt. **Stunden pro Tag** hat Vorrang, wenn Sie diesen Wert direkt je Person eingeben. Aufgaben ohne Stundenangabe werden nicht mit erfundenen Schätzwerten in die Berechnung aufgenommen.

## Häufige Fragen

**Eine Aufgabe fehlt im Diagramm.** Der Grund steht unter dem Diagramm. Prüfen Sie Start, Ende, Dauer und zirkuläre Abhängigkeiten.

**Wochenenden sollen nicht zählen.** Aktivieren Sie im Menü **Wochenenden überspringen**. Feiertage werden pro Tabellenblatt eingestellt.

**Das Diagramm ist zu breit.** Die Zeitskala wechselt automatisch zwischen Tagen, Wochen, Monaten und Quartalen. Eine maximale Projektlaufzeit gibt es nicht.

**Ich habe mehr als 50 Aufgaben.** Der kostenlose Tarif unterstützt 50 Aufgaben; Pro hebt das Limit auf. Aufgaben über dem Limit werden gemeldet und nicht stillschweigend entfernt.

## Lizenzschlüssel

Pro kaufen: https://slowgrain.app/gantt-for-sheets/de/#pro

Wählen Sie zum Eingeben **Erweiterungen → Gantt Chart for Sheets → Lizenz → Lizenzschlüssel eingeben**. Der Schlüssel wird in Ihrem Google-Konto gespeichert und muss nur einmal eingegeben werden.

Wenn der Schlüssel nicht ankommt, verloren geht oder abgelehnt wird, schreiben Sie dem Support mit Ihrer Bestellreferenz. Schlüssel beginnen mit GS1. und enthalten keine Leerzeichen.

## Problem melden

Schreiben Sie an **slowgrain.dev@gmail.com** und senden Sie uns:

- was Sie erwartet haben und was stattdessen passiert ist
- einen Screenshot des Diagramms oder der Fehlermeldung
- nach Möglichkeit eine Kopie der Tabelle ohne vertrauliche Inhalte

Das Add-on sendet keine Daten selbstständig. Hängen Sie Dateien nur an, wenn Sie sie teilen möchten.
