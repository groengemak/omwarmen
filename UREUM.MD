# Energie uit Ureum

> *Een mens plast ongeveer 11 kg ureum uit per jaar, dat qua
> energie vergelijkbaar is met 16 kg waterstof.  En mocht je
> zelf te weinig brouwen dan kan het altijd nog als kunstmest
> worden ingekocht.  Op dit moment wordt dat van aardgas gemaakt,
> maar er is interesse dit te vervangen door zon en wind.*

Ureum is CO(NH₂)₂, dus een ruggegraat van CO met aan weerszijden
een NH₂ koppel.  Het is een opslagvorm van waterstof dat met
[electrolyse](https://suttonfruit.com/pics/urea_electrolysis.pdf)
vrij kan komen, maar ook directe
[brandstofcellen voor ureum](https://strathprints.strath.ac.uk/34081/1/TAOb924786f.pdf)
zijn in ontwikkeling.  Ureum lost gemakkelijk op in water, nadat
het in droge vorm stabiel kan worden bewaard.


## Processen

Er zijn meerdere processen die ureum afbreken.  Niet allemaal
zijn ze even gunstig.  Doordat CO voorkomt zal bij de verbranding
van elk molecuul CO₂ vrijkomen.  De verhouding waterstof is in
verhouding dezelfde als van aardgas of methaangas, CH4.  Het
grote verschil zit hem in de afwerking van stikstof.

### Microbieel

Microörganismen maken de volgende twee stappen door:

 1. ureum + water --> ammoniak + kooldioxyde
 2. ammoniak + zuurstof --> stikstof + water

In formules is dat

```
CO(NH₂)₂ + H₂O     -->  2 NH₃ + CO₂           [2x]

4 NH₃ + 5 O₂       -->  4 NO + 6 H₂O
--------------------------------------------
2 CO(NH₂)₂ + 5 O₂  -->  4 NO + 4 H₂O + 2 CO₂
```

Hierbij komt de stikstof vrij als NO, ook wel benoemd
als NOx wanneer het wordt besproken als
gezondheidsschadelijke stof.

Als ureum wordt gebruikt als meststof (of alternatief
voor strooizout) dan speelt dit zich in enkele dagen
af.  Het is een rustig proces, maar stinkt naar
ammoniak en doordat veel uitspoelt krijg je de problemen
van overbemesting, zoals onderdrukte wilde paddenstoelen
en blauwalg in zwemwater.  Dit is het proces waar de
Raad van State het "Streep door PAS" tegen nam.

### Ureum naar waterstof

[Electrolyse van ureum opgelost in water](https://suttonfruit.com/pics/urea_electrolysis.pdf)
onttrekt waterstof uit water met ureum bij een veel
lagere spanning (0,37 Volt) dan rechtstreeks uit water (1,23 Volt),
waardoor in principe 70% van de energie van electrolyse bespaard wordt.
Dit is uitgezocht met (goedkope) vernikkelde electrodes:

```
CO(NH₂)₂ + 6 OH⁻    -->  N₂ + 5 H₂O + CO₂ + 6 e⁻

6 H₂O + 6 e⁻        -->  3 H₂ + 6 OH⁻
------------------------------------------------
CO(NH₂)₂ + H₂O      -->  N₂ + CO₂ + 3 H₂
```

Hier komt de stikstof vrij als N₂, het stikstofgas dat
het grootste deel uitmaakt van de lucht die we ademen.
In deze vorm is stikstof compleet onschadelijke.

Het produkt waterstof kan nu worden omgezet in elektrische
energie met een brandstofcel.

### Brandstofcel voor ureum

Hier wordt een
[rechtstreekse brandstofcel voor ureum](https://strathprints.strath.ac.uk/34081/1/TAOb924786f.pdf)
gemaakt volgens een
[vastgelegde procedure](http://www.rsc.org/suppdata/EE/b9/b924786f/b924786f.pdf)
waarmee de volgende reactieverhoudingen werden bereikt:

```
O₂ + 2 H₂O + 4 e⁻  -->  4 OH⁻                    [3x]

CO(NH₂)₂ + 6 OH⁻   -->  N₂ + CO₂ + 5 H₂O + 6 e⁻  [2x]
-----------------------------------------------
2 CO(NH₂)₂ + 3 O₂  -->  2 N₂ + 2 CO₂ + 4 H₂O
```

Ook hier wordt stikstof als N₂ afgestaan, wat niet
schadelijk is voor onze gezondheid.  De omzetting
die hier gedaan wordt is wel efficiënter dan de
gang via electrolyse naar een brandstofcel voor
waterstof.

De metingen tonen aan dat te hoge concentraties de
reactie in de weg zitten; en dat extra stoffen in
urine, zoals elektrolyten, de opbrengst van de
brandstofcel verminderen (onduidelijk of dat dan
gaat over totale opbrengst of alleen het vermogen).

### Warmte uit ureum

Het is mogelijk om waterstof rechtstreeks om te
zetten in warmte, als dat het doel is.  Dat kan
met een brandstofcel natuurlijk niet, je hebt
er een soort HR-ketel voor nodig.

## Energieinhoud

**Onderstaande berekening is een ruwe schatting:**

Als je jaarlijks energie uitplast zoals in 16 kg waterstof, dan win je
[251,6 kJ/mol of 141,83 MJ/kg](https://www.quora.com/How-much-energy-is-produced-when-one-mole-hydrogen-is-burnt?share=1)
uit verbranding en zit je, als je ruw rekent
(temperaturen en aggregatietoestanden negerend), op ongeveer
16 kg/y * 141,83 MJ/kg = 2,27 GJ/y -- een flinke hoeveelheid energie
dus.  Het water komt vaak als stoom vrij, dus daar is ook nog de
(erg hoge) latente energie van waterdamp uit te winnen, net als in
een HR-ketel, vooral ook als het bestemd is voor een vloerverwarming
die niet verder stijgt dan 40 ˚C.

In water opgelost ureum is vergankelijk; geef het een paar dagen en het verandert in
ammoniak, en daarna in NOx wat overbemesting tot gevolg heeft.  Het
is in die zin ook in het belang van waterzuivering om urine op te
vangen voor het verschaalt.  De verschaling treedt op een
[hogere pH dan die van urine](https://theconversation.com/we-found-a-way-to-turn-urine-into-solid-fertiliser-it-could-make-farming-more-sustainable-148877)
niet op, zodat rustig aan het drogingsproces kan worden begonnen,
bijvoorbeeld de volgende keer dat de zon schijnt  Uiteindelijk
zal een concentraat ontstaan, als een witte massa.

**Warmte.**
Bij stookkosten van 0,78 kWh/˚C/d ofwel 2,81 MJ/˚C/d kun je met
2,27 GJ dus 808 ˚C.d (graad-dagen) stoken.  Bijvoorbeeld in de
62 moeilijke dagen qua zon in december en januari,
kan gemiddeld 13 ˚C worden overwonnen.  In werkelijkheid is het
[januarigemiddelde 2,75 ˚C](https://www.knmi.nl/klimaat-viewer/kaarten/temperatuur/gemiddelde-temperatuur/januari/Periode_1991-2020)
en het
[decembergemiddelde 3,25 ˚C](https://www.knmi.nl/klimaat-viewer/kaarten/temperatuur/gemiddelde-temperatuur/december/Periode_1991-2020)
dus samen gemiddeld 3 ˚C.  Tel daarbij de 13 ˚C om te komen op
een beginnetje van 16 ˚C.  Wel wat fris, maar al een hele goede
basis bereikt.  Zoals altijd geldt dat infraroodwarmte zekerheid
kan bieden.

**Elektriciteit.**
Brandstofcellen leveren electriciteit, dat is een alternatieve
route om te overwegen.  2,27 GJ/y komt neer op 630 kWh/y, dus
duidelijk minder dan zonnecellen leveren, maar als het wordt
ingezet in de maanden januari en februari dan is dat gemiddeld
10 kWh/d -- en uiteraard is dat het budget dat infraroodpanelen
nodig hebben om het eerder gevonden 13 ˚C temperatuursverschil
te overwinnen.

**Gasvrij.**
De [energie in aardgas](https://www.energieconsultant.nl/energiemarkt/energie-berekeningen-uit-de-praktijk/omrekening-van-m3-n-naar-kwh/)
is ongeveer 35,17 MJ/m3, dus de 2,27 GJ die een persoon
jaarlijks opwekt staat ongeveer gelijk met
2270 / 35,17 = 64,5 m3 aardgas.  Op het moment is dat een
transportvorm voor aardgas, maar er is onderzoek gaande naar
[ureum uit zon en wind](https://dutch.alibaba.com/Popular/CN_urea-n46-granular-fertilizer-Trade.html)
en dat kan in principe: CO(NH₂)₂ zou in elkaar gepuzzeld
moeten kunnen worden met CO₂, N₂ en H₂O, feitelijk in de
omgekeerde richting bewegend als de verbruiksprocessen.
Misschien dopen we de gasleiding ooit om naar de
[ureter](https://nl.wikipedia.org/wiki/Ureter) van elke
woning!


## Warmtebatterij

Zo gaat ureum werken als een warmtebatterij: droog urine tot
ureum als er een overschot aan warmte is, bij tekort aan warmte
gebruik je eerst ongedroogd urine en later opgeloste korrels
in een brandstofel.

De berekening van de hoeveelheden hierboven geven aan dat een
persoon een goede aanvulling is op een collectie heat pipes,
en diezelfde heat pipes zorgen bij het overschot van warmte
voor het drogen van urine.  In een jaar produceer je ongeveer
11 kg / 1323 kg/m3 = 8,3 dm3 = 8,3 liter urea per jaar.  Nog
geen emmer vol dus.

Overigens, Ureum is een bekende meststof en wordt in
pure vorm als 46-0-0 NPK-kunstmest verkocht (46% van het gewicht
bestaat uit stikstof, en er is geen fosfor of kalium) en is
prima
[in bulk](https://dutch.alibaba.com/Popular/CN_urea-n46-granular-fertilizer-Trade.html)
verkrijgbaar voor een paar dubbeltjes per kilo.
Emmers zie je minder vaak, maar dat
[kost ongeveer](https://www.nederlandsezouthandel.nl/ureum-dooikorrels/)
€140 ex BTW, dus dat is €2,12/kg en voor 11 kg betaal je dan
€23,30.  Of per
[5 zakken van 25 kg](https://www.strooizoutgigant.nl/dooikorrels/5-zakken-dooikorrels)
betaal je €159, dus dat is €1,27/kg en voor 11 kg betaal je
dan €13,99.
(Verder is het een absurd idee straten te ontdooien met
ureum, want het vervalt dan op de meest onzalige manier en
doet dus NOx in de bodem wegsijpelen!  En dit is nog altijd
een afhankelijkheid van aardgas, alleen dan in een vaste
vorm omgezet.)

