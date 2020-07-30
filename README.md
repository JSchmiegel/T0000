# Repository T0000: <br> LaTeX Vorlage für T-Arbeiten an der DHBW Campus Horb

## Description:
Diese Repository stellt LaTeX-Vorlage für die T-Arbeiten an der DHBW Campus Horb.

Zur Bearbeitung empfehle ich folgende Werkzeuge:
+ **LaTeX-Installation:** [miktex.org](https://miktex.org/download)
+ **LaTeX-Editor:** [xm1math.net/texmaker](https://www.xm1math.net/texmaker/download.html)
+ **Citavi:** [Citavi.com](https://www.citavi.com/de/download)

## Dateistruktur:
+ **./main.tex:** Hauptdokument
+ **./Abbildungen/*:** Ordner in dem alle Abbildungen abgespeicher werden können.
+ **./CitaviT0000Logging/*:** Citavi Beispielprojekt für die T0000
+ **./Kapitel/*:** Übersicht der Unterkapitel der T0000
+ **./compile:** Powershell-Script zur manuellen Kompilierung 

## Besondere Befehle:
+ **\chapterref{\<linkname>}:** Verlinkung auf ein Kapitel, welches mit Hilfe von \label{\<linkname>} mit einem Link versehen wurde
+ **\begin{anhang} \caption{} ... \end{anhang}:** Einfügen eines Anhangs, der im Anhangsverzeichnis aufgeführt wird (siehe ./Kapitel/001BeispielKapitel)
+ **\begin{kischt}{\<title>} ... \end{kischt}:** Einfügen einer blau umrandeten Box für z.B. Theoreme, Hypothesen, Hinweise, etc. (siehe ./Kapitel/001BeispielKapitel)

## Sperrvermerk einfügen
Um den Sperrvermerk einzufügen muss folgende Zeile auskommentiert werden in dem % entfernt wird.
>%\include{Kapitel/000Sperrvermerk}

## Kompilieren
Falls nicht die Kompilier-Funktion vom Texmaker genutzt werden soll, sondern per Console kompiliert werden soll kann das Script **./compile.ps1** mit dem Befehl
>powershell .\compile.ps1
aufgerufen werden