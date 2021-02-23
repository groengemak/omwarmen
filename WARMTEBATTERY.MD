# Warmtebatterij

> *De warmtebatterij van TNO en TU/e slaat energie over langere periodes op,
> en zonder verlies.  Opslag van zomer tot winter is denkbaar.*

Het [CREATE project](http://createproject.eu/documents)
werkt aan een warmtebatterij met chemisch stabiele opslag in zouthydraten.
Neem K2CO3 zouten, en voeg daar water aan toe, dan kan het in de roosterstructuur
worden opgenomen tot K2CO3 . 1,5 H2O.  Mogelijk zijn er ook andere hydraatzouten
die overwogen worden, wij werken met deze verder.
Lees vooral ook de
[testmetingen in het lab](http://createproject.eu/documents/category/4-reports?download=34:d5-3-lab-test-results-with-proof-of-principle-regarding-the-critical-components)
en de
[economische analyse](http://createproject.eu/documents/category/4-reports?download=30:d2-1-economic-value-of-heat-storage-systems)
van deze oplossing.

Soortelijk gewicht hydraatzout: 1200 kg/m3.
Theoretische opslag 600 kJ/kg, praktisch eerder 400 kJ/kg.

Stel we maken een hoek in de hobbykamer vrij voor dit spul.
Hoeveel is nodig voor 5 GJ?
5 GJ / 400 kJ/kg = 12500 kg
en de ruimte daarvoor is
12500 kg / 1200 kg/m3 = 10.4 m3.
Dit sluit aan op de inschatting van 11 m3 die TNO opgaf.

Ruimte onder de trap in de schuur, rustend op de begane grond:
2,5 m x ( 1 m + 2,5 m / 2 ) x 0,8 m = 4,5 m3.
Daarin past 4,5 m3 x 1200 kg/m3 x 400 kJ/kg = 2.16 GJ.
Er zijn mensen die de ruimte onder een trap minder goed benutten.

De voorspelling van het team is dat we helemaal niet de
volledige opslag nodig hebben, dus dat we best toe kunnen
met iets van deze orde.  Zo'n buffervat lijkt dus goed
te doen.


## Open Vragen

Niet alles is nog helder...

  * Leveren heat pipes een voldoende threshold voor deze zouten?
  * Zo ja, dan zouden heat pipes beter aansluiten dan vlakke platen, vooral als het vriest en zonnig is?
  * Kunnen voorraden van hydraatzouten [pellets] in en uit het buffervat gepompt worden?
  * Kan het (zware) buffervat op de begane grond worden geplaatst?
  * Is het dan mogelijk de Heat eXchange nabij het dak te plaatsen?


## Alternatief PCM

Stel we gebruiken een
[S10 zouthydraat PCM](https://www.pcmproducts.net/Salt_Hydrate_PCMs.htm)
met een handige
[inkapseling](https://www.pcmproducts.net/Encapsulated_PCMs.htm).
We hebben dan 1900 J/kg.K soortelijke warmte en een faseverandering
van 250 MJ/m3 bij een soortelijk gewicht van 1515 kg/m3.

De 4,5 m3 onder de trap is dan goed voor het opslaan van
4,5 m3 x 1515 kg/m3 x 1900 J/kg.K = 13 MJ
aan soortelijke warmte plus
4,5 m3 x 250 MJ/m3 = 1125 MJ
aan faseopslag, samen dus 1138 MJ of 1,1 GJ.
Pakken we de inkapselingen als ice pack of tube, dan komen
we op 4,5 m3 x 44 kWh/m3 x 3,6 MK/kWh = 713 MJ in plaats
van 1125 MJ, dus 36% lager; dat overkomt ook het totaal,
dus 1,1 GJ wordt dan 0,7 GJ.  (That hurts a little.)

Dat is minder dan met het buffervat, maar voor de opslag
op korte termijn is het ook veel simpeler.  PCM opstapelen,
buizen erdoorheen, klaar.  Er zijn opties om het te koppelen
aan zonnecollectoren of een vloerverwarmingsgroep, of aan de
ondergrond.  En vooral, met 10 ˚C als temperatuur is de lek
naar de schuur en zeker naar de vloer niet enorm hoog, het
kan echter wel helpen beschermen tegen vorst en zolang het
niet al te koud is "laadt het zich op", dat wil zeggen, kan
een warmtepomp zich er tegen afzetten.  Dat kan dan een
water/water of (goedkoper, en mogelijk even efficiënt)
een lucht/water warmtepomp zijn.

Het opwekken van 0,7 GJ met zonnecollectoren duurt een
tijdje.  Het komt neer op 697 MJ / 3,6 MJ/kWh = 194 kWh.
*Ik kan niets vinden over opbrengsten in de winter, dus
ik kan niet uitrekenen hoeveel dagen dit kan opslaan
en overbruggen.*  Reken met 100 W/m2 en 4h zon, dan zit
je met 8 m2 op 8 m2 x 100 W/m2 x 4h = 3,2 kWh.  Dus deze
"tijdelijke" opslag kan 60 dagen zon opslaan.

Let op dat 0,7 GJ bij een warmtepomp niet met de COP
vermenigvuldigd kan worden; het is juist (1-1/COP) die
uit deze voorraad moet komen, dus dit komt dan ongeveer uit
rond 0,9 GJ.  Dit is de springplank, niet de veerspanning.
Maar dan nog, is dit een prima opslagcapaciteit voor een
afzetpunt voor een warmtepomp.  Reken verder met dit getal;
0,9 GJ / 3,6 MJ/kWh = 250 kWh dan kun je twee panelen van
700 Watt gedurende 250 kWh / 1,4 kW = 179 h aan hebben staan,
of 3h/d in 60d.  Dit is onprecies bij gebrek aan opbengsten,
maar klinkt als een goede ontlasting van infraroodpanelen.
Vergeet ook niet dat je "vol" beginnen kunt, en dan inboeten
naarmate het langer koud en zonloos blijft, maar zodra het
opklaart dus ook weer bijladen.

Let op dat een warmtepomp de PCM ook onder het vriespunt
zou kunnen drukken, door te veel energie te onttrekken.
Dat is dan niet efficiënt meer, en afgeraden.  Beter is
het dan op infrarood over te schakelen.  Sterk aan een
PCM is dat je hem overdag met zonnewarmte weer kunt
opladen, en dan 's avonds gebruiken.  Je gebruik van 5 GJ/y
kost je dan ongeveer 1,25 GJ/y aan elektriciteit, tegen
5 GJ/y voor infraroodpanelen.  Als het kan is een warmtepomp
dus een prima idee, ook om de warmte van overdag te bufferen
(zonder de schuur te zeer te verwarmen zelf).  Het lijkt ook
een stuk simpeler dan een warmtebatterij, en uitgewerkter.

*Douche-WTW en Compostvat.*
Nog een gedachte is om douchewater langs de PCM te leiden.
Dit kan niet met een warmtebatterij wegens de starttemperatuur,
maar 10 ˚C is gemakkelijk gehaald met douchewater!
Er is dan geen reden meer voor een afzonderlijke douche-WTW.
Dit kan ook perfect met een PCM onder de trap.  Een GFT-bak
op douchewarmte zou zelfs nog versterkend kunnen werken en
extra energie opleveren `;-)`


