# PVLkohlekommission
# Prüfungsvorleistung, Modul 226503 
Codebuch Stand 21-07-20,
erstellt von Luca Gröning lg058@hdm-stuttgart.de 

## EDGE-Attribute
**from**

Definiert den Sender im gerichteten Netzwerk. ID entspricht dem gleichen Wert in Nodelist 

**To**  
Definiert den Empfänger im gerichteten Netzwerk. ID entspricht dem gleichen Wert in Nodelist. 


## NODE-Attribute
**id** 

Identische ID wie aus der edgelist zur Identifikation der Knoten. In diesem Fall sind alle Namen abgekürzt mit drei oder vier Buchstaben zu sehen.

**sex**

(1= female, 2=male, 3=diverse) 

**type**

Haben wir es mit einer Person oder einer Organisation zu tun?
0 = Person
1 = Organisation

**party**

Zu welcher politischen Partei gehört die Person?
1 = CDU
2 = CSU
3 = SPD
4 = Gruene
5 = FDP

**age**

Gibt das Alter an:
1 = bis 39 Jahre
2 = 40 bis 49 Jahre
3 = 50 bis 59 Jahre
4 = 60 und älter

**representation**

bezieht sich auf die Funktion innerhalb der Kommission: 

(1=Politik, 2=Wirtschaft, 3=Gewerkschaft, 4=Umwelt, 5=Regionen, 6=Wissenschaft)

**Position**

Bezieht sich auf den Einfluss in der Kommission 

1 = kein Stimmrecht
2 = Mitglied
3 = Vorsitz

**State**

Bezieht sich auf das Herkunfts-Bundesland der Kommissionsmitglieder 

1= Baden-Württemberg, 2=Brandenburg, 3=Bayern, 4= Berlin, 5= Bremen, 6= Hamburg, 7= Hessen, 8= Mecklenburg Vorpommern, 9= Niedersachsen, 10= Nordrhein-Westfalen, 11= Rheinland-Pfalz, 12= Saarland, 13= Sachsen, 14= Sachsen-Anhalt, 15= Schleswig-Holstein, 16= Thüringen
