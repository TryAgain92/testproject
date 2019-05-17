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
<table>
  <tr><td>Index</td><td>0</td><td>1</td><td>2</td><td>3</td><td>4</td><td>5</td><td>6</td><td>7</td><td>8</td><td>9</td><td>10</td><td>11</td><td>12</td><td>13</td><td>14</td><td>15</td><td>16</td><td>17</td><td>18</td><td>19</td><td>20</td><td>21</td><td>22</td><td>23</td></tr>
  <tr><td>Alle Töne</td><td>C</td><td>C#</td><td>D</td><td>D#</td><td>E</td><td>F</td><td>F#</td><td>G</td><td>G#</td><td>A</td><td>A#</td><td>H</td><td>C</td><td>C#</td><td>D</td><td>D#</td><td>E</td><td>F</td><td>F#</td><td>G</td><td>G#</td><td>A</td><td>A#</td><td>H</td>
  </tr>
  <tr><td>Töne der Tonleiter</td><td></td><td></td><td>D</td><td></td><td>E</td><td></td><td>F#</td><td>G</td><td></td><td>A</td><td></td><td>H</td><td></td><td>C#</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
  <tr><td>Rechnung</td><td></td><td></td><td>2+0</td><td></td><td>2+2</td><td></td><td>2+4</td><td>2+5</td><td></td><td>2+7</td><td></td><td>2+9</td><td></td><td>2+11</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
</table>

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
