---
layout: default
title: Datenschutz
lang: de
home_path: /de/
support_path: /de/support/
privacy_path: /de/privacy/
terms_path: /de/terms/
permalink: /de/privacy/
---

# Datenschutzerklärung für Gantt Chart for Sheets

**Zuletzt aktualisiert: 14. Oktober 2026**

## Kurzfassung

Dieses Add-on hat keine Berechtigung für den Internetzugriff. Es liest Ihre Aufgabenliste, erstellt daraus ein Gantt-Diagramm und schreibt es in ein Tabellenblatt derselben Tabelle. Über das Add-on erheben, speichern, verkaufen oder teilen wir keine personenbezogenen Daten.

## Worauf das Add-on zugreifen kann

Es fordert genau diese zwei Berechtigungen an:

| Berechtigung | Umfang | Zweck |
|---|---|---|
| Nur die aktuell verwendete Google-Sheets-Datei ansehen, bearbeiten, erstellen und löschen | `spreadsheets.currentonly` | Aufgabenliste lesen und das Diagramm in ein Tabellenblatt derselben Datei schreiben |
| Webinhalte in Nachrichten und Seitenleisten anzeigen und ausführen | `script.container.ui` | Menü und Dialogfelder des Add-ons anzeigen |

Google ergänzt Ihren Namen und Ihre E-Mail-Adresse auf dem Installationsbildschirm des Google Workspace Marketplace. Das gilt für alle dort angebotenen Add-ons. Der Add-on-Code liest diese Daten nicht; wir erhalten oder speichern sie ebenfalls nicht.

Das Add-on greift nicht auf Google Drive, andere Tabellen, E-Mails, Kontakte oder Kalender zu. Es hat auch keine Berechtigung `script.external_request` und kann deshalb keine externen Netzwerkverbindungen herstellen.

## Was wo gespeichert wird

Im Google-Speicher für Add-ons innerhalb Ihres Kontos werden folgende Daten gespeichert:

1. Einstellungen pro Tabelle: Wochenenden überspringen und kritischen Pfad hervorheben.
2. Ihr Lizenzschlüssel, falls vorhanden. Er kann Tarif, Ablaufdatum und Kaufreferenz enthalten, jedoch nicht Ihren Namen oder Ihre E-Mail-Adresse.

Wenn Sie das Add-on deinstallieren, löscht Google diese Daten. Sie können den Lizenzschlüssel jederzeit selbst löschen: Öffnen Sie **Erweiterungen → Gantt Chart for Sheets → Lizenz**, lassen Sie das Feld leer und bestätigen Sie.

## Daten beim Kauf einer Lizenz

Käufe werden vom Zahlungsanbieter und nicht vom Add-on verarbeitet. Beim Kauf von Pro erhalten wir eine Bestellreferenz und die E-Mail-Adresse, an die der Lizenzschlüssel gesendet werden soll. Ihre Kartendaten sehen oder speichern wir nie. Ein separates Google-Apps-Script erzeugt den Schlüssel und sendet ihn per E-Mail. Bestellreferenz und E-Mail-Adresse werden im privaten Speicher unseres Kontos aufbewahrt.

Wir verwenden diese Daten nur zur Ausgabe oder erneuten Zusendung des Schlüssels und für gesetzlich vorgeschriebene Aufzeichnungen. Wir verwenden sie nicht für Marketing und geben sie nicht an Dritte weiter. Die Daten bleiben nur so lange gespeichert, wie es die steuerlichen Aufbewahrungspflichten verlangen. Danach werden sie gelöscht. Soweit gesetzlich zulässig, können Sie eine frühere Löschung beantragen.

## Schutz Ihrer Daten

**Während der Übertragung:** Ihre Tabellendaten verlassen die Google-Infrastruktur nicht. Das Add-on wird als Google Apps Script ausgeführt und schreibt das Diagramm in dieselbe Datei. Google schützt die Verbindung zwischen Browser und Script mit TLS. Das Add-on hat keine Berechtigung für externe Netzwerke.

**Gespeicherte Daten:** Wir bewahren keine Kopie Ihrer Tabellendaten auf. Aufgabennamen, Termine und Verantwortliche werden nur während der Diagrammerstellung im Arbeitsspeicher verarbeitet und danach verworfen. Einstellungen und Lizenzschlüssel werden im Google-`PropertiesService` gespeichert und von Google im Ruhezustand verschlüsselt. Wir können diese Werte nicht lesen.

**Zugriffskontrolle:** Es gibt keinen Weg, über den Slowgrain auf Ihre Tabellendaten zugreifen kann. Es gibt keine Beschäftigten, Auftragnehmer oder sonstigen Datenverarbeiter mit Zugriff darauf. Das veröffentlichte Apps-Script-Projekt gehört einem einzelnen Google-Konto. Das Geheimnis zum Signieren von Lizenzschlüsseln wird weder in das Quellcode-Repository eingecheckt noch in veröffentlichten Code aufgenommen.

## Aufbewahrung und Löschung

- Tabellendaten bewahren wir nicht auf.
- Google löscht Einstellungen und Lizenzschlüssel bei der Deinstallation. Den Schlüssel können Sie auch selbst löschen.
- Bestellreferenz und Versand-E-Mail werden nur für die steuerrechtlich vorgeschriebene Aufbewahrungszeit gespeichert und danach gelöscht. Kontaktieren Sie uns, wenn Sie eine frühere Löschung beantragen möchten, soweit das Gesetz sie erlaubt.

Das Diagramm wird in ein Tabellenblatt Ihrer eigenen Datei geschrieben und übernimmt deren Freigabeeinstellungen. Personen, mit denen Sie die Datei geteilt haben, können das Diagramm ebenso wie die Aufgabenliste sehen. Wir veröffentlichen oder teilen das Diagramm nicht.

## Google Workspace APIs und KI-Modelle

Wir verwenden keine Daten aus Google Workspace APIs zur Entwicklung, Verbesserung oder zum Training allgemeiner oder nicht personalisierter KI- oder Machine-Learning-Modelle. Das Add-on verwendet weder KI noch maschinelles Lernen; Zeitpläne werden mit gewöhnlichen Berechnungen erstellt.

Die Nutzung und Übertragung von Informationen aus Google APIs richtet sich nach der [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), einschließlich der Anforderungen zur eingeschränkten Nutzung.

## Kinder

Dieses Add-on ist ein Geschäftswerkzeug und richtet sich nicht an Kinder unter 13 Jahren.

## Änderungen

Wenn sich diese Datenschutzerklärung ändert, aktualisieren wir das Datum oben und veröffentlichen die aktuelle Fassung unter dieser URL.

## Kontakt

Bei Fragen zum Datenschutz oder einem Antrag auf Löschung gespeicherter Daten:

**slowgrain.dev@gmail.com**

Wir antworten innerhalb von fünf Werktagen.
