# Hip-Hop-2020
Netzwerkanalyse Hip-Hop-2020
CODEBUCH			
Wert	Defintion	Kommentar	Quelle
nodelist		Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.	
id	Erste drei Buchstaben	eindeutige Identifikation jedes einzelnen Künstlers/Labels (vertex), der erfasst wird.  	
name	Name	Name des Künstlers/Labels	
sex	1=male oder 2=female 3=kein Geschlecht	dichotome Ausprägung	
type	1=Künstler 2=Tochterlabel 3=Mutterlabel 4=Majorlabel	Unterscheidung zwischen Akteur/Künstler und unterschiedlichen Labelformen	
highest rank	Platzierung	der höchste Rang des Künstlers/Label in der Chartliste Top 100 MTV Jahrescharts 2020	http://www.mtv.de/charts/lod2k0/top-100-jahrescharts-2020
charts	totale Anzahl	Anzahl der Charts in den Top 100 MTV Jahrescharts 2020	http://www.mtv.de/charts/lod2k0/top-100-jahrescharts-2020
personal rank	Platzierung	Persönliche Reihenfolge der Hip-Hop-Künstler nach 1. Platzierung in den Top 100, 2. Anzahl der Charts in den Top 100, 3. Anzahl der Auszeichnungen	
award gold	totale Anzahl	Anzahl der Gold Auszeichnungen für den Künstler oder das Label im Jahr 2020	https://www.musikindustrie.de/markt-bestseller/gold-/platin-und-diamond-auszeichnung/datenbank////#topSearch
award platin	totale Anzahl	Anzahl der Platin Auszeichnungen für den Künstler oder das Label im Jahr 2020	https://www.musikindustrie.de/markt-bestseller/gold-/platin-und-diamond-auszeichnung/datenbank////#topSearch
award diamond	totale Anzahl	Anzahl der Diamond Auszeichnungen für den Künstler oder das Label im Jahr 2020	https://www.musikindustrie.de/markt-bestseller/gold-/platin-und-diamond-auszeichnung/datenbank////#topSearch
fans	1=0 bis 100.000 2=100.001 bis 500.000 3=500.001 bis 1.000.000 4= 1.000.001 bis 2.000.000 5= alles höher als 2.000.000	definiert die Anzahl der Follower des Künstlers/Labels auf Instagram (gemessen im Februar 2021)	https://www.instagram.com/
edgelist		Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).	
from	ID des Senders	definiert den Sender in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen.	
to 	ID des Empfängers	definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen.	
relationship	1=gemeinsame Single von Künstlern 2=gemeinsames Album von Künstlern 3=Künstler & Tochterlabel 4=Künstler & Mutterlabel 5=Künstler & Majorlabel 6=Tochterlabel & Mutterlabel 7=Tochterlabel & Majorlabel 8=Mutterlabel & Majorlabel 	definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten 	
weight	1=einfach 2=mittel 3=stark	definiert die Qualität der Beziehung	
			
99	Variable: definiert fehlende Werte, ist n/a gleichgestellt		
			
Unsere Ausgangsposition:			
Wir analysieren die Kooperationen der deutschsprachigen Hip-Hop-Künstler und deren Labels, welche in den MTV Top 100 Jahrescharts 2020 vertreten sind. 			
Unsere Künstlerauswahl bezieht sich auf keine feste Hip-Hop-Chartliste, sondern beruft sich auf ein individuelles Sample. 			
Die unterschiedlichen Beziehungen zwischen den Künstlern sind gemeinsame Singles oder Alben.			
Wir arbeiten darüber hinaus die Beziehungen der Künstler und Labels, bei denen sie unter Vertrag stehen, heraus.			
Zudem stellen wir die Labelstruktur der deutschen Hip-Hop-Landschaft dar, indem wir diese in eineinander zugehörige Tochter-, Mutter- und Majorlabel unterteilen.			
			
Die Daten werden aus unterschiedlichen Datenbanken erhoben, wie MTV Top 100 Jahrescharts 2020, Spotify, Instagram, Websiten der Labels, Wikipedia, etc.			
Als Verbindungen zwischen den Künstlern haben wir die Songs aus den MTV Top 100 Jahrescharts 2020, auf die sich unser Sample beruft, sowie alle Songs und Alben, bei denen unsere gesampelten Künstler im Jahr 2020 kooperiert haben, erstellt. 			
