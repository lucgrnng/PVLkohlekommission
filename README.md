# PVLkohlekommission
# Prüfungsvorleistung, Modul 226503 
## EDGE-Attribute
**id**

(eindeutige Codierung des Knoten)
codiert als Abkürzung der Namen mit drei oder vier Buchstaben zur Identifikation der Mitglieder der Kohlekommission. 

**To**  
- Politik (Poli),
- Verein (Vere),
Verband (Verb),
Gewerkschaft (Gewe),
Umweltschutz (Umwe),
Energieunternehmen (Ener),
Industrie (Indu),
Wissenschaft (Wiss),
Regionalvertreter (Regi),
CDU,
CSU,
SPD,
GRU,
FDP,

**weight**
Intensität der Beziehung; bzw. Einfluss 
1 = ohne Stimmrecht / Parteimitglied / ehemaliges Mandat 
2 = Stimmrecht / aktives Mandat
3 = aktives Mandat / Ministeramt 

## NODE-Attribute
**id** 
Identische ID wie aus der edgelist zur Identifikation der Knoten. In diesem Fall sind alle Namen abgekürzt mit drei oder vier Buchstaben zu sehen.
**name**
Die Namen der Mitglieder der Kohlekommission. 
sex
Bitte geben Sie ihr Geschlecht an:
1 = weiblich
2 = männlich
3 = divers
type
Haben wir es mit einer Person oder einer Organisation zu tun?
0 = Person
1 = Organisation
party
Zu welcher politischen Partei gehört die Person?
1=CDU
2=CSU
3=SPD
4=Gruene
5=FDP
age
Gibt das Alter an:
1 = bis 39 Jahre
2 = 40 bis 49 Jahre
3 = 50 bis 59 Jahre
4 = 60 und älter
representation
bezieht sich auf die Funktion innerhalb der Kommission: 
A = Politik 
B= Wirtschaft 
C= Gewerkschaft
D= Umwelt
E= Regionen
F= Wissenschaft

Position
Bezieht sich auf den Einfluss in der Kommission 
1= kein Stimmrecht
2= Mitglied
3= Vorsitz

State
Bezieht sich auf das Herkunfts-Bundesland der Kommissionsmitglieder 
BB= Brandenburg
BW= Baden-Württemberg
BA= Bayern
BE= Berlin
HB= Bremen
HH= Hamburg
HE= Hessen
MV= Mecklenburg-Vorpommern
NI= Niedersachsen
NW= Nordrhein-Westfalen
RP= Rheinland-Pfalz
SL= Saarland
SN= Sachsen
ST= Sachsen-Anhalt
SH= Schleswig-Holstein
TH= Thüringen
