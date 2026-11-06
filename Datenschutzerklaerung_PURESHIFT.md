# Datenschutzerklärung für PURESHIFT

**Stand:** 06. November 2026

## 1. Verantwortlicher

Verantwortlich für die Datenverarbeitung im Zusammenhang mit der Android-App **PURESHIFT** (nachfolgend „App") ist:

**Adonis Japalak**
Blücherstraße 39
86165 Augsburg
Deutschland

E-Mail: NextExchangeStudio@proton.me

## 2. Allgemeines zur Datenverarbeitung

PURESHIFT ist eine Schichtplaner-App mit Mitarbeiterverwaltung. Die von Ihnen eingegebenen Schicht- und Mitarbeiterdaten werden lokal auf Ihrem Android-Gerät gespeichert. Der Anbieter betreibt für diese App-Daten keinen zentralen Server und keine eigene Cloud-Synchronisation. Im normalen Betrieb erhält der Anbieter keine Kopie dieser Daten.

Die Kernfunktionen der App können offline genutzt werden. Die optionale WLAN-Freigabe benötigt ein lokales Netzwerk. Internetzugriff ist erforderlich, wenn Sie die in der App verlinkten Rechtsinformationen bei GitHub öffnen.

Daten können Ihr Gerät verlassen, wenn Sie sie selbst exportieren oder teilen (Abschnitt 5), wenn Android eine Gerätesicherung durchführt (Abschnitt 7) oder wenn Sie externe Links öffnen (Abschnitt 10). Bei einer Weitergabe an eine andere App oder einen Cloud-Dienst gelten zusätzlich deren Datenschutzbestimmungen.

Eine Registrierung oder ein Nutzerkonto ist nicht erforderlich.

## 3. Welche Daten werden lokal verarbeitet?

Folgende Daten werden auf Ihrem Gerät gespeichert:

- Schichten und Schichteinträge (Datum, Uhrzeiten, Notizen und gegebenenfalls ein von Ihnen eingetragener Einsatzort) sowie Schichttausch-Einträge
- Schichttypen (Bezeichnung, Farbe, Stundenangaben und Pausen) und Schichtgruppen
- Kalender- und Gruppenbezeichnungen
- Einstellungen zu Währung, Gehalts- bzw. Steuerberechnung, Bundesland, Sprache, Darstellung und Widgets
- Startzeitpunkt einer laufenden Zeiterfassung (Timer)
- PDF-Export-Vorlagen und -Einstellungen
- **Mitarbeiterdaten**, sofern Sie die Mitarbeiterverwaltung nutzen und befüllen (alle Felder sind freiwillig):
  - Name und Geburtsdatum
  - Kontaktdaten (E-Mail privat/dienstlich, Telefon, Mobilnummer und Anschrift)
  - Beschäftigungsdaten (Eintritt/Austritt, Beschäftigungsart, Abteilung, Position und Standort)
  - Vergütungsdaten (Gehalt, Bankverbindung und Steuerklasse)
  - Sozialversicherungsdaten (Sozialversicherungsnummer, Steuer-ID, Kranken- und Rentenversicherung)
  - Urlaubsdaten sowie Qualifikationen, Trainings, Zertifikate und Schlüsselübergabe

Für Android-Widgets wird außerdem eine lokale Zusammenfassung kommender Schichten gespeichert.

Für die WLAN-Freigabe speichert die App technische Synchronisationsdaten, darunter die Kopplungs-PIN, Kennungen und Zugriffstoken gekoppelter Geräte, den Zeitpunkt der letzten Synchronisierung sowie die Einstellung zur automatischen Annahme von Schreibvorgängen.

## 4. Verantwortlichkeit bei Mitarbeiterdaten

Wenn Sie die App zur Verwaltung personenbezogener Daten anderer Personen, zum Beispiel von Beschäftigten, nutzen, müssen Sie prüfen, wer für diese Verarbeitung datenschutzrechtlich verantwortlich ist. Das kann je nach Einsatz insbesondere Ihr Arbeitgeber oder Ihr Unternehmen sein.

Die verantwortliche Stelle muss eine Rechtsgrundlage für die Verarbeitung haben, betroffene Personen informieren und die Daten angemessen schützen. Für Beschäftigtendaten können besondere gesetzliche Vorgaben gelten.

Der Anbieter erhält im normalen Betrieb keinen Zugriff auf die lokal gespeicherten Mitarbeiterdaten. Sicherungen, von Ihnen veranlasste Übertragungen und externe Dienste werden in den folgenden Abschnitten beschrieben.

## 5. Vom Nutzer ausgelöste Datenübertragungen

### 5.1 Datensicherung (Backup / Restore)

Über die Funktion „Datensicherung" können Sie eine JSON-Datei mit App-Daten exportieren und wieder importieren. Ein vollständiger Export kann auch Mitarbeiterdaten enthalten.

Bei einem Zeitraum-Export werden nur Schichteinträge und Schichttausch-Einträge des gewählten Zeitraums eingeschränkt. Weitere Daten, etwa Mitarbeiterstammdaten und Einstellungen, können weiterhin vollständig enthalten sein.

Die JSON-Datei ist nicht verschlüsselt. Auf Android wählen Sie den Speicherort über die System-Dateiauswahl aus. Wenn Sie dafür eine Cloud-, Messenger- oder andere Drittanbieter-App auswählen, können deren Anbieter die Datei erhalten und nach ihren eigenen Datenschutzbestimmungen verarbeiten. Der Anbieter von PURESHIFT erhält keine Kopie.

### 5.2 PDF-Export

Beim Erstellen eines PDF-Dokuments aus Ihren Schichtdaten wird die Datei lokal auf dem Gerät erzeugt. Anschließend können Sie sie über die Systemfunktionen teilen, drucken oder speichern. Wenn Sie dafür eine andere App oder einen externen Dienst auswählen, verarbeitet dieser die Datei nach seinen eigenen Datenschutzbestimmungen. Eine Übermittlung an den Anbieter von PURESHIFT erfolgt durch den PDF-Export nicht.

### 5.3 Kalender teilen

Die Funktion „Kalender teilen" erzeugt lokal ein Bild Ihres Schichtkalenders. Sie können dieses Bild anschließend über die Teilen-Funktion Ihres Geräts an andere Personen oder Apps senden. Mit wem Sie es teilen, entscheiden Sie selbst.

### 5.4 WLAN-Freigabe (Synchronisation zwischen Geräten)

Die App bietet optional eine „WLAN-Freigabe". Wenn Sie diese aktivieren, startet die App auf Ihrem Gerät einen lokalen Server, der im selben lokalen Netzwerk erreichbar ist. Ein anderes Gerät kann sich mit der angezeigten PIN koppeln und anschließend App-Daten abrufen oder übermitteln. Dabei können sämtliche App-Daten einschließlich Mitarbeiterdaten übertragen werden.

Bitte beachten Sie:

- Die WLAN-Freigabe ist standardmäßig ausgeschaltet und wird nur durch Sie aktiviert.
- Die Übertragung erfolgt innerhalb des lokalen Netzwerks über HTTP und ist nicht verschlüsselt. Nutzen Sie die Funktion nur in vertrauenswürdigen Netzwerken, nicht in öffentlichen WLANs.
- Für die Synchronisierung wird kein zentraler Server des Anbieters verwendet.
- Gekoppelte Geräte können Daten lesen.
- Schreibvorgänge gekoppelter Geräte werden standardmäßig ohne weitere Bestätigung angenommen („Immer akzeptieren"). Wenn Sie diese Einstellung deaktivieren, werden eingehende Schreibvorgänge abgelehnt; eine Bestätigungsabfrage wird dabei nicht angezeigt.
- Wenn Sie die PIN neu erzeugen, werden die bisherigen Kopplungen widerrufen.
- Schalten Sie die WLAN-Freigabe nach der Nutzung wieder aus.

## 6. Berechtigungen und Systemfunktionen

Die App nutzt Netzwerk- und Systemfunktionen für folgende Zwecke:

- **Netzwerk:** für die optionale WLAN-Freigabe, die Anzeige der lokalen Netzwerkadresse und das Öffnen der verlinkten Datenschutzerklärung sowie des Impressums im Browser
- **Vibration:** für Rückmeldungen bei der Bedienung
- **Datei- und Teilen-Funktionen:** für den Import und Export von Sicherungsdateien sowie das Teilen von PDF- und Kalenderdateien. Auf Android wählen Sie Dateien oder Speicherorte über die Systemauswahl aus.

Die App verwendet keine Kamera, kein Mikrofon, keine GPS-Standortbestimmung und keine Kontakte. Ein von Ihnen manuell eingetragener Einsatzort oder Mitarbeiterstandort ist kein GPS-Standort. Die App versendet keine Push-Benachrichtigungen.

## 7. Datensicherung durch das Betriebssystem (Android)

Die Android-App ist für Gerätesicherungen zugelassen. Wenn die Sicherung auf Ihrem Gerät beziehungsweise in Ihrem Google-Konto aktiviert ist, können App-Daten automatisch in eine Google-Sicherung aufgenommen werden. Dazu können auch lokal gespeicherte Schicht- und Mitarbeiterdaten gehören.

Ob eine Sicherung durchgeführt wird, hängt von Android und Ihren Geräte- und Kontoeinstellungen ab. Die Sicherung wird durch Google und nicht durch den Anbieter von PURESHIFT durchgeführt. Es gelten die Datenschutzhinweise von Google: https://policies.google.com/privacy

Wenn Sie keine solche Sicherung möchten, prüfen und ändern Sie die Sicherungseinstellungen Ihres Geräts und Google-Kontos.

## 8. Keine Analyse-, Tracking- oder Werbedienste

Die App enthält keine Analyse-, Tracking-, Werbe- oder Social-Media-Dienste. Es werden keine Gerätekennungen zu Werbe- oder Analysezwecken erhoben.

Für die WLAN-Freigabe verwendet die App eine lokale Gerätekennung und Zugriffstoken für gekoppelte Geräte. Diese Daten dienen der Synchronisierung im lokalen Netzwerk und werden nicht an den Anbieter übermittelt.

## 9. Verarbeitung durch Google Play

Wenn Sie die App über Google Play herunterladen oder aktualisieren, verarbeitet Google Daten im Zusammenhang mit dem Store-Betrieb und der Bereitstellung der App. Welche Daten dabei verarbeitet werden, hängt unter anderem von Ihrem Google-Konto, Ihrem Gerät und Ihren Einstellungen ab.

Auf diese Verarbeitung hat der Anbieter von PURESHIFT keinen Einfluss. Es gelten die Datenschutzhinweise von Google: https://policies.google.com/privacy

## 10. Aufruf dieser Datenschutzerklärung und des Impressums

Die Datenschutzerklärung und das Impressum werden auf GitHub bereitgestellt. Wenn Sie einen dieser Links in der App öffnen, wird die entsprechende GitHub-Seite in Ihrem Browser geladen. Dabei erhält GitHub technisch notwendige Verbindungsdaten, insbesondere Ihre IP-Adresse. Es gelten die Datenschutzhinweise von GitHub: https://docs.github.com/site-policy/privacy-policies/github-privacy-statement

## 11. Build- und Distributionsdienste

Die App wird mit Expo entwickelt und mithilfe von Expo Application Services (EAS) erstellt und verteilt. Für den Build verarbeitet Expo technische Projekt- und Build-Daten. Das ist von den Daten zu unterscheiden, die Sie in der App eingeben.

Im laufenden Betrieb übermittelt PURESHIFT keine eingegebenen Schicht- oder Mitarbeiterdaten an Expo.

## 12. Rechte betroffener Personen

Die in der App eingegebenen Schicht- und Mitarbeiterdaten werden lokal auf Ihrem Gerät gespeichert und stehen dem Anbieter nicht über einen zentralen Server zur Verfügung. Der Anbieter kann diese lokalen Inhalte daher nicht aus einer zentralen Datenbank abrufen, ändern oder löschen.

Das bedeutet nicht, dass Rechte gegenüber Stellen entfallen, die Daten tatsächlich verarbeiten. Für Daten, die Sie über Sicherungen, externe Links oder Drittanbieter-Apps weitergeben, sind die jeweils beteiligten Stellen und deren Datenschutzinformationen maßgeblich. Personen, deren Daten Sie in der App erfassen, wenden sich für ihre Rechte an die für diese Verarbeitung verantwortliche Stelle, zum Beispiel an ihren Arbeitgeber.

Sie können Ihre lokalen Daten in der App ansehen, ändern und exportieren. Durch die Deinstallation der App werden die lokal gespeicherten App-Daten grundsätzlich vom Gerät entfernt. Exportdateien, Kopien auf anderen Geräten und Android-Sicherungen müssen gegebenenfalls separat gelöscht werden.

Sie haben außerdem das Recht, sich bei einer Datenschutz-Aufsichtsbehörde zu beschweren.

## 13. Datensicherheit

Die App speichert ihre Daten im internen App-Speicher des Geräts. Dieser wird durch das Betriebssystem vom Zugriff anderer Apps abgeschirmt. Die App verschlüsselt die gespeicherten Daten nicht zusätzlich.

Für den Schutz Ihres Geräts sind Sie selbst verantwortlich. Dazu gehören insbesondere eine Gerätesperre, die Geräteverschlüsselung und aktuelle Software-Updates. Bei der WLAN-Freigabe und beim Teilen von Dateien gelten zusätzlich die Hinweise in Abschnitt 5.

## 14. Kinder

Die App richtet sich nicht an Kinder unter 16 Jahren.

## 15. Änderungen dieser Datenschutzerklärung

Diese Datenschutzerklärung kann angepasst werden, wenn sich die App, die Datenverarbeitung oder die Rechtslage ändert. Die jeweils aktuelle Fassung ist über den in der App angezeigten Link und gegebenenfalls im Store-Eintrag abrufbar.

## 16. Kontakt

Bei Fragen zum Datenschutz wenden Sie sich bitte an: NextExchangeStudio@proton.me
