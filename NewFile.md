# Speedwar

Speedwar ist eine Modifikation für das Spiel "Die Siedler - Das Erbe der Könige Legenden", die das Spiel im Multiplayer 
beschleunigen und von Dorfzentren loslösen soll. Dies wird dadurch erreicht, dass Technologien durch **Ränge** 
begrenzt sind, welche wiederum **erkämpft** werden. Weiterhin wurden große Veränderungen an den Einheiten und Gebäuden vorgenommen, 
um ein schnelleres Spiel zu ermöglichen. Im Folgenden seht ihr alle Änderungen.

## Außenposten
Siedler ohne Dorfzentren? Ja! Ihr könnt Außenposten bauen, die zwar mit steigender Anzahl sehr viel teurer werden, welche 
aber sowohl 100 Bevölkerungsplätze als auch die Rekrutierung von Leibeigenen ermöglichen. Hier seht ihr die Kosten der ersten 6 Außenposten:

|Gebaute Aussenposten| 1 | 2 | 3 | 4 | 5 | 6 |
|Taler| 0 | 350 | 900 | 2350 | 5950 | 13450 |
|Holz| 0 | 250 | 700 | 1900 | 4750 | 10750 |
|Stein| 0 | 450 | 1250 | 3300 | 8350 | 18850 |

### Das ist viel. Können die nicht einfach zerstört werden?
Und genau deswegen besitzen Außenposten eine besondere Fähigkeit: Wird der Außenposten beschädigt, so schicken andere Gebäude Lebenspunkte 
an den beschädigten Außenposten, um ihn zu heilen. Dies funktioniert jedoch nur, solange die Umgebungsgebäude bei mehr als 60% ihrer maximalen HP liegen. 
Auch ist die Umwandlung etwas ineffizient, 40 Lebenspunkte werden zu einem Lebenspunkt des Außenpostens umgewandelt.

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
Aussichtstürme halten praktisch nichts aus, ein Kanonenturm ist aber massiver als die meisten Zivilgebäude.


### Liste von erwähnten Änderungen
- Außenposten mit steigenden Kosten, Tankiness, DZPlatz
- TechTree
- LKav-Änderung
- ProgressWindow
- Movementspeedrebalance
- Veränderte Einheiten- und Gebäudekosten
- Türme: Sichtweite, TechTree, Pappe
### Liste von zu erwähnenden Änderungen
- DefeatCondition
- RandomWeather
- Plünderskript
- Standhafte Ficker
- Mauerbau
- QualityOfLife-Changes
- RandomStart
- RefineryPush
- TradeFix
- WinCondition

Ein Spieler hat verloren, wenn alle Leibeigenen, Hauptmänner und Außenposten zerstört wurden. Sollte ein Spieler verlieren oder die 
Verbindung verlieren, bleibt seine Siedlung aber bestehen.

Änderungen an Einheiten und Gebäuden:
	Aussichtstürme und die bewaffneten Türme besitzen nun einen sehr großen Sichtradius.
	Leibeigene kosten 15 Holz.
	Veredeler und Minen sind deutlich effektiver. Der Ausbau von Veredelern erhöht auch die Menge, die pro Veredelungstick produziert wird.
	Außenposten heilen sich auf Kosten der sich in der Nähe befindlichen Gebäude. 
		Die effektiven HP eines Außenposten liegen bei 1000 + GesamtHP aller umliegenden Gebäude/25.

Neuerungen:
	Ihr könnt Mauern ähnlich wie bei Anarkis Mauerbau bauen!
	Mit [Strg]+Klick auf den Soldatennachkaufbutton könnt ihr alle Truppen in der Selektion auffüllen.
	Überall auf der Map sind Kisten verteilt, die von Leibeigenen oder Hauptmännern geöffnet werden können.
