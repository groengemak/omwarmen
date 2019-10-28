# Vloerverwarming

> *Dit project is nogal eigenwijs met vloerverwarming.  Het haalt alle
> warmte uit de zon die het kan krijgen, en stopt dat dan niet in een
> enorme watertank, maar in het beton van de woonvloer.*

Het idee is als volgt:

  * Zonnecollectoren vangen zonnewarmte op, liefst ook uit diffuus licht
  * Een relatief kleine zonneboiler verzamelt tapwaterwarmte
  * De rest wordt in betonvloeren gestopt als vloerverwarming
  * De betonvloer is hierbij het warmtereservoir in plaats van watertanks
  * Hierdoor verliest het zonnewater relatief veel warmte
  * Waar nodig is met infraroodverwarming bij te verwarmen

## Tapwater gaat voor

Een (redelijk goed geisoleerd) boilervat kan water redelijk lang op een
prettige douchetemperatuur houden.  Ook afwaswater en wasmachinewater is
hier te vinden (sommige machines hebben hier een "hot fill" voor).

Als het water van de zonnecollector warmer is dan het water in de boiler,
dan is het een goed idee het door de boiler te leiden.  Dit koelt het water
al wel af, maar douchen is minder gemakkelijk aan te vullen dan vloerverwarming
die geldt als achtergrondwarmte die met infraroodpanelen aangevuld kan worden.

Een uitwerking hiervan kan een klep zijn die water van de zonnecollector
via een "kortsluiting" langs de boiler laat vloeien in plaats van het te
dwingen er doorheen te reizen.  Als beide wegen open staan zal er weinig
of niets door de boiler gaan voeren, als die tenminste veel meer weerstand
tegen de waterstroom biedt.


## Beton als warmtereservoir

De dimensies van de betonvloer:

  * de vloer is 15 cm dik, en weegt dus rond 375 kg/m2
  * woonkamergroep 20 m2
  * keukengroep 15 m2
  * overloopgroep 5 m2
  * samen goed voor 10 m3 beton of 15000 kg beton
  * beton heeft een warmtecapaciteit rond 0,85 kJ/kg.K, water is 4,2 kJ/kg.K
  * al dat beton is dus vergelijkbaar met 3000 kg of 3000 liter water

Let op dat we het beton niet (veel) warmer willen maken dan 40 graden Celcius,
de werktemperatuur van vloerverwarming.  Nemen we een basistemperatuur van
10 graden aan, en 70 graden uit de zonnecollectoren, dan is dus maar de helft
van de capaciteit te gebruiken.  Het halve werk is een goed begin!

De capaciteit mag dus nog gehalveerd worden tot 1500 liter water als we willen
rekenen met 70 graden als doeltemperatuur voor een equivalente boiler.  En zo
komen we op een vergelijkbaar boilervat voor dit warmtereservoir in beton.
Daar komt dan nog de echte boiler voor douchewater bij.

Natuurlijk wordt de vloerverwarming slim ingezet, door eerst de primaire
ruimtes te verwarmen, of daar waar het relatief koud is.  Dat is normaal,
ook in de praktijk van zonneboilers met hulpvaten wordt onverdroten water
heen en weer gepompt om er het meeste winst uit te halen.

De retourtemperatuur van de vloerverwarming is erg laag, doorgaans onder
40 graden.  Dat betekent dat langzamer kan worden gepompt in het circuit
met zonnewarmte.  Al met al verbetert de overdracht van warmte naarmate het
systeem een groter verschil van temperaturen overbrugt.  Als alleen een
boiler wordt verwarmd, dan komt er een punt waar die 60 graden bereikt en
nog amper warmte opgepikt kan worden.  Enfin, dat is dus waarom je extra
vaten (of vloeren) wilt hebben.

Uiteraard geldt voor de isolatie van een betonvloer dat die abominabel
is; het hele idee van vloerverwarming is immers de afgifte van warmte!
Omdat de warmte echter over een "dubbele" capaciteit wordt verdeeld om
een lagere temperatuur te krijgen, kan worden gesteld dat de warmteweerstand
dubbel zo hoog is als de vloerverarming zelf aangeeft.


### Beton en ruimte als warmtereservoir

Het is ook nog mogelijk om de ruimte boven de vloerverarming mee te
rekenen in de warmtecapaciteit.  Dat wordt al snel vaag, omdat er dan
factoren gaan meespelen als tocht en isolatie van de woning.  Dit is
goed om te weten voor het wooncomfort, maar verder zinloos complicerend
voor een warmtecapaciteitsberekening.

Dit 
[principe staat bekend als BKA](http://www.cementenbeton.nl/duurzaam-bouwen/thermische-massa/energiek-beton---brochure)
in de beton- en cementindustrie: Betonkernactivering.
Inmiddels heeft men wel onderkend dat het inbouwen van waterleidingen in
het midden van een pakket beton veel traagheid geeft, dus is men ertoe
overgegaan het dichter naar plafond of vloer te bewegen.  Vloer is het
meest geschikt voor verwarming, omdat warmte opstijgt, en plafond is de
beste plek om te koelen, omdat koude daalt.

Dit artikel vermeldt temperaturen van 25 graden voor verwarming en
20 graden voor koeling.  Het geeft aan dat verwarming in een vloer
ongeveer 11 W/m2.K kan overdragen, terwijl koeling in de vloer minder
efficient verloopt met ongeveer 7 W/m2.K overdacht.  Dit is nog zonder
de vloerbedekking mee te nemen, uiteraard.  Verder vermeldt het NEN 5128
als EPC-normering voor woonhuizen die BKA toepassen.

Algemeen onderschrijft dit artikel het idee dat hier wordt geponeerd,
zowel voor verwarming alsook als systeem voor gebouwkoeling.  De link
met warmtepompen wordt genoemd als ideaal, omdat het dankzij de grote
oppervlaktes en trage reactietijden kan werken met kleine sprongen
in temperatuur -- waarbij warmtepompen optimaal presteren.  Het artikel
meldt ook dat behoefte kan bestaan aan lokale aanpassingen, en dat is
precies waarom infraroodpanelen in dit plan zijn opgenomen om lokale
zones aanpasbaar te maken (tenminste in de richting van verwarming).

**TODO:** Mogelijke correctie: een watertemperatuur van 40 graden voert
tot een betontemperatuur van 27 graden.  Bij koeling voert water van
13 graden tot een betontemperatuur van 17 graden.  Bron: blz 28 van
onderstaand magazine over cement & beton.  Dit beinvloedt dan wel de
warmtecapaciteit van het beton.


## Lekkage van Betonwarmte

Een betonvloer is altijd gewapend, omdat beton alleen amper trekkrachten
aankan.  Als dat de gangbare (onduurzame) bewapening is met metaal, dan
is dat een warmtegeleider.  Vloeren die doorlopen naar buren zijn daarmee
een lekkanaal voor warmte.  Idealiter nemen de buren dus het systeem ook
op in hun woning!  Bij BKA wordt vaak een heel gebouw op deze manier
uitgevoerd en speelt dit minder dan in een woonhuis.

In een woonhuis moeten we ons afvragen hoe de betonwarmte wordt verdeeld
over de te verwarmen ruimtes en eventuele lekkages naar aangrenzende
woonhuizen.  We bepalen daarom voor beide de afvoersnelheid in W/K en
berekenen het verloren percentage, waarbij de temperatuur er niet toe
doet.

Stel je voor dat je een meter van de randen blijft, met een warmteweerstand
van gewapend beton van 2.0 W/m.K en een dikte van 15 cm, dan is horizontaal
per meter breedte het oppervlakte 0.15 m2 en de afstand 1 m, dus de
warmteoverdracht per graad en per meter breedte is 2.0x0.15/1 = 0.3 W/m.K
(dimensie gelijk aan die van de soortelijke warmteweerstand, maar het gaat
hier over meters breedte).  Met een rand van 2x11 = 22m naar de buren is
het totale verlies per graad dan 0.3x22 = 6.6 W/K.  Als ook de buren
warmte in de betonvloer jagen dan neemt dit uiteraard af.

Tegelijk wordt een oppervlakte warm.  Gaan we uit van 40 m2 met isolatie
aan de onderzijde en 5 mm linoleum (0.17 W/m.K) of 3 mm kurk (0.04 W/m.K)
als vloerbedekking, dan vinden we respectievelijk 0.17x40/0.005 = 1360 W/K
en 0.04x40/0.003 = 533 W/K als overdracht per graad.

We verliezen dus, ongeacht de betontemperatuur,
6.6/1360 = 0.5% bij linoleum en
6.6/533 = 1.2% bij kurk.  Beide lijken acceptabel, en op de koudste
dag waarop het budget voor vloerverwarming 33 MJ is houden we daarvan na
verrekening van lekkage naar buren
33x(100%-0.5%) = 32.8 MJ over met linoleum en houden we
33x(100%-1.2%) = 32.6 MJ over met kurk.  Beide zitten in de marge van
de afronding en we kunnen dus blijven rekenen met 33 MJ.

De warmteweerstand van de vloerbedekking vertraagt de afgifte van warmte
uit het beton, maar afgezien van bovenstaande marginale lekken heeft het
geen verliezen tot gevolg.  Net als bij een elektrische weerstand die een
condensator oplaadt en uiteindelijk de ingangsspanning bereikt, zal ook de
betontemperatuur uiteindelijk doordringen via de vloerbedekking, ongeacht
de hoogte van de warmteweerstand.


## Mengen van zonnewater met retourwater

De warmte van de zonnecollectoren is, ook als die door het boilervat is
gegaan, vaak te warm voor vloerverwarming.  Niemand wil op een vloer van
70 graden Celcius moeten lopen!  Het kan nodig zijn om retourwater van de
vloerverwarming terug te mengen in de flow die naar de vloerverwarming
gaat.  Dit kan vermoedelijk worden gedaan met een eenvoudige mengkraan
die op een vaste temperatuur is ingeregeld.


## Isoleren is Sparen voor Later

Als de temperatuur van de vloer verandert, dan heeft dat een lineaire
invloed op de afgifte van warmte, zowel naar de ruimte als naar het
overige beton.  Als het overdag warm is, dan is het dus moeilijk
om het beton op te warmen voor 's avonds als het afkoelt.  De enige
parameter die daarbij helpt is de mate van isolatie tussen vloer en
ruimte.

Zoals houten luiken overdag openstaan en warmte verzamelen, om 's avonds
dicht te gaan en naar buiten te isoleren terwijl ze naar binnen uitstralen,
zo zouden we kunnen zoeken naar een veranderlijke vloerconfiguratie, die
het gemakkelijker maakt om overdag warmte in het beton te stoppen en het
er 's avonds weer uit te halen.

**TODO/IDEE:** Dat kan onder andere door matten en
tapijten worden geregeld, vooral met materialen zoals kurk of hout of
wellicht een folielaag van aluminium.  Een vraag zou kunnen zijn of dit
effect ook te bereiken is met bijvoorbeeld een vloeistof in de betonlaag?
Of kan ik een structuur vanonder de bank uitklappen of uitrollen boven de
vloer?  Of misschien een opblaasbare ballon van aluminiumfolie?


## Overschot aan zonnewarmte

Het is mogelijk om een extra groep aan de vloerverarming te koppelen
voor "gekke projecten", zoals een droogkast voor groente, fruit en
lijnzaadcrackers.  Er zijn wel meer natuurlijke processen die rond of
onder 40 graden plaatsvinden, zoals bier, yoghurt, tempeh.

Maar in de zomer is er domweg veel te veel warmte.  In die tijd zou je
idealiter overgaan tot seizoensopslag, dat wil zeggen het omzetten van
de warmte in een stabiele vorm die in de winter weer kan worden aangeboord.
Dat kan bijvoorbeeld in de vorm van chemische verbindingen, met name zouten
lijken heel geschikt.  We hebben dan nog de keuze om te gokken dat er
genoeg warmte zal zijn om via de relatief kleine boiler mee te douchen,
maar onvoldoende voor een warm huis.


## Koelen via de vloer

Een circuit voor vloerverwarming kan ook gebruikt worden om de vloer
te koelen.  Een vlakkeplaat zonnecollector straalt ongeveer half zo
veel uit als hij overdag invangt, maar een heat pipe is op dit punt
hopeloos.  Er is natuurlijk niets op tegen een extra vlakkeplaat neer
te leggen speciaal voor infraroodstraling richting de sterren (of naar
andere delen van de broeikas).

Een andere oplossing kan zijn in de koude grond onder de woning.  Dat
zou tevens als seizoensopslag kunnen dienen; dat is dan een warmtepomp.
Een seizoensopslag in zout kan mogelijk ook nog hulp bieden, zeker als
we die op lagere temperaturen bedrijven omdat we gokken op voldoende
douchewarmte in de winter.


## Aanvulling met infraroodpanelen

Een vloerverwarming op zonnecollectoren kan geen volledige warmtebron
zijn, tenzij die stevig overgedimensioneerd is.  Er is immers gewoon
minder licht en warmte in de winter.

Het handige aan infraroodpanelen in deze setting is dat ze rustig
staan te nietsen zolang de vloerverwarming het aankan, om dan bij te
springen wanneer het nodig is.  In plaats van overdimensionering van
het hele systeem is er dus met deze relatief simpele uitbreiding veel
dynamiek te winnen, ook als het dakoppervlak ontoereikend is.

Het valt hierdoor te verwachten dat juist in de winter een stevige
toename van elektriciteit ontstaat; minder achtergrondwarmte beschikbaar
net terwijl het buiten stervenskoud is.

