# Repository T0000: <br> LaTeX Vorlage für T-Arbeiten an der DHBW Campus Horb

## Description:
Dieses Repository stellt eine LaTeX-Vorlage für die T-Arbeiten an der DHBW Campus Horb dar.

Zur Bearbeitung empfehle ich folgende Werkzeuge:
+ **LaTeX-Installation:** [miktex.org](https://miktex.org/download)
+ **LaTeX-Editor:** [xm1math.net/texmaker](https://www.xm1math.net/texmaker/download.html)
+ **JabRef:** [jabref.org](https://www.jabref.org/#download)

## Dateistruktur:
+ **./main.tex:** Hauptdokument
+ **./Abbildungen/*:** Ordner in dem alle Abbildungen abgespeichert werden können
+ **./Anhang/*:** Ordner in dem alle Anhänge abgespeichert werden können
+ **./Backstage/*:** This is called a 'neuralyzer'. A gift from some friends from out of town. The red eye here isolates ...
+ **./Kapitel/*:** Übersicht der Unterkapitel der T0000
+ **./compile.ps1:** Powershell-Script zur manuellen Kompilierung 

## Einstellungen:
Um wiederauftretende Konstanten, wie Autor, Titel, Matrikelnummer, etc. einzustellen bitte einfach die jeweilige Angabe in **./settings.tex** anpassen.

## Besondere Befehle:
+ **\chapterref{\<linkname>}:** Verlinkung auf ein Kapitel, welches mit Hilfe von \label{\<linkname>} mit einem Link versehen wurde
+ **\begin{anhang} \caption{} ... \end{anhang}:** Einfügen eines Anhangs, der im Anhangsverzeichnis aufgeführt wird (siehe **./Kapitel/001BeispielKapitel**)
+ **\begin{kischt}{\<title>} ... \end{kischt}:** Einfügen einer blau umrandeten Box für z.B. Theoreme, Hypothesen, Hinweise, etc. (siehe **./Kapitel/001BeispielKapitel**)

## Sperrvermerk einfügen
Um den Sperrvermerk einzufügen muss der Kommentar in der folgenden Zeile (durch das Entfernen des %) aufgehoben werden.
>%\include{Kapitel/000Sperrvermerk}

## Kompilieren
Falls nicht die Kompilier-Funktion vom Texmaker genutzt werden soll, sondern per Console kompiliert werden soll kann das Script **./compile.ps1** mit dem Befehl
>powershell .\compile.ps1

aufgerufen werden