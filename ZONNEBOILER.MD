# Zonneboiler

> *Tapwater opwarmen met de zon, je zou wel gek zijn als je het niet deed.
> Zonnecollectoren werken prima, vooral als ze overcapaciteit hebben.*

In dit ontwerp kan flink veel oppervlakte aan zonnecollectoren worden
gebruikt, effectief een overcapaciteit als je alleen maar naar tapwater
kijkt, maar het teveel kan richting vloerverwarming afvloeien, waar het
regelrecht bespaart op stookkosten (van infraroodpanelen).


## Zo warm mogelijk

De temperatuur kan in het stookseizoen alleen maar omlaag worden gebracht
(door te mengen met koud) maar concentreren lukt nooit.  Iets met entropie.
Het gebruik van de hoogste temperatuur waar die nodig is, is dus optimaal.

Douchen doe je op iets meer dan lichaamstemperatuur, maar om Legionella af
te doden wil je een duidelijk hogere temperatuur.  Lukt dat niet met de zon
dan moet er (ongeveer wekelijks) elektrisch gestookt worden om eventuele
Legionella alsnog te nekken.  (Elektrisch kan nog altijd betekenen dat je
een kleine warmtepomp gebruikt, maar helemaal vermijden is efficienter.)

Een extra reden voor hoge temperatuur in de boiler is dat het meer warmte
opslaat in hetzelfde aantal liters.  Nogmaals, er kan altijd koud bijgemengd
worden, maar dat kan dan niet meer ongedaan gemaakt worden.


## Zuinig met douchewarmte

Het is mogelijk om zuinig om te springen met douchewarmte met een
warmtewisselaar die het (koude) douchewater voorverwarmt met de
warmte die via het doucheputje wordt afgevoerd.  In de praktijk wint
zo'n systeem vaak ongeveer 50% warmte terug, vooral de vertikale zijn
goed.  Douchewater is vervuild met zeep en lichaamstroep, dus kan het
niet door vloerverwarmingsleidingen worden gevoerd.

Dit ondersteunt langer douchen, en afgezien van het waterverbruik dat
dat oplevert kan dat bijdragen aan de houdbaarheid van een wat kouder
huis.  Lekker opwarmen onder de douche, zeg maar.  Geen idee hoe zinvol
dat effect is.

Een warmtewisselaar die 50% besparing geeft, maakt een half zo grote
boiler mogelijk.  Anders gezegd, er is maar de helft van de capaciteit
in de boiler nodig voor hetzelfde douchecomfort.  Onbenutte warmte in
de boiler kan eventueel worden gebruikt om de vloerverwarming 's avonds
een beetje extra te geven.  Niet veel, schat ik, maar dit systeem laat
zich eventueel wel met meer tanks uitbreiden?  Let op dat de
warmtewisselaar geen verbeteringen teweegbrengt voor de vloerverwarming.


## Hygieneboiler

Er is ook een optie van een afzonderlijke winding (een buis door het
boilervat) voor het douchewater.  Dit heet een hygieneboiler; er zal
bij regelmatig gebruik geen Legionella voorkomen, zeker niet als de
buis van koper is.

Het toegevoerde water kan koud water zijn, of uit de warmtewisselaar
komen.  Het verschil is vooral hoe snel het door die buis stroomt.
Het beste tegen Legionella is snel stromen, dus koud toevoeren aan de
hygienewikkeling kan in dat opzicht slim zijn?  Dat geeft ook de beste
warmteoverdracht en de kortste leidingen voor de warmtewisselaar.

In een dergelijke opstelling kan het boilervat gevuld worden met
hetzelfde water dat naar de zonnecollectoren gaat en dat ook in de
vloerverwarming overgaat.  Vragen die dat oproept gaan over antivries
en andere toevoegingen die her en der problemen kunnen geven.


## Dimensionering boiler

Een boiler van 80 liter lijkt al voldoende voor deze setup.  In de
praktijk gelden die als kleintjes en hebben die te weinig wikkelingen.
Het zal dus wel neerkomen op 160 liter of 200 liter.

Het onhandige aan een te grote boiler is dat de warmte van de
zonnecollectoren over meer liters wordt verdeeld, met als gevolg
dat er meer zonuren nodig zijn om een gewenste temperatuur te
bereiken, en bijvoorbeeld Legionella uit te sluiten.

Normaalgesproken geldt als tegenwicht dat een overdaad aan warmte ook
opgeslagen kan worden.  Dat is hier minder het geval omdat we die
warmte in het beton van de vloerverarming gaan stoppen.  Alleen voor
wat extra warmte in de avond zou het interessant kunnen zijn, maar
dat is van secundair belang.  Overdag stoken warmt een huis op, zeker
als het goed geisoleerd is, en maakt stoken 's avonds amper nodig.


## Dimensionering collector

Heat pipes en vlakkeplaatcollectoren ontlopen elkaar niet zo erg.
De opbrengst is ongeveer 1,5 GJ/m2.jaar en daarvan is er in de
winter ongeveer 4x minder dan in de zomer (wegens de langere weg
van het zonlicht door de atmosfeer en de kortere dag).

Over het jaar is de opbrengst gemiddeld 4 MJ/m2.dag en op de koudste
dag dus een kwart van de warmste dag, dus op de koudste dag rekenen
we met een vijfde van tweemaal deze waarde; dat is 1,6 MJ/m2 op de
koudste dag.

Nemen we een oppervlak aan zonnecollectoren van 8 m2, wat haalbaar
is op het gegeven dak, dan zitten we op 13 MJ voor die koudste dag.
Daarmee moet water van 4 graden Celsius naar 40 graden worden
verwarmd, met de helft retour via een warmtewisselaar, dus komen
we op 18 graden te overbruggen temperatuurverschil, voor water met
4200 J/kg.K.

We hebben hierdoor 174 liter douchewater per dag beschikbaar.  Bij
6 liter per minuut (met een spaardouchekop) is dat 30 minuten
douchen.  Dat wil zeggen: 30 minuten energieneutraal douchen.
Daarvoorbij moet bijgestookt worden, en hangt het van het verdere
jaar af of we energieneutraal zijn (wat uiteraard goed mogelijk is).

Let op dat een boiler met een voorraad van 80 liter water op
70 graden in staat is om veel meer dan 80 liter bij te verwarmen.
Het water is 66 graden warmer dan de instroom, en om 18 graden
te overbruggen is 18/66 hiervan nodig; totaal 293 liter.  Dat is
onder dezelfde aannames genoeg voor bijna 49 minuten douchen.  Een
2x zo groot boilervat levert 2x langer douchen als het op 70 graden
zit.

Uiteraard geldt dat de warmte moet worden toegevoegd als die is
onttrokken.  Dus langer douchen dan de beschikbare 30 minuten
betekent vroeg of laat dat er bijverwarmd moet worden.  Om dat te
vermijden moet dus meer oppervlakte gebruikt worden.


## Virtuele Boiler

Als douchegedrag voorspeld kan worden, dan kan een deel van de
warmte uit de boiler daarvoor worden gereserveerd.  Het is alsof
elke doucheganger een eigen "virtuele boiler" ter beschikking
heeft staan.  Wat resteert kan in de vloerverwarming worden
gebruikt, bijvoorbeeld in de voorgaande avond.

