# Codebuch Testat VfB
# Inhalt
1.EdgesVfB.csv (Edgelist)

2.NodesVfB.csv (Nodelist)

3.Codebuch.md (Codierung der Datensätze)
# Ursprung und Datenerhebung
Das Netzwerk wurde anhand folgender Daten erstellt: https://www.transfermarkt.de/vfb-stuttgart/startseite/verein/79

Der Datensatz beinhaltet die Transfers zum VfB Stuttgart des jetztigen Kaders mit vorherigem Verein, Nationalität der Spieler, bezahlte Summe für die Spieler sowie die Jahreszahl des Transfers. 

# 1) Edge-Attribute

 <b>from,to,weight,season</b>

from = von welchem Verein kommt der Spieler 

to = ID des Spielers (Rückennummer)

weight = Transfersumme in 100.000 Euro Schritten, gerundet falls abweichend.

season = transferfenster. Erste Jahreszahl des Fensters.

# 2) Node-Attribute
<b>id, name,country,type</b>

id = Rückennumer oder Vereinsname

name = Spieler oder Vereinsname

country = Land

type 1 = Spieler
