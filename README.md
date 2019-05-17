# Test_Project
In diesem kleinen Projekt geht es einfach mal darum zu gucken. Natürlich zählen ebenfalls Referenzen. Aber ich kann nicht beurteilen wie viel Stack Overflow ist, wie lange die Entwicklungsphase war, unter welchen Umständen programmiert wurde. Meine Anforderung an dich:
Du bekommst einen Auftrag von mir. Du erfüllst ihn. Manche Sachen werden dir naturgemäß einfacher fallen :)

# Ich SUCHE Hilfe
Das Projekt ist riesig. Daher suche ich Hilfe. Dieser kleine Test ist absolut kein Auschlusskriterium, sieh es als gegenseitiges Beschnuppern. Ich bereite ein Google Sheet vor und stelle mich und meine kleine Idee mal genauer vor. Nach dem kleinen Test bekommst du noch eine Entwicklungsumgebung für die fortlaufende Zusammenarbeit. 

# Der erste Auftrag
Ein Programm, welches die harmonische Dur-Tonleiter für jeden beliebigen Grundton ausgibt.

## Die Theorie
In der Musik gibt es 7 Grundtöne und 5 Halbtöne (weiße- und schwarze Klavier Tasten) - insgesamt also 12 Töne. Kommt man zum Ende der Skala, geht's wieder von vorne los. Wie bei einer Uhr. Das bedeutet: der 13-te Ton ist wieder der erste.

Folgende Töne werden beachtet:
<br/>C C# D D# E F F# G G# A A# H

Eine Tonart ist wie eine Richtlinie für Töne die Verwendet werden dürfen. In der Regel harmonieren die Töne einer bestimmten Tonart miteinander. In dem Beispiel wird die harmonische Dur-Tonleiter betrachtet.
Relativ zur Grundtonposition der Tonleiter, dürfen folgende Töne (additiv zum Grundton) betrachtet werden:
<br/>0 2 4 5 7 9 11

<p>Beispiel:
  <ul>
    <li>C-Dur:  C D E F G A H</li>
<li>G-Dur:  G A H C D E F#</li>
<li>E-Dur:  E F# G# A H C# D#</li>
    </ul>
</p>

Falls es hier noch nicht ganz klar ist, ein letztes Beispiel. Dazu schreibe ich die 12 Töne 2 Mal hintereinander. Darunter anschließend alle Treffer für die D-Dur Tonleiter.
<br>0   1   2   3   4   5   6   7   8   9   10  11  12  13  14  15  16  17  18  19  20  21  22  23
<br>C   C#  D   D#  E   F   F#  G   G#  A   A#  H   C   C#  D   D#  E   F   F#  G   G#  A   A#  H
<br>        D       E       F#  G       A       H       C#
<br>        2+0     2+2     2+4 2+5     2+7     2+9     2+11

## Das bekommst du
Für deine Funktion stehen dir zwei Listen zu Verfügung:
<br/>sounds = ['C', 'C#', 'D', 'D#', 'E', 'F', 'F#', 'G', 'G#', 'A', 'A#', 'H']
<br/>harmonic_dur_scale = [0,2,4,5,7,9,11]

## Das erwarte ich
1. Eine Funktion die eine Liste der Tonleiter ausgibt. Die Funktion bekommt von außen die verwendeten 12 Töne, die Tonleiter und den Grundton als Buchstaben.
2. Eine Textausgabe in folgender Form:
'Harmonische Dur-Tonleiter mit dem Grundton GRUNDTON beinhaltet folgende Töne: TON1, TON2, TON3, .... '

Um das nicht zu einfach zu machen: Es ist verboten die Liste der sounds zu verlängern wie ich es im Beispiel gemacht habe.

# Funfacts
Mit Ampermusic gibt es eine öffentlich zugängliche KI die komplette Kompositionen generiert. Folgender Song ist so entstanden:

https://www.youtube.com/watch?v=XUs6CznN8pw

einzig die menschliche Stimme und die Wörter sind menschlich. Alle Melodien (inklusive die der Stimme), sowie Instrumente kommen direkt vom PC.

... Musik ist reine Mathematik. Nur falls die Frage aufkommt, was dieser kleine Testauftrag eigentlich mit dem Projekt zu tun hat ;)
