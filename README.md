Android App Scanner je desktop aplikacija za Windows koja pomoću ADB-a omogućava pregled i upravljanje instaliranim aplikacijama na Android uređaju. 
Namenjena je IT osobama, serviserima i svima koji žele jednostavno da prate, izvezu ili uklone korisničke i sistemske aplikacije, kao i da detektuju sumnjive/virus aplikacije sa blacklist-e.

Funkcionalnosti
- Povezivanje sa Android uređajem preko ADB-a (potreban uključen "USB Debugging")
- Automatsko skeniranje svih aplikacija na telefonu (korisničke i sistemske)
- Prikaz detalja o uređaju (model, Android verzija, serijski broj)
- Prikaz korisničkih naloga sa uređaja
- Filtriranje i pregled aplikacija po tipu (korisničke, sistemske)
- Detekcija sumnjivih/virus aplikacija na osnovu blacklist-e (TXT fajl)
- Brza deinstalacija korisničkih aplikacija direktno iz liste
- Izvoz liste aplikacija u JSON format
- Pamćenje početnog stanja uređaja – prilikom izlaska pravi listu aplikacija koje su uklonjene tokom rada
- Resetovanje ADB servera jednim klikom (za slučaj ADB greške)

Napomene
- Potreban je ADB instaliran i podešen u PATH-u (ili u folderu aplikacije).
- "USB Debugging" na telefonu mora biti uključen.
- Sve akcije (čitanje aplikacija, deinstalacija, export) rade se bez root-a (ali neka ograničenja važe za sistemske aplikacije).
- Za blacklist koristiš običan TXT fajl – možeš ga menjati prema potrebama.
