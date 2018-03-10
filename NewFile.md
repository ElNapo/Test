## Speedwar

Die Siedler Speedwar ist eine Multiplayer Modifikation mit dem Ziel schneller einen Kampf zwischen den einzelnen Spielern
zu erzeugen. Erzwungen wird dies dadurch, dass der **Siedlungsfortschritt durch Ränge** beschränkt ist, die man sich durch **Kämpfen**
freischalten muss. Desweiteren wurden etliche Anpassungen am Balancing vorgenommen, die den Siedlungsaufbau beschleunigen.
Damit ihr nicht böse überrascht werdet, erkläre ich im Folgenden alle Änderungen.

Es gibt vier Ränge:
1. Siedler
2. Krieger
3. Feldherr
4. Eroberer

Um das ganze Spiel dynamischer zu gestalten, haben wir die Existenz der Siedlung von der Burg und den Dorfzentren losgelöst.
Eine zerstörte Burg bedeutet nichtmehr dass ihr das Spiel verloren habt und Dorfzentren geben nicht mehr das Bevölkerungslimit vor.
Stattdessen könnt ihr euch jetzt selbst eure Burgen bauen, genannt Außenposten. Diese geben euch jeweils **100 Dorfzentrumsplätze**.
Der erste Außenposten ist gratis, die Kosten steigen mit der Anzahl der schon gebauten Außenposten. Hier die Kosten für die ersten 6 Außenposten:


|#Aussenposten| 1 | 2 | 3 | 4 | 5 | 6 |
|Taler| 0 | 350 | 900 | 2350 | 5950 | 13450 |
|Holz| 0 | 250 | 700 | 1900 | 4750 | 10750 |
|Stein| 0 | 450 | 1250 | 3300 | 8350 | 18850 |

### Liste von zu erwähnenden Änderungen
- DefeatCondition
- TechTree
- RandomWeather
- Türme: Sichtweite, TechTree, Pappe
- Movementspeedrebalance
- Außenposten mit steigenden Kosten, Tankiness, DZPlatz
- Veränderte Einheiten- und Gebäudekosten
- Plünderskript
- Standhafte Ficker
- LKav-Änderung
- Mauerbau
- QualityOfLife-Changes
- RandomStart
- RefineryPush
- ProgressWindow
- TradeFix
- WinCondition

Ein Spieler hat verloren, wenn alle Leibeigenen, Hauptmänner und Außenposten zerstört wurden. Sollte ein Spieler verlieren oder die 
Verbindung verlieren, bleibt seine Siedlung aber bestehen.

Es gab massive Veränderungen bei Einheiten- und Gebäudekosten. Der TechTree wurde stark verändert und häufig braucht ihr für gewisse Technologien oder 
Einheiten einen Mindestrang. Die Ränge ermöglichen euch(nachdem eventuell andere Bedingungen erfüllt wurden):

Rang Siedler:
	Ausbildung von Speerträgern, Schwertkämpfern und Bogenschützen. Ausbau zu mittleren Wohnhäusern und Mühlen möglich.
Rang Krieger:
	Ihr könnt nun Lvl2-Einheiten erforschen, Leichte Kavallerie und Kirchen können gebaut werden. Außerdem habt ihr jetzt die Möglichkeit, das Wetter 
	zu verändern und Kanonen zu bauen.
Rang Feldherr:
	Zugriff auf Lvl3-Einheiten, leichte Scharfschützen und schwere Kavallerie. Ihr könnt nun eine Kathedrale, Märkte und Balistatürme bauen lassen.
	Alle Hauptspielveredeler lassen sich nun auf die höchste Stufe ausbauen.
Rang Eroberer:
	Keinerlei Einschränkungen.

Änderungen an Einheiten und Gebäuden:
	Aussichtstürme und die bewaffneten Türme besitzen nun einen sehr großen Sichtradius.
	Leichte Kavallerie macht mit ihrem ersten Angriff gegen Einheiten massiven Bonusschaden, weil sie einen magischen Pfeil vorbereitet haben.
	Leichte Kavallerie beschaffen euch Gold für jede Einheit, die von ihnen getötet wird. Die Menge des geplünderten Goldes ist in jedem Außenposten einsehbar.
	Leibeigene kosten 15 Holz.
	Veredeler und Minen sind deutlich effektiver. Der Ausbau von Veredelern erhöht auch die Menge, die pro Veredelungstick produziert wird.
	Außenposten heilen sich auf Kosten der sich in der Nähe befindlichen Gebäude. 
		Die effektiven HP eines Außenposten liegen bei 1000 + GesamtHP aller umliegenden Gebäude/25.

Neuerungen:
	Ihr könnt Mauern ähnlich wie bei Anarkis Mauerbau bauen!
	Mit [Strg]+Klick auf den Soldatennachkaufbutton könnt ihr alle Truppen in der Selektion auffüllen.
	Überall auf der Map sind Kisten verteilt, die von Leibeigenen oder Hauptmännern geöffnet werden können.
