# Datenbank: Arbeitsprotokoll
<a href="">

# Inhaltsverzeichnis

## 1.Woche 02.12.2019-08.12.2019
## 2.Woche 09.12.2019-14.12.2019
## 3.Woche 13.01.2020-19.01.2020
## 4.Woche 20.01.2020-26.01.2020
## 5.Woche 27.01.2020-02.02.2020
## 6.Woche 03.02.2020-09.02.2020
## 7.Woche 10.02.2020-16.02.2020
## 8.Woche 17.02.2020-23.02.2020
## 9.Woche 02.03.2020-08.03.2020
## 10.Woche 09.03.2020-15.03.2020

# 1.Woche 02.12.2019-08.12.2019

## Mittwoch, der 04.12.2019

Heute habe ich mich darüber informiert, welche Programme ich zum Bau meiner Datenbank benötige. Das ist nämlich erst mal einen Testserver, dafür habe ich Xampp gewählt, weil es kostenlos ist und mit vielen Programmen synergiert. Zusätzlich benötigt man einen Editor in dem man Tabellen erstellen kann und der mit Php kompatibel ist, weil Php das beste Programm zur Kommunikation zwischen Datenbank und Website ist. Als diesen Editor habe ich MySQL gewählt, da es die Bedingungen erfüllt und viele Entwickler es benutzen. Mein Plan ist es jetzt diese Programme zu installieren und mich mit diesen Programmen vertraut zu machen.

## Donnerstag, der 05.12.2019

Am Donnerstag habe ich Xampp und MySQL installiert. Jedoch hatte ich ein paar Probleme mit dem installieren der MySQL Workbench. Diese Proble Konnte ich aber nachdem ich mir ein Tutorial angeschaut habe lösen und es funktionierte ebenfalls. Als nächtes mache ich mich dann mit beiden Programmen vertraut.

# 2.Woche 09.12.2019-14.12.2019

## Dienstag, der 10.12.2019

Heute habe ich mir einen Artikel zu Xampp durchgelesen und ein Tutotial angeschaut, wie Xampp funktioniert. Danach habe ich mein Xampp Control Panel geöffnet und die mein Apache sowie mein MySQL-Modul gestartet. Als nächtes werde ich mir MySQL Kenntnisse aneignen um meine Datenbank zu schreiben, die ich dann mit meiner Website verbinden will.

## Mittwoch, der 11.12.2019

Am Mittwoch habe ich mich mit den Tutorials von "Programmieren und Starten" einiges über Datenbanken gelernt, wie beispielsweise ein theoretischer teil zum Aufbau einer Datenbank und eines Datenbankmanagmentsystems(DBMS) sowie ein Video zur Erstellung der ersten Datenbank. Dieses funktioniert mit create Database, dann muss man noch eine Tabelle erstellen mit verschiedenen Spalten, die man mit insert into füllen kann. Morgen will ich mit den Videos weitermachen, um bald mit meiner eigenen Datenbank anzufangen.

## Donnerstag, der 12.12.2019

Heute habe ich mit den Videos von "Programmieren und Starten" weiter gemacht, dabei habe ich die "where" Funktion kennengelernt mit der man "select" Anfrage genauer formulieren kann und somit spezifische Werte ausgeben lassen kann. Ebenfalls ging es um den Primärschlüssel, seine Bedeutung und seine Verwendung. Er ist wichtig um der Tabelle eine Struktur zu geben, denn jeder Zeile wird ein Wert zugeteilt andhand dessen man die Information identifizieren kann, wie eine ID. Außerdem lernte ich wie man Datensätze der Tabelle verändert mit "update" oder sie löscht mit delete. Nächste will ich die Videos beenden und mit der Verbindung der drei Elemente, Datenbank, Php Dokument und Website anfangen.

# 3.Woche 13.01.2020-19.01.2020

## Dienstag, der 14.01.2020

Am Dienstag habe wieder mit den Videos von Programmieren und Starten weitergebildet, es ging um die verschiedenen Datentypen, welche man für die Spalten der Tabelle auswählen. Beispiele für Text sind der "char" und der "varchar", man durch Zahlen auf ein Maximum begrenzt, der Unterschied liegt in der mit zu wenigen Buchstaben umzugehen. Hat beispielsweise ein Wort, in einer Spalte mit der Definition "char", nicht genügend Buchstaben so werden die Fehlenden mit Leerzeichen gefüllt z.B. char(8) (Brot....). Beim varchar hingegen wird die Länge an das Wort angepasst z.B. varchar(8) (Brot). Auch den Null-Wert habe ich benutzen gelernt, er ist dafür um einen fehlenden Wert in einer zu ersetzen, wenn verhinder möchte, das dies in einer Spalte möglich ist, muss man der Spalte die definition "not null" geben.

## Mittwoch, der 15.01.2020

Heute ich mit den Videos abgeschlossen, dabei habe ich noch einmal einiges gelernt, wie beispielsweise wie man mit SQL rechnet, das ist relativ man verwendet eine "select" Anfrage. Das kann zur Berechnung von Finanzen nutzen. Ich habe mich mit dem Spalten Alias vertraut gemacht. Ebenfalls habe ich die Befehle "order by", "limit" und "group by" kennengelernt, alle drei spezifizieren den "select" Befehl z.B. reduziert "limit" die Anzahl ausgegebenen Zeilen, während man mit "order by" die Sotierung der Tabelle verändern kann. "group by" hingegen um mehrere Zeilen über eine Spalte in Gruppen einzuteilen, um dann diese jeweils bearbeiten zu können. Morgen will mit dem Verbinden meines Php Dokuments mit meiner Datenbank weitermachen.

## Donnerstag, der 16.01.2020

Am Donnerstag habe ich mir ein Tutorial zu dem Thema, Php mit Datenbank verbinden angeschaut. Daraufhin habe ich mich bei phpmyadmin angemeldet und eine Datenbank angelegt mit dem Namen "data". Danach habe ich ein Tabelle für die Accounts auf meiner Seite erstellt mit sieben Spalten und zwar id, email, passwort, vorname, nachname, created_at und updated_at. Für id habe ich die Befehle "primary", "int" und "auto_increment" ausgewählt, damit es ein Primärschlüssel wird, als Zahl definiert wird und durch "auto_increment" sich bei jedem neuen Eintrage um eins erhöht. Für die vier Textbereiche habe ich ein "varchar" Befehl benutz, weil bei allen vieren verschiedene Wortlängen möglich sein müssen. Nächste Stunde will ich dann auch beide miteinander verbinden.

# 4.Woche 20.01.2020-26.01.2020

## Dienstag, der 21.01.2020

Am Dienstag hatten wir einen Besuch im DESY, weswegen kein Fortschritt erfolgt ist.

## Mittwoch, der 22.01.2020

Heute habe ich angefangen mit der Website "php-einfach.de" zu arbeiten um meine Php-Dateine für meine Website zuerstellen. Dort hab ich dann nach Loginscripts gesucht um die Mechaniken zu verstehen. Zuerst einmal habe ich mir angeschaut wie man das Php-script und habe es um gesetzt, indem ich die Variable $con erstellt und sie mit den Zugangsdaten für die Datenbank gafüllt habe, diese habe ich als Variablen angegeben. Als nächstes will ein Php Dokument zur Speicherung der beim Registrieren eingegebenen Daten in meiner Datenbank.

## Donnerstag, der 23.01.2020

Am Donnerstag habe ich mit meinem Php Dokument angefangen, zuerst habe ich michum die Registrierung kümmern wollen, weil man das auf einer Website zuerst macht. Dafür habe ich meine html Datei für das Registrierungsformular genommen und habe es in ein php Dokument umgewandelt und es im xampp Ordner unter einem einzelnen Odner abgespeichert. Das habe ich ebenfalls mit dem Loginformular und der Accountseite gemacht.
Daraufhin habe ich mit den if Anweisungen, erst einmal ein if geschrieben, für den Fall, dass jemand eine nicht existierende email angibt der Benutzer bekommt dann einen Hinweis das er eine gültige email angeben soll. Auch zwei weitere if´s damit jeder ein passwort hat und beide geschriebenen Passwörter übereinstimmen. 

# 5.Woche 27.01.2020-02.02.2020

## Dienstag, der 28.01.2020

Heute habe ich mit dem Formular weitergemacht, indem ich mit if Anweisungen und den Funktionen prepare, execute und fetch 
dafür gesorgt habe das keine email mehrere Accounts hat, indem ich eine "select" Abfrage in Php geschrieben habe. Außerdem habe ich damit das einfügen der Daten in die Tabelle möglich gemacht eine weitere if Anweisung zur Überprüfung geschrieben. Falls es nicht funktioniert wird man zum Formular zurück geleitet. Als nächstes will das Loginformular machen.

# 6.Woche 03.02.2020-09.02.2020

## Dienstag, der 04.02.2020

Am Dienstag habe ich mein Loginformular gemacht, dabei habe ich zwei if Anweisungen benutzt und in der einen wird die passende Email mit einer Select Abfrage ausgewählt, mit der anderen wird das Passwort überprüft. Ebenfalls wird dem Benutzer mit geteilt, ob der Login erfolgreich war oder nicht. Daraufhin wird er weitergeleitet. Ich will morgen mit der Accountseite anfangen.

## Mittwoch, der 05.02.2020

Heute habe ich mit dem Kontaktformular angefangen, ich habe Variabeln für alle wichtigen Dinge erstellt, nämlich diewchtigen Daten, des Senders (Email und co.) sowie von mir als Empfänger als auch bezüglich der Weiterleitung und für Elemente die nicht in der email vorhanden sein sollen. Als nächstes muss ich noch weitere Variabeln definieren.

## Donnerstag, der 06.02.2020

Am Donnestag habe ich mit dem Kontaktformular weitergemacht, dabei habe ich um die Variabeln gekümmert, welche zu der Erstellung des exakten Absendedatums nötig sind, wie die Bestimmung des Wochentages sowie die Zahl des Tages, die Woche und das Jahr des Absendens und eine zur Zusammenfassung aller dieser Variabeln. Nächste Woche möchte ich mit der Kontaktformular fertig werden.

# 7.Woche 10.02.2020-16.02.2020

## Mittwoch, der 12.02.2020

Am Mittwoch habe ich weiter an dem Kontaktformular gearbeitet, ich einmal if Anweisung und die foreach Anweisung verwendet, ich habe mit foreach alle Variabeln bezüglich der email ausgewählt und dann mit der if Anweisung die Variabeln nicht sichtbar gemacht, welche für mich als Empfänger nicht so wichtig zu sehen sind. Danach habe ich noch den die im Fomular einzugebende email als Absender email definiert. nächste Stunde will das Kontaktformular beenden.

## Donnerstag, der 13.02.2020

Heute habe ich das Kontaktformular beenden können, dabei habe ich den Betreff der Mail als Überschrift der Mail mit einer if Anweisung definiert. Ebenfalls habe ich beide Möglichkeiten der Weiterleitung geregelt, wenn die Mail versandt wurde wird man wieder auf die Seite zurückgeleitet, wenn das nicht Fall wird man auf einer anderen seite davon in Kenntnis gesetzt.

# 8.Woche 17.02.2020-23.02.2020

## Mittwoch, der 19.02.2020

Am Mitwoch habe ich mir Gedanken darüber gemacht, was noch zu erledigen ist. Dabei fiel mir auf, dass ich noch die Projektseite machen muss, noch Text auf der Startseite meiner Website hinzufügen muss und noch mein Php Dokument sowie die Accountseite dazu noch bauen muss und mit css gestalten muss.  

## Donnerstag, der 20.02.2020

Heute habe ich den noch fehlenden Text auf meiner Website hinzugefügt. Als nächtes will ich mit der Accountseite anfangen.

# 9.Woche 02.03.2020-08.03.2020

## Mittwoch, der 04.03.2020

Am Mitwoch habe ich das Design meiner Accountseite geplant und überlegt, was man noch für tools einbauen könnte. 

## Donnerstag, der 05.03.2020

Heute habe ich mit meiner Account seite angefangen, ich erst einmal das Layout meiner Log in Seite genommen und es auf mehrere Arten verändert, indem ich die Side bar farblich verändert habe. Ebenfalls habe ich die Navigation um die Accountseite erweitert und eine Anrede für den Benutzer formuliert und ihm noch eine Anleitung für die Benutzung meiner noch in Planung seienden Datenbank gegeben. 

## Freitag, der 06.03.2020

Am Freitag habe ich mit der Account seite weitergemacht ich habe sie zu meiner Accountdatenbank verbunden um auf die Daten zu greifen zu können, mit der $con Variabel und den Zugangsdaten als einzelne Variabeln definiert. In Html habe ich eine Tabelle erstellt in der dann später die Fotos sowie die wichtigsten Informationen gespeichert werden. 

# 10.Woche 09.03.2020-15.03.2020

## Donnerstag, der 12.03.2020

Heute habe ich eine Datenbank das als Kernstück dienen soll erstellt ich habe die Spalten "uploaded_at", "link", "Watched". Diese habe ich wie die andere Datenbank durch die $con Variabel und den anderen Variabeln mit der Accountseite verbunden. Als nächstes will ich noch die Projektseite machen, damit man auch alles verstehen kann.

## Freitag, der 13.03.2020

Am Freitag habe ich mit der Projektseite angefangen, um nicht die Probleme vom letzten mal wieder zu haben ich habe Struktur vorbereitet und schon mal ein bisschen überlegt was ich schreiben könnte, welche Bilder ich verwenden könnte und wie ich mein Projekt bewerten würde. Aber ich muss auch noch ein paar Dinge an meiner Seite optimieren um möglich Probleme auszuschließen. 

