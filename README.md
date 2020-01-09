# PreTest
Pretest zum Netzwerk von Charles Manson

Datenstand: 07. Januar 2020


 						
Codebuch definieren Sie, wie und nach welchen Kriterien erfasst werden.						
						
					
edgelist	
Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).					
from	
definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort					
to 	
definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 					
weight	
Ausprägung der Kantenstärke (Beziehungsstärke), definiert nach vorgegeben Skalen. Skala 1-3	

relationship	
definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten. Wenn zwei Arten der Beziehung bestehen werden auch zwei Einträge gemacht.

1 = Bekanntschaft 
2 = Freundschaft
3 = Abneigung
4 = Familie
5 = Liebe/Ehe
6 = A hat B ermordet"	

year beginning	
Jahr der Bekanntschaft (bzw. Art der relationship) um nach vor/nach Haft filtern zu können	

year end	
Jahr ENDE der Bekanntschaft (bzw. Art der relationship) um nach vor/nach Haft filtern zu können und Dauer zu bestimmen					
						
nodelist (Menschen)	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.					

id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  					

name	Name oder Bezeichnung des Knotens. 					

sex	dichotome Ausprägung: male oder female. Einfacher auch numerisch als 1 oder 2 zu kodieren.					

date of birth	DD-MM-YYYY					

date of death	DD-MM-YYYY					

type of death	
	1 = lebend
	2 = natürlicher Tod
	3 = ermordet
	4 = Selbstmord					

power	definiert als Macht des Akteurs 
	1 = sehr gering
	2 = gering
	3 = normal
	4 = hoch
	5 = sehr hoch				

relation to murder	
	1 = hat niemanden getötet
	2 = war bei Mord anwesend
	3 = hat jemanden getötet					
						
						
nodelist (Orte)	
Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.	

id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  					
name	Name oder Bezeichnung des Knotens. 					
						
						
nodelist (Gruppierungen)	
Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.					

id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  					
name	Name oder Bezeichnung des Knotens. 					
						
						
						
Sonstiges						
99	definiert fehlende Werte					
