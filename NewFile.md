# Speedwar

Speedwar ist eine Modifikation für das Spiel "Die Siedler - Das Erbe der Könige Legenden", die das Spiel im Multiplayer 
beschleunigen und von Dorfzentren loslösen soll. Dies wird dadurch erreicht, dass Technologien durch **Ränge** 
begrenzt sind, welche wiederum **erkämpft** werden. Weiterhin wurden große Veränderungen an den Einheiten und Gebäuden vorgenommen, 
um ein schnelleres Spiel zu ermöglichen. Im Folgenden seht ihr alle Änderungen.

## Außenposten
Siedler ohne Dorfzentren? Ja! Ihr könnt Außenposten bauen, die zwar mit steigender Anzahl sehr viel teurer werden, welche 
aber sowohl 100 Bevölkerungsplätze als auch die Rekrutierung von Leibeigenen ermöglichen. Hier seht ihr die Kosten der ersten 6 Außenposten:

|Gebaute Aussenposten| 0 | 1 | 2 | 3 | 4 | 5 |
|Taler| 0 | 350 | 900 | 2350 | 5950 | 13450 |
|Holz| 0 | 250 | 700 | 1900 | 4750 | 10750 |
|Stein| 0 | 450 | 1250 | 3300 | 8350 | 18850 |

### Das ist viel. Können die nicht einfach zerstört werden?
Und genau deswegen besitzen Außenposten eine besondere Fähigkeit: Wird der Außenposten beschädigt, so schicken andere Gebäude Lebenspunkte 
an den beschädigten Außenposten, um ihn zu heilen. Dies funktioniert jedoch nur, solange die Umgebungsgebäude bei mehr als 60% ihrer maximalen HP liegen. 
Auch ist die Umwandlung etwas ineffizient, 25 Lebenspunkte werden zu einem Lebenspunkt des Außenpostens umgewandelt.

## Ränge
Durch Teilnahme an einer Schlacht könnt ihr Punkte sammeln, die in einem höheren Rang münden können. Infolge eines höheren Rangs erhaltet 
ihr Zugriff auf neue Gebäude, Einheiten und Technologien. Falls ihr mit einfachsten Bogenschützen, Speerträgern und Schwertkämpfern nicht zufrieden seid, 
werdet ihr wohl einen anderen Spieler bekämpfen müssen. Den aktuellen Rang und die zugehörige Punktzahl seht ihr im neuen Fenster im Außenposten, 
auch oben links seht ihr, wie weit ihr und eure Verbündeten auf der Jagd nach dem nächsten Rang schon sind.

Es gibt vier Ränge:
1. Siedler
2. Krieger
3. Feldherr
4. Eroberer

Hier eine Übersicht, welche Technologien sich hinter den jeweiligen Rängen verbergen:
### Siedler
Ausbildung von Speerträgern, Schwertkämpfern und Bogenschützen. Ausbau zu mittleren Wohnhäusern und Mühlen möglich.
### Krieger
Ihr könnt nun Lvl2-Einheiten erforschen, Leichte Kavallerie und Kirchen können gebaut werden. Außerdem habt ihr jetzt die Möglichkeit, das Wetter 
zu verändern und Kanonen zu bauen.
### Feldherr
Zugriff auf Lvl3-Einheiten, leichte Scharfschützen und schwere Kavallerie. Ihr könnt nun eine Kathedrale, Märkte und Balistatürme bauen lassen.
Alle Hauptspielveredeler lassen sich nun auf die höchste Stufe ausbauen.
### Eroberer:
Alles, was euch aus dem Spiel bekannt ist, ist möglich.

Damit haben wir das Wichtigste eigentlich schon zusammen, aber wir noch viele kleine Änderungen vorgenommen.
## Leichte Kavallerie
Im Original ist Leichte Kavallerie praktisch unbrauchbar, wir wollten sie zurückbringen. Deswegen ist Leichte Kavallerie hier 
deutlich schneller als im Hauptspiel, verbraucht nur einen Platz im Dorfzentrum, macht mit dem ersten Angriff Bonusschaden und erhält Gold für jeden 
getöteten Gegner. Wieviel Gold euch eure Leichte Kavallerie eingebracht hat, könnt ihr in der Burg im neuen Menü nachvollziehen.

## Einheitengeschwindigkeit
Im Original sind die Einheiten doch etwas langsam, deshalb haben wir viele Einheiten etwas beschleunigt:
```
Einheit: Geschwindigkeit Original -> speedwar ohne Techs -> speedwar mit Techs
Schwertkämpfer: 360 -> 400 -> 750
Speerträger: 360 -> 480 -> 850
Bogenschützen: 320 -> 400 -> 750
Scharfschützen: 320 -> 400 -> 750
Leichte Kavallerie: 480 -> 900 -> 1250
Schwere Kavallerie: 440 -> 700 -> 1000
Kanonen: 260, 240, 220, 180 -> 300 -> 450
Arbeiter: 320 -> 550
Leibeigene/Diebe: 400 -> 550
Kudschafter: 350 -> 550
```

## Türme
Türme - in praktisch jedem Spiel verboten oder stark limitiert. Deshalb haben wir ein paar Änderungen vorgenommen: Zunächst wurden sowohl Kosten als auch 
Sichtweite von allen drei Türmen massiv erhöht. Ein einfacher Aussichtsturm ist jetzt sinnvoll!
Die bewaffneten Türme kommen aber deutlich später ins Spiel: Ballistatürme brauchen den Rang Feldherr, Kanonentürme sogar Eroberer.
Aussichtstürme halten praktisch nichts aus, ein Kanonenturm ist aber stabiler als die meisten Zivilgebäude.

## Neue Befestigungsanlagen
Wie Ihr sicher schon bemerkt habt, sind die Speedwar-Maps offener als die üblichen Multiplayermaps. Damit Ihr euch gegen die schnelleren Einheiten 
besser verteidigen könnt, haben wir neue Befestigungsanlagen eingebaut:
Mauern und Standhafte Türme!

Mauern könnt ihr errichten, sobald ihr Konstruktion erforscht habt. Das Tor und die normale Mauer verhalten sich wie Anarkis Mauern:
Eine fertiggestellte Mauer versucht, sich an eine bestehende Mauer anzuschließen. 
Die Abschlussmauer hat zwei Verwendungszwecke: Eine Abschlussmauer versucht zuerst, eine Lücke in der Mauer zu schließen. Falls keine Lücke 
gefunden wird, setzt die Abschlussmauer eine existierende Mauer in die gleiche Richtung fort. So könnt ihr sehr geradlinige Mauern bauen.

Den Standhaften Turm könnt ihr erst auf dem Rang Krieger verwenden, gibt euch aber die Möglichkeit, Truppen einzulagern. Wenn ihr eurer Armee 
den Auftrag gebt, den Turm zu bewachen, so werden sich einige Soldaten im Turm niederlassen. Sie brauchen in dieser Phase keinen Platz im 
Dorfzentrum und können bei Bedarf - und ausreichendem Bevölkerungslimit - den Turm verlassen. Sollte der Turm zerstört werden, so gehen alle 
stationierten Soldaten verloren. Stationierte Soldaten werden auch nicht aufgewertet, wenn ihr die nächste Stufe erforscht.

## Sieg und Niederlage
Im Gegensatz zum Hauptspiel hängen Sieg und Niederlage nicht von einem einzigen Gebäude ab. Endgültig verloren habt ihr erst, wenn jeder Leibeigene, 
jede Milize, jeder Hauptmann und jeder Außenposten besiegt ist - oder wenn ihr nach Ablauf der Spielzeit nicht das größte Gebiet kontrolliert.
Und damit sind wir bei der Siegbedingung:
Das Team, welches nach Ablauf der Zeit - momentan 90 Minuten - das größte Gebiet besitzt, gewinnt und das Spiel wird beendet. Dazu wird die Map 
in Zellen aufgeteilt, die ungefähr so groß wie 4 Kasernen sind. Ein Team kontrolliert eine Zelle, falls es mehr Hauptmänner und fertige Gebäude 
in dieser Zelle hat als alle anderen Teams. Die Anzahl der momentan kontrollierten Zellen ist in jedem Außenposten im neuen Menü einsehbar und 
wird als Zahl links der Spielernamen angezeigt.

Solltet Euer Team aus dem Spiel ausscheiden, bleiben eure Gebäude aber noch bestehen und die Karte wird für Euch aufgedeckt.

## Änderungen an Veredelern
Damit Ihr auch an die Ressourcen für ein mächtiges Militär kommt, haben wir die Arbeit der Veredeler und Bergarbeiter etwas beschleunigt.
Die Bergarbeiter holen pro Arbeitsschritt 16/20/24 Ressourcen aus ihrer Mine, je nach Ausbaustufe. Für die Veredeler lauten die Werte:
```
Schmiede: 6 / 9 / 12
Ziegelhütte: 6 / 12
Sägewerk: 8 / 16
Alchemistenhütte: 8 / 12
Bank: 4 / 6
Steinmetze: 6 / 9
```

## Kleine Änderungen
- Leibeigene kosten 15 Holz.
- Es gibt einige neue Wetterlagen wie z.B. Sturm, Schneeregen oder "saurer" Regen
- Das Zerstören von Gebäuden gibt Euch Ressourcen, momentan 75% der Baukosten.
- Die Startpositionen sind zufällig, werden aber auf der Minimap markiert.
- Die Preisverhältnisse im Marktplatz sind konstant.
- Wenn ihr Soldaten nachkauft und [Strg] gedrückt haltet, wird versucht, alle Truppen in der Selektion aufzufüllen.
- Wenn ihr Einheiten entlasst und [Strg] gedrückt haltet, wird die komplette Selektion entlassen.
- Sollte ein Spieler das Spiel verlassen, wird der Name des aktuellen Hosts ausgegeben.


### Liste von erwähnten Änderungen
- Außenposten mit steigenden Kosten, Tankiness, DZPlatz
- TechTree
- LKav-Änderung
- ProgressWindow
- Movementspeedrebalance
- Veränderte Einheiten- und Gebäudekosten
- Türme: Sichtweite, TechTree, Pappe
- Standhafte Ficker
- Mauerbau
- WinCondition
- DefeatCondition
- RefineryPush
- RandomWeather
- Plünderskript
- RandomStart
- TradeFix
- QualityOfLife-Changes