# intratech - Schritt für Schritt Anleitung

Für den Upload im sapaso Portal benötigen Sie zwei Dateien:

1. [Die Mitgliederdatei](#die-mitgliederdatei)
2. [Die SEPA/Lastschrift-Datei](#sepalastschrift-datei)

Im folgenden zeigen wir Ihnen, Schritt für Schritt, wie Sie diese Dateien in magicline erstellen:  
([Upload auf sapaso.de](upload-im-portal))

## Die Mitgliederdatei

### 1. Gehe zum Menüpunkt Personengruppen

Klicken Sie im Hauptmenü auf den Menüpunkt `Statistik` und dann `Controlling`.
Wählen Sie in der sich öffnenden Seite oben den Reiter `Kundenzahlen`.

Stellen Sie nun bei `Auswahltyp 3` Jahr und Monat auf den Monat für den Abbuchung stattfinden soll.
Wollen Sie z.B. am 1. September 2017 abbuchen, so stellen Sie `Jahr = 2017` und `Monat = September` ein.

Klicken Sie nun bei dem Report "Mitgliederliste aktiver Kunden - Mitgliederliste mit Adress- und Kontaktdaten" rechts auf `Excel`. Speichern Sie diese Datei ab.

> Tipp: Speichern Sie die Mitgliederliste unter einem Namen mit Datum z.B. `Mitgliederliste-September-17.xls`

Die so exportierte Excel-Liste ist ihre Mitgliederliste, die Sie bei uns hochladen - siehe [Upload auf sapaso.de](upload-im-portal)

![intratech Mitgliederliste Exportieren](anleitung/_media/intratech/mitgliederliste/mitgliederliste-exportieren.jpg "Mitgliederliste Exportieren")

## SEPA/Lastschrift-Datei

Sie müssen die folgenden Schritte 2 mal durchführen: Für die Erstlastschrift und für die Folgelastschrift.
Mehr dazu im ersten Schritt:

### Lastschriftlauf Einstellen

Klicken Sie im Hauptmenü auf den Menüpunkt `Buchhaltung` und dann `Debitorenwesen`.  

Wähle Sie für ihre Filiale das Fälligkeitsdatum `Fällig am:` und das Ausführungsdatum `Ausführung am:` aus. Wichtig ist, dass Sie das Datum auf den Tag setzen an dem wir von den Kunden einziehen sollen z.B. `01.09.2017` wenn wir die Monatsbeiträge der Kunden am 1.9. einziehen sollen.

Anschließend wählen Sie bitte zuerst `COR1 - Erstlastschrift` aus und die Erstlastschriften zu erzeugen
und klicken auf `Einstellen` rechts daneben.


Beim zweiten mal wählen Sie hier stattdessen `Folgelastschriften` aus.

> Tipp: Wenn Sie von Erstlastschriften zu Folgelastschriften wechseln verändern sich manchmal
die `Fällig am:` und `Ausführung am:` Werte. Überprüfen Sie die Daten bevor sie weiter machen.

![SEPA/Lastschriftlauf Einstellen](anleitung/_media/intratech/sepa/1-sepa-einstellen.jpg "SEPA/Lastschriftlauf Einstellen")

### Einzüge der Kunden buchen

Klicken Sie auf `weiter`. Im nächsten Fenster sehen Sie die Buchungen. Wenn diese stimmen klicken Sie bitte auf `Buchen`.

![Einzüge der Kunden buchen](anleitung/_media/intratech/sepa/2-einzuege-buchen.jpg "Einzüge der Kunden buchen")

### SEPA/Lastschrift-Datei exportieren

Im nächsten Fenster klicken Sie einfach `Sepa` (siehe Screenshot) und erstellen die Datei.

Nun beginnen Sie den Prozess bitte nochmal von vorn für die [Folgelastschriften](#lastschriftlauf-einstellen)

Dadurch werden die SEPA/Lastschrift-Datei im XML Format erstellt. Diese laden Sie bei uns hoch - siehe [Upload auf sapaso.de](upload-im-portal)

![Sepa Datei exportieren](anleitung/_media/intratech/sepa/3-sepa-datei-exportieren.jpg "Sepa Datei exportieren")
