# 01-04-02-Domino
## Osztálychierarchia készítése dominó játék egy dominójának.
Feladata objektum orientált programban modellezni a dominó játék egy dominóját. Ehhez készítse el a következő osztályhierarchiát:  
Készítse el az oldal (side) osztályt melynek egy adattagja van, az azon az oldalon lévő pöttyök száma és az oldal neve. A pöttyök száma egy egész szám. Készítsen konstruktort az oldal megadására. A pöttyök számából készítsen olvasható tulajdonságot pont (point) néven.  
Mintakód az osztályhoz:  
*Side rightSide=new Side(„jobb oldal”,3);*  
*Side leftSide=new Side(„bal oldal”,8);*  
*Console.WriteLine(rightSide);*  
Kimenet:  
*A  jobb oldal 3 pöttyöt tartalmaz.*  

Készítse el a dominó (domino) osztályt menynek két adattagja van, a jobb oldal és a bal oldal (side). Ezek az előbb elkészített dominó oldal osztályú adattagok. Készítsen egy olvasható őszpontszám (total point) tulajdonságot, amely a dominó bal és jobb oldalán lévő pontok összege.  
Mintakód az osztályhoz (folytatás):  
*Domino d=new Domino(rightSide,leftSide)*  
*Console.WriteLine(d);*  
Kimenet:  
*Dominó adatok:*  
*A  jobb oldal 3 pöttyöt tartalmaz.*  
*A bal oldalon 8 pöttyöt tartalmaz.*  

Mintakód az osztályhoz (folytatás):  
*Console.WriteLine(„Összpontszám:”+d.TotalPoint);*  
Kimenet:  
*Összpontszám: 11*  
