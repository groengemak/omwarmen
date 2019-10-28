# Aannames in Berekeningen

> *De basiswaarden en hun herkomst.*


## Fysische grootheden

  * Warmtecapaciteit water, algemeen, 4200 J/kg.K
  * [Warmtecapaciteit beton](https://www.betonlexicon.nl/W/Warmtecapaciteit/), 850 J/kg.K
  * [Warmtegeleiding beton](http://www.joostdevree.nl/shtmls/warmtegeleidingscoefficient.shtml), niet verdicht, 1.4 W/m.K
  * [Warmtegeleiding gewapend beton](http://www.joostdevree.nl/shtmls/warmtegeleidingscoefficient.shtml), max 2.0 W/m.K
  * [Warmtegeleiding linoleum](http://www.joostdevree.nl/shtmls/warmtegeleidingscoefficient.shtml), 0.17 W/m.K
  * [Warmtegeleiding kurk](http://www.joostdevree.nl/shtmls/warmtegeleidingscoefficient.shtml), 0.04 W/m.K
  * Soortelijk gewicht water, algemeen, 1000 kg/m3
  * [Soortelijk gewicht verdicht gewapend beton](http://www.soortelijkgewicht.com/vaste-stoffen/beton), 2500 kg/m3

## Watertemperaturen

Alles in graden Celcius, tenzij anders vermeld.

  * Temperatuur waterleiding 10 graden
  * Temperatuur zonneboiler 70 graden
  * Temperatuur douchewater 40 graden
  * Temperatuur vloerverwarming 40 graden


## Douchen

  * Water op 40 graden, iets boven lichaamstemperatuur
  * Doorstroomsnelheid spaarkop, 6 liter per minuut
  * Terugwinst met een douche-warmtewisselaar, 50%
  * Douchen kost (40-10)x4200x6x50% = 378 kJ/min
  * Bij 30 minuten douchetijd per dag is dat 11 MJ/dag


## Boiler

Dit ontwerp vergelijkt een kleine boiler van 80 liter met gangbare grotere
van 160 liter en 200 liter.  Voor douchen op zonnewarmte alleen, de
hoofdtaak van de boiler in dit ontwerp, volstaat 80 liter al.  Grotere
hebben meer buffercapaciteit maar hebben ook meer zonnewarmte nodig om
die buffer op voldoende hoge temperatuur te bereiken en hun capaciteit
uit te nutten.  Grotere hebben vaak wel meer wikkelingen en ze kunnen
bijvoorbeeld dagwarmte bufferen tot in de avond.

  * Water gaat tot 70 graden, rond de verdampingstemperatuur van alcohol
  * Met heat pipes wordt deze temperatuur het hele jaar door verwacht
  * Bij 080 liter is de warmtecapaciteit (70-10)x4200x080 = 20 MJ
  * Bij 160 liter is de warmtecapaciteit (70-10)x4200x160 = 40 MJ
  * Bij 200 liter is de warmtecapaciteit (70-10)x4200x200 = 50 MJ
  * Hygieneboilers kunnen veilig tot 40 graden dalen, de douchetemperatuur
  * Bij 080 liter op 40 graden daalt de warmtecapaciteit tot (40-10)x4200x080 = 10 MJ
  * Bij 160 liter op 40 graden daalt de warmtecapaciteit tot (40-10)x4200x160 = 20 MJ
  * Bij 200 liter op 40 graden daalt de warmtecapaciteit tot (40-10)x4200x200 = 25 MJ

Zelfs bij 40 graden in een boiler van 80 liter hebben we nog (bijna) de
aangenomen 30 minuten douchetijd.  Maar er is geen buffer voor het overbruggen
van donkere dagen.


## Zonnecollectoren

  * [Jaaropbrengst](https://www.zonnepanelen-weetjes.nl/zonnecollector/rendement-zonnecollector/) 5 GJ/m2.y
  * Ruimte voor 8 m2
  * Opbrengst dus 40 GJ/y
  * Gemiddelde levert dit dus 110 MJ/dag
  * Verloop over het jaar is ongeveer symmetrisch, ongeveer een cosinusvorm
  * Winterdagen leveren 1/4 van het licht van een zomerdag
  * Op de korstste dagen krijg je dus 1/5 van 2x gemiddeld, dus 44 MJ/dag
  * Op de langste dagen krijg je dus 4/5 van 2x gemiddeld, dus 175 MJ/dag

Let op hoe 160 liter op zo'n kortste dag nog tot 40 MJ kan komen, maar
hoe 200 liter al afkoelt (als hij dagelijks leeggetrokken wordt).

Merk op dat verliezen en koudere dagen niet zijn meegerekend.  De
eerste pleit voor een kleinere boiler vanwege de maximale temperatuur,
de laatste voor een grotere.


## Vloerverwarming

De volgende gegevens zijn te danken aan mijn vader, die jarenlang het
gasverbruik heeft bijgehouden, zodat het vergelijkbaar is.

  * Meetwoning met 40 m2 woonkamer, begane grond op kruipruimte
  * Ook raakvlakken naar buiten lijken vergelijkbaar
  * Gasverbruik in hartje winter 84 m3/week meer dan in hartje zomer
  * Stoken gebeurt via een CV-ketel; ook slaapkamers liften soms mee
  * Koken en tapwater zijn verwijderd uit dit getal; het is puur warmte
  * 84 m3/week is [omgerekend](https://hypertextbook.com/facts/2002/JanyTran.shtml) 84x37 = 3108 MJ/week, of 444 MJ/dag
  * 444 MJ/dag voor 40 m2 komt neer op 11 MJ/dag.m2 of 3 kWh/dag.m2

Rond de equinox in datzelfde jaar waren de meetgegevens als volgt:

  * 7 m3/dag in de lente, 2 m3 in de herfst
  * Dat is 7x37 = 259 MJ/dag in de lente, 2x37 = 72 MJ/dag in de herfst
  * Voor deze 40 m2 rekenen we met (259+72)/2/40 = 4 MJ/dag.m2 of 1 kWh/dag.m2

Relativering van deze gasverbruiksgegevens:

  * Dit komt neer op vermogens van 125 W/m2 gedurende 24 h/dag, en kan voortkomen uit de indirecte aard van verwarming via een CV-ketel die het hele huis bedient en ook heet genoeg moet stoken voor douchewater
  * Infraroodpanelen worden aangeraden rond 35 W/m3 of 88 W/m2, maar dat zijn leveranciers die belang hebben bij verkoop van hoge vermogens zonder dat de klant dit ooit waarneemt
  * Urgenda dimensioneert infraroodpanelen rond 50 W/m2 (met bijtellen voor deuren en ramen) en dat zou met deze techniek een piekbelasting zijn

