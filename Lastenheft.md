# 1) Zielbestimmung #

Der Kunde möchte eine Software zur Verwaltung von Dokumente.
Zur Zeit hat der Kunde eine große Menge an Dokumente und Studenten, die diese Dokumente ausleihen wollen. Die Software soll die Studenten, die Dokumente, sowie den Ausleihvorgang  verwalten (Ausleihvorgang, Rückgabe, Verwaltung, Aktualisierung).

# 2) Produkteinsatz #

Die Verwaltungssoftware soll auf einem Webserver laufen.
Anbindung an eine Datenbank ist nötig.
Bedienung über einen Webbrowser über das Internet möglich.

Nutzergruppen:
  * Administrator
  * Mitarbeiter
  * Angemeldeter Student
  * Gast (Onlinebenutzer)

# 3) Produktfunktionen #

## /LF10/ Studenten verwalten ##
  * Neuen Student anlegen
  * Vorhandenen Student bearbeiten
  * Vorhandenen Student löschen

## /LF20/ Dokumente verwalten ##
  * Neues Dokument eintragen
  * Vorhandenes Dokument bearbeiten
  * Vorhandenes Dokument löschen

## /LF30/ Dokumente verleihen ##
  * Vorhandenes Dokument ausleihen
  * Ausgeliehenes Dokument zurücknehmen

## /LF40/ ##

# 4) Produktdaten #

## /LD10/ Benutzerdaten ##
  * eindeutige Identifikationsnummer
  * Barcodenummer
  * Vornamen, Nachname
  * E-Mail Adresse
  * Kommentar (optional)
  * Studiengang
  * Rolle (Benutzergruppe)

## /LD20/ Dokumentdaten ##
  * eindeutige Identifikationsnummer
  * Barcodenummer
  * Dokumenttyp
  * Kurs (z.B. Mathe I)
  * Studiengang
  * Dozent
  * Semester (Jahr)
  * Digitale Version
  * Anzahl der Ausleihvorgänge

## /LD30/ Ausleihdaten ##
  * Datum der Ausleihe
  * Ausgeliehenes Dokument
  * Ausleiher

# 6) Produktleistungen #

## /LL10/ Anbindung an einen Barcodescanner ##

