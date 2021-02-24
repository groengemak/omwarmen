# Warmte en Entropie

> *Entropie is de mate waarin warmte overal gelijkmatig is verdeeld.
> Eigenlijk is het belangrijkte spel met warmte het laag houden van
> de entropie van je systeem, zodat je de keuze blijft houden om warmte
> te doen transporteren door een temperatuursverschil aan te brengen.*

Het is goed om het idee van entropie expliciet mee te nemen in het ontwerp.
Zo blijkt een PCM in een zonneboiler helemaal niet zo handig, terwijl het
onderin het systeem kan helpen een warmtepomp te stabiliseren.


## Wat hebben we nodig?

Ons systeem heeft de volgende dingen nodig:

  * Genoeg warm water om op te douchen, van voldoende temperatuur en vrij van Legionella
  * Warmte opgeslagen in de woning, in de vloerverwarming
  * Grondwarmte opgeslagen in PCM die een warmtepomp voedt maar amper warmte lekt


## Optimale zonnecollector

Heat pipes leveren in de winter meer op dan vlakkeplaatcollectoren, en dat
is bij uitstek de tijd dat het nodig is.  Dit is zeker ook van belang omdat
langdurige opslag van warmte moeilijk is.

Een maximale opstelling vangt de meeste warmte, en dat zal in de zomer een flinke
overcapaciteit zijn.  Het is altijd mogelijk om die capaciteit niet te
benutten door geen warmte af te tappen; maar het is ook denkbaar dat de
warmte voor een solar chimney gebruikt wordt en dus voor de passieve koeling
die zo goed werkt in de heetste landen.

De temperatuur uit heat pipes is geconcentreerd op de hoge temperatuur van
alcoholverdamping, en dat komt ook vrij in de winter, alleen in kleinere
hoeveelheden.  Dat betekent dat de afgevoerde warmte zo veel entropie bevat
als maar mogelijk, terwijl een vlakkeplaatcollector als het ware voorgemengd
is met een hoge hoeveelheid warmte.

Het lijkt handig om een rustige flow van water te gebruiken, en zeker niet
op vol vermogen te pompen.  Batches die opwarmen en dan doorgepompt worden
lijken ook een interessante mogelijkheid.  Het is mogelijk om qua temperatuur
op een bepaald punt te mikken.  Lichte variaties kunnen helpen beslisen of
het sneller of langzamer moet, en constanter of meer met een flow.  Meten
om te weten.

Het water naar de heat pipes toe hoeft niet zo warm mogelijk te zijn.  Wat
telt zijn de overgedragen warmte en de bereikte temperatuur.  Echter, een
lange verblijftijd buiten maakt de kans wel kleiner dat de temperatuur in
de winter bereikt wordt.  Voor optimale performance in de winter lijkt het
dus slim om de uitvoer van de zonneboiler weer terug te voeren, terwijl het
in de zomer handiger kan zijn om kouder water omhoog te pompen en zo minder
pompactiviteit nodig te hebben.

**Keuze:** Heat pipes met 8 m2 oppervlakte.  Rustig of intermitterend pompen.
In de winter pompen vanonder de zonneboiler, in de zomer vanuit de vloerverwarming.


## Optimale warmteboiler

Een gegeven zonneboiler heeft een vaste inhoud.  Het is niet gebruikelijk
die te verkleinen als maar weinig warmte binnenkomt, maar dat zou een techniek
kunnen zijn om de warmte van een zonnecollector niet te verliezen.  Met name
heat pipes geven een redelijk vaste temperatuur af, dus je zou dat als de
minimaal toegevoegde warmte kunnen gebruiken.

Een PCM is in de praktijk niet compacter in opslag dan water.  De soortelijke
warmte van water is erg hoog, een PCM komt halverwege en maakt dat niet goed
op het punt van faseovergang.

Van belang voor het douchen is de warmte die boven de douchetemperatuur
uitsteekt, want die kan nuttig worden gebruikt.  Er zal dus een voortdurende
lekkage van warmte zijn aan de koudere omgeving, met als gevolg dat isolatie
hier erg belangrijk is.

Als een boilervat te klein blijkt, is het bijplaatsen van een Douche-WTW de
simpelste oplossing om het effectieve volume te vergroten; dat komt doordat
de aanvoer al halverwege op weg is naar de douchetemperatuur, en er dus minder
warmte uit de zonneboiler toegevoegd hoeft te worden.

Om Legionella tegen te gaan bestaan twee oplossingen: hoog opstoken van de
temperatuur, of een hygiënewikkeling.  Dat laatste is veel efficiënter in de
zin dat er minder entropie verspild wordt aan de noodzakelijk hoge temperatuur.
Hygiënewikkelingen spoelen goed door, en bij regelmatig gebruik hoopt zich er
geen Legionella in de leidingen op.

Een verwarmingsunit is doorgaans ingebouwd.  Dat gaat waarschijnlijk beter
werken dan een warmtepomp, die de benodigde temperaturen voor douchen eigenlijk
niet goed kan leveren (de COP daalt dan sterk).

**Keuze:** Boiler van 60 liter met een hygiënewikkeling en verwarming.


## Optimale vloerverwarming

De vloerverwarming heeft een temperatuur nodig van ongeveer 40 ˚C.  Dat is
een onomkeerbare verlaging van de temperatuur, maar de menging met koud geeft
zelf ook energie af, in de vorm van Gibbs vrije energie.  Als het dan meteen
in de vloerverwarming vloeit is dat welbesteed.

De verlaging van temperatuur kan gedaan worden met een vaste of instelbare
mengkraan die water uit de vloerverwarming bijmengt.  Als warmte uit de
zonnecollector wordt gehaald zal er ook iets terug moeten naar boven.  Dat
kan dan goed met een warmtewisselaar worden voorbereid.  Hierbij keert dan
zo warm mogelijk water terug in de doucheketen.  Aangezien vloerverwarmingen
niet zo snel stromen zal die overdracht goed voldoen.  Twee leidingen strak
tegen elkaar gelast, met gezamenlijke isolatie eromheen, zou moeten werken.

Er is een groep voor woonkamer, keuken en de hal rond de trap, in volgorde
van belangrijkheid voor woongenot.  De bedrading blijft ~1m van de muren
en randen, omdat daar een gradiënt mag ontstaan.

Om ook te koelen kan een extra groep met PCM worden toegevoegd.  Schakel die
bij en het water circuleert daar ook langs.  Als geen andere groep open staat
dan kan de zonnewarmte eigenlijk meteen doorstromen naar de PCM.  Dat loopt
dan via de mengkraan, dus het is meer water dan normaal; dat draagt vast bij
aan een betere verdeling van de warmte in de PCM (waar de temperatuur egaal
is en de verdeling van phase changes dus niet vanzelfsprekend is).

**Keuze:** Vloerverwarming na een mengkraan, overflow via warmtewisselaar
terug naar de zonneboiler of zonnecollector.  Groepen voor woonkamer,
keuken, hal en PCM.


## Optimale PCM

Een PCM is geschikt om in een klein temperatuurbereik veel energie op te
slaan.  Kleine variaties in temperatuur met de omgeving zullen de lekkage
beperkt houden, ook bij wat minder isolatie.  Warmte wordt toegevoegd en
onttrokken, en moet wel degelijk in totaal neutraal zijn, dus ook het
toevoeren van warmte aan een PCM in warmte tijden is nodig om er in
koudere tijden voordeel van te hebben.

Het is denkbaar om meerdere stages in een PCM te hebben.  Bijvoorbeeld in
relatie tot de grond eentje op 10 ˚C en op een woonvloer een tweede
rond 18 ˚C.  In beide gevallen zijn de temperaturen stabiel en geven dus
minimale lekkage.  Het is voor warmtewinning zelfs aantrekkelijk iets
onder de omgeving te zitten, zodat er een natuurlijk ingaande stroom is.
Daarentegen zal bij iets warmer stoken niet veel energie opgaan in de 18 ˚C,
en zou een kleine isolatie al volstaan als dat tegengegaan moet worden.
In de praktijk kan het vereffenend werken en dat is alleen maar goed.

Een fijne PCM, als voorbereiding op een warmtepomp, zou warmte eerst opslaan
in een blok van 18 ˚C en daarna doorstromen naar het blok op 10 ˚C; als
invoer voor een warmtepomp zou het de omgekeerde richting gebruiken.
De tweede stage is een interessante optie voor later; vooralsnog plan ik
een blok van 10 ˚C in de garage of ingegraven in de grond.

De energie in de PCM moet volstaan voor enige weken.  In 4 m3 kan ongeveer
0,5 GJ opgeslagen worden, goed voor ongeveer een maand.  Er kan redelijk
van uit worden gegaan dat zowel hittegolven als vriessprints niet zo lang
gaan duren, zodat het gebruik van infraroodpanelen minimaal nodig is.

**Keuze:** Een PCM van ongeveer 4 m3 onder de trap in de schuur.  Vermoedelijk
op 10 ˚C, wat geschikt is als afzetpunt voor vloerverwarming.  Goede connectie
met het beton van de vloer eronder, naar opzij geïsoleerd.  *Nu nog niet.*


## Optimale warmtepomp

Een warmtepomp kan de PCM vervolgens uitnutten om van 10 ˚C naar 40 ˚C
te gaan met een COP van ongeveer 4.  Dit ontlast de infraroodpanelen en
gebruikt de opgeslagen warmte in de PCM.

Als de woonvloer een PCM op 18 ˚C heeft dan wordt het mogelijk rondpompen
van energie, en dat zou raar kunnen zijn.  Het is niet zo dat de COP hier
nog overheen gaat, de PCM slaat echt de energie op.  De warmtepomp is meer
degene die de warmte opnieuw uitmikt, zowel qua plek als qua timing.


**Keuze:** Nog niet uitgewerkt.  *Nu nog niet.*

