# Koeltechniek

> *Naast verwarmen wordt ook koeling steeds belangrijker.
> Het ideale klimaat is altijd een andere dag dan de huidige,
> in het ideale geval sleep je daartussen heen en weer, of
> middel je te warm tegen te koud uit.  Passief is beter.*


## Vloerverwarming

TODO.


## Infraroodpanelen

Een infraroodpaneel heeft een temperatuur en straalt daarmee
overeenkomstig energie uit.  Bij het verwarmen is zo'n paneel
bijvoorbeeld 40 ˚C en straalt dan een bepaalde hoeveelheid
straling uit; dat is een vierde macht van de absolute
temperatuur, dus (287,15 K + 40 K)^4.

Als een paneel nu 30 ˚C is, dan straalt het dus best veel
energie weg, vergelijkbaar met het verwarmen van de ruimte
met een paar graden (in mijn praktijk).  Is het binnen
30 ˚C en buiten 18 ˚C dan moet je kijken naar het verschil,
en dat bepaalt dan hoeveel er netto naar buiten stroomt.

Verwarmen met 40 ˚C tot 18 ˚C straalt meer uit dan in,
(287,15 + 40)^4 / (287,15 + 18)^4 = 1,321
dus de opwarming van de ruimte is het gevolg van de
32,1% meer uitstraling dan terugkaatsing uit de ruimte.

Stel nu dat de lucht rond het plafond 30 ˚C is, en het
infraroodlicht kaatst van/naar buiten, waar het 18 ˚C
is.  Dan stralen we
(287,15 + 30)^4 / (287,15 + 18)^4 = 1,167
dus de afkoeling van de ruimte is het gevolg van een
16,7% meer uitstraling dan terugkaatsing van buiten.

Afkoelen gaat dan half zo snel als opwarmen, in een
nacht dat de warmte binnen blijft hangen.  De truc
is dan het infrarode licht naar buiten te kaatsen,
via een spiegel die ook infrarood kaatst.  Dat zou
een "zak" van zilverkleurige Tonzon folie kunnen zijn.

### Variatie: Hemelkaatsen

Als we de infraroodstraling niet naar buiten kaatsen,
waar tuin of muren de temperatuur bepalen, maar naar
de lucht, waar het vermoedelijk een stuk kouder is,
dan keert minder warmte terug.  Vooral als er geen
wolken zijn.  Stel dat we dan 0 ˚C zouden meten met
een infraroodstralingsmeter, dan verliezen we
(287,15 + 30)^4 / (287,15 + 0)^4 = 1,488
dus de afkoeling is dan het gevolg van een 48,8%
hogere uitstraling dan terugkaatsing uit de hemel.

Afkoelen gaat nu dus 13% sneller (1,488 / 1,321)
dan de opwarming in het gegeven rekenvoorbeeld.

Meestal is de hemel kouder, zeker als de zon niet
op fijnstof of waterdampt reflecteert.  Zelfs overdag
is de hemel vaak -15 ˚C, meer naarmate de richting
meer naar de zon neigt.  We verliezen dan
(287,15 + 30)^4 / (287,15 - 15)^4 = 1,844
dus de afkoeling is dan het gevolg van een 84,4%
hogere uitstraling dan terugkaatsing uit de hemel.

Afkoelen gaat nu zelfs 40% sneller (1,844 / 1,321)
dan de opwarming in het gegeven rekenvoorbeeld.

### Extra: Condensatie

Als de temperatuur daalt, dan kan ook minder waterdamp
vastgehouden worden.  Er zal dus condens neerslaan,
vooral op de infraroodpanelen, of het contact daarmee
dat de warmte uit de lucht opneemt.  (TODO: warmte?)

Als de condens wordt opgevangen en de volgende dag
niet weer verdampt, dan blijft de lucht droger.  Dat
draagt bij aan een minder klam gevoel.  Ook in de
nacht zou dit helpen, ware het niet dat de lucht dan
ook koel is en nog altijd 100% vochtig.  We willen wel
minder zweten als het koeler is, dus het voelt wel
minder drukkend.


## Zonneschoorsteen

Lucht laten stromen door opwarming langs een schacht
van 5 meter, en daarmee zuiging creëren die het huis
bovenin afzuigt, waar het heet en vochtig is.


## Planten

Opname van vocht maakt het mogelijk er nieuwe in te
brengen.  Planten die vocht uit de lucht opnemen zijn
er genoeg, ze zijn zelfs nuttig in de douche.  Dit
bereidt de lucht voor op zweten en/of verdamping van
lucht die langs een groot vochtig oppervlak stroomt,
bijvoorbeeld een groot en poreus stuk klei.


## Persoonlijke Gletcher

Een ijskelder (of een persoonlijke gletcher, die onder je
voeten wegsmelt) kan worden gevuld met ijs, zelfs al is dat
maar ijs van 0 ˚C.  Dat kan bijvoorbeeld uit het
[grijze water](GRIJSWATER.MD)
ontstaan als daarin een warmtewisselaar hangt.
Het is dan wel nodig het smeltwater ook weer als
grijswater af te voeren.

De vorming van ijs is normaal in de 60 koudste dagen
(december, januari) want juist dan is grijs water een goede
bron van warmte, met een hoge COP tot gevolg.  Per persoon
komt daar bijvoorbeeld 50 kg ijs vrij, over de hele periode
is dat 3000 kg of 3000 liter.

Zelfs op 0˚C smelt dit ijs niet zomaar, het moet een
latente warmte overwinnen van 334 kJ/kg, dus in 3000 kg
is dat 1 GJ aan warmte die onttrokken kan worden aan
bijvoorbeeld doorstromend water.  Dat doorstromende water
heeft geen anti-vries middel nodig doordat menging van
warmtes toch nooit "doorschiet".  Het is zelfs denkbaar
om hiermee leidingen tegen vorst te beschutten; maar dan
wel met water, niet met het ijs.

De verliezen zijn veel kleiner dan deze afvoer.  Denk aan
een buitenoppervlak van 10 m2, en stel dat dit de grond
op 10 ˚C is zonder enige vorm van isolatie of weerstand,
dan smelt de buitenkant met een tempo dat enkel afhangt
van de warmtegeleiding van grond op 2,0 W/m.K en over
10 m2 en een dikte van 1 m is dat
2,0 W/m.K * 10 m2 / 1 m = 20 W/K en bij het
verschil van 10 K wordt dat 20 W/K * 10 K = 200 W.
In een half jaar verliezen we dan
180 d * 24 h/d * 3600 s/h * 200 J/s = 3 GJ.
*Het is wel duidelijk dat dit niet werkt.*

Opnieuw.  We metselen met baksteen en hebben dan een lambda
van 0,4 W/m.K dus verlies je 4 W/K over 10 J dus 40 W.  In
een half jaar verlies je dan
180 d * 24 h/d * 3600 s/h * 40 J/s = 0,6 GJ ofwel 60% van de
opslag.  *Wel duur, een bakstenen muur van een meter.*
De verhouding tussen volume en oppervlakte is ongunstig;
De kleine hoeveelheid ijs vraagt dus om betere isolatie.

Opnieuw.  We isoleren met 2,5 m2.K/W ofwel 0,4 W/m2.K
en kijken weer naar 10 m2 en een verschil van 10 K.
Dan verliezen we 40 W, of over een half jaar
180 d * 24 h/d * 3600 s/h * 40 J/s = 0,6 GJ ofwel 60% van
de opslag.  *Het begint er een beetje op te lijken.*

Op zich zijn hogere waardes haalbaar, bijvoorbeeld met
[isobooster T5](https://isoboosterspecialist.nl/product/isobooster-t5-12500mm-x-1200mm/)
kom je op 4,6 m2.K/W of 0,217 W/m2.K en dan verlies je
over 10 m2 en 10 J dus 21,7 W, of over een half jaar
180 d * 24 h/d * 3600 s/h * 21,7 J/s = 0,3 GJ of 30% van
de opslag.  Dit is een concrete optie met een flink deel
over, en wel 70% van de ideale 1 GJ over, of 700 MJ of
200 kWh aan passieve vloerkoeling.

Vroeger werden de
[ijskelders](https://nl.wikipedia.org/wiki/IJskelder) geconstrueerd
als diepe structuren (zeg 5 meter) met een tapse bovenkant die met
isolatiemateriaal bedekt werd, een ingang op het noorden had en verder
geen zonlicht liet invallen.  Vaak opgemetseld uit baksteen.

Dit idee is een variant waarbij

  * Aanvoer van het ijs automatisch verloopt door het afromen van grijs water;
  * Het ijs niet gehakt hoeft te worden maar vooral doorgevoerd water koelt;
  * Dampen en gassen die vrijkomen moeten afgevoerd worden naar het riool;
  * Aanvoerlucht kan niet over het ijs stromen, maar wel vlakbij koelen;
  * Het ijs blijft op 0˚C en zou dus niet aan elkaar vast zou moeten vriezen;
  * Smeltwater moet terug naar grijs water; dat was gemakkelijker met natuurijs!


