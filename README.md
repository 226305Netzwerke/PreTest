# PreTest
Pretest zum Netzwerk von Charles Manson

Datenstand: 07. Januar 2020


 						
Im Codebuch definieren Sie, wie und nach welchen Kriterien erfasst werden.						
						
Wert	Kommentar					
edgelist	Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).					
from	definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort					
to 	definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. 					
weight	Ausprägung der Kantenstärke (Beziehungsstärke), definiert nach vorgegeben Skalen. Skala 1-3					 
relationship	"definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten. Wenn zwei Arten der Beziehung bestehen werden auch zwei Einträge gemacht.
1 = Bekanntschaft, 2 = Freundschaft, 3 = Abneigung, 4 = Familie, 5 = Liebe/Ehe, 6 = A hat B ermordet"					
year beginning	Jahr der Bekanntschaft (bzw. Art der relationship) um nach vor/nach Haft filtern zu können					
year end	Jahr ENDE der Bekanntschaft (bzw. Art der relationship) um nach vor/nach Haft filtern zu können und Dauer zu bestimmen					
						
nodelist (Menschen)	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.					
id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  					
name	Name oder Bezeichnung des Knotens. 					
sex	dichotome Ausprägung: male oder female. Einfacher auch numerisch als 1 oder 2 zu kodieren.					
date of birth	DD-MM-YYYY					
date of death	DD-MM-YYYY					
type of death	1 = lebend, 2 = natürlicher Tod , 3 = ermordet, 4 = Selbstmord					
power	definiert als Macht des Akteurs (1 = sehr gering, 5 = sehr hoch)					
relation to murder	1 = hat niemanden getötet, 2 = war bei Mord anwesend, 3 = hat jemanden getötet					
						
						
nodelist (Orte)	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.					
id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  					
name	Name oder Bezeichnung des Knotens. 					
						
						
nodelist (Gruppierungen)	Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.					
id	eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  					
name	Name oder Bezeichnung des Knotens. 					
						
						
						
						
99	definiert fehlende Werte					
						
						
						
Bearbeitungshinweise						
Achten Sie bitte auf die Kommentare in den Spalten. Diese erklären genauer, welche Daten erfasst werden. 						
Sie sehen die Kommentare, wenn Sie auf die entsprechende Spalte gehen. 						
Skizzieren Sie zunächst Ihr Netzwerk bzw. die Daten, die für Sie relevant sind. 						
Welche Informationen wollen Sie erheben? Wie müssen diese erfasst sein?						
Legen Sie bitte im Codebuch möglichst genau fest, wie die Daten erhoben werden (Codebuch)						
Bitte verwenden Sie keine Sonderzeichen in der Erfassung, dazu gehören Satzzeichen, Umlaute, etc.						
Verpflichten Sie alle Teammitglieder darauf, das Codebuch zwingend einzuhalten. 						
Wer seine Daten nicht sauber erstellt muss diese nachbereinigen.						
Dokumentieren Sie jeden Schritt Ihrer Datenerfassung mit, um dies zu rekonstruieren.						
Nutzen Sie das Skript zur Datenbereinigung auf dem letzten Reiter!						
