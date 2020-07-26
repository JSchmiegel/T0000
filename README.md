# Repository T0000: <br> LaTeX Vorlage für T-Arbeiten an der DHBW Campus Horb

## Description:
Diese Repository stellt LaTeX-Vorlage für die T-Arbeiten an der DHBW Campus Horb.

Zur Bearbeitung empfehle ich folgende Werkzeuge:
+ **LaTeX-Installation:** [miktex.org](https://miktex.org/download)
+ **LaTeX-Editor:** [xm1math.net/texmaker](https://www.xm1math.net/texmaker/download.html)
+ **Citavi:** [Citavi.com](https://www.citavi.com/de/download)

## Ordnerstruktur:
+ **./Abbildungen/*:** Ordner in dem alle Abbildungen abgespeicher werden können.
+ **./CitaviT0000Logging/*:** Citavi Beispielprojekt für die T0000
+ **./Kapitel/*:** Übersicht der Unterkapitel der T0000

## Besondere Befehle:
+ **\nameref{\<linkname>}:** Verlinkung auf ein Kapitel, welches mit Hilfe von \label{\<linkname>} mit einem Link versehen wurde
+ **\begin{anhang} \caption{} ... \end{anhang}:** Einfügen eines Anhangs, der im Anhangsverzeichnis aufgeführt wird

## Sperrvermerk einfügen
Um den Sperrvermerk einzufügen muss folgende Zeile auskommentiert werden in dem % entfernt wird.
>%\include{Kapitel/000Sperrvermerk}
