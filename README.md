# coins
Das Münz-Nim-Spiel (verstärkendes Lernen)

# Das Münz-Spiel
- **Ein sehr einfaches Beispiel für verstärkendes Lernen**
- **Geeignet für den Informatikunterricht WP II, Unterrichtseinheit KI**
## Die Regeln
- Auf dem Tisch liegen einige Münzen. 
- Zwei Personen (hier Alice und eine KI, Bob genannt) spielen gegeneinander. 
- Sie nehmen abwechselnd eine oder zwei Münzen weg und legen sie beiseite. 
- Derjenige Spieler, der die letzte bzw. die letzten beiden Münzen wegnimmt, hat das Spiel verloren.

In der ersten Runde startet Alice. Ist das Spiel beendet, beginnt ein neues Spiel, in dem jetzt Bob beginnt. 

Viele solcher Runden werden gespielt, bis Bob *genug* gelernt hat.

Die Implementaion mit einem JNB zeigt, wie ein KI-System beim wiederholten Spielen lernt, welche Züge 

- zum sicheren Sieg führen oder 
- ob der optimal spielende Gegner sicher gewinnen wird. 
