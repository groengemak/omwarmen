# Worst Case: Kortste en koudste dag

> *Wat gebeurt er met deze plannen op de kortste en/of de
> koudste dag van het jaar?*

Verwarmen moet altijd werken, ook op de kortste dag, en ook als dat
de kortste dag is.  Infraroodpanelen staan paraat, maar in hoeverre
vermijden we dat met de beoogde opzet?

  * **Zonnepanelen:** Wekken niet erg veel op, rond 1 kWh.  Ruim minder dan
    we deze dag gaan verbruiken.

  * **Douchen:** Kost 11 MJ/dag, terwijl 8 m2 zonnecollectoren goed zijn
    voor 44 MJ/dag op de koudste dag.  Douchen is dus geen probleem.
    In een boiler van 80 liter past 20 MJ bij 70 graden, en met heat
    pipes is dat ook een te verwachten temperatuur.  Grotere boilers
    zijn voor het douchen overbodig onder deze aannames.

  * **Vloerverwarming:** Uit 8 m2 zonnecollectoren is op de kortste dag
    nog 44-11 = 33 MJ/dag over voor ruimteverwarming.  Dat is 12 kWh,
    genoeg om 8 uur lang 30 m2 te verwarmen met 50 W/m2.  We komen dus
    nog best ver met deze aanvulling, zelfs op deze koudere dag.

  * **Boilervoorraad:** Een boiler van 160 liter kan 40 MJ opslaan, en met
    een dagelijkse cyclus zal de temperatuur ook de daarvoor benodigde
    70 graden blijven.  Omdat 44 MJ/dag wordt opgewekt is de boiler in
    een dag te vullen, dus hij mag leeggetrokken worden behoudens de
    benodigde douchewarmte voor de ochtend.  Gaan we uit van 30 minuten
    douchen in de ochtend, dan komt dat neer op de volgende hoeveelheden
    die van overdag tot in de avond opgeslagen kunnen worden:

      - in 080 liter, 20-11=09 MJ/avond plus 44-20=22 MJ/overdag
      - in 160 liter, 40-11=29 MJ/avond plus 44-40=04 MJ/overdag
      - in 200 liter, 44-11=33 MJ/avond

  * **Dagverwarming:** Op het moment dat de zon schijnt dienen we een deel
    van de warmte te verstoken.  Dat kan al meteen na de laatste
    douchebeurt in de ochtend, als de verwachtingen op zon goed zijn.
    Zo kan al vroeg in de dag begonnen worden met betonverwarming.
    Midden overdag kan de energie zo goed toevloeien dat zelfs op de
    kortste dag een overschot in de vloer moet worden gestopt als we
    het niet willen verliezen; gaan we uit van het hele woonoppervlak
    van 30 m2 en vloerverwarming op 50 W/m2, dan komen we op het
    volgende aantal verwarmingsuren:

      - bij 080 liter, 22/0.0036/30/50 = 4 uur/overdag
      - bij 160 liter, 29/0.0036/30/50 = 5 uur/overdag

  * **Avondverwarming:** Warmte opslaan in beton is prima, maar het is wel
    aantrekkelijker om tegen de avond te verwarmen en niet midden
    overdag.  Als we een woonoppervlak van 30 m2 willen verwarmen met
    50 W/m2 dan kunnen we dat uitsmeren over het volgende aantal uren:

      - uit 080 liter, 09/0.0036/30/50 = 2 uur/avond
      - uit 160 liter, 29/0.0036/30/50 = 5 uur/avond
      - uit 200 liter, 33/0.0036/30/50 = 6 uur/avond

    We kunnen ons ook op het halve woonoppervlak terugtrekken en daar
    hetzelfde nastreven, dus 15 m2 op 50 W/m2 (en de rest on demand met
    infraroodpanelen bijverwarmen) gedurende het volgende aantal uren:

      - uit 080 liter, 09/0.0036/15/50 = 03 uur/avond
      - uit 160 liter, 29/0.0036/15/50 = 10 uur/avond
      - uit 200 liter, 33/0.0036/15/50 = 12 uur/avond

    Het lijkt erop dat 80 liter voor deze verlengingstijd tekort schiet,
    maar het verschil tussen 160 liter en 200 liter is niet substantieel.
    Dit komt doordat de ene vlak onder, en de andere vlak boven de
    opwekkende capaciteit van de zonnecollector zit (op de kortste dag).

    Het prijsverschil is echter ook niet altijd groot, en de flexibiliteit
    bij 200 liter is iets groter.  De waarde daarvan zal toenemen naarmate
    er meer warmte aangevoerd wordt, dus op langere dagen met meer zonlicht.

    **TODO:** Toetsen of 50 W/m2 realistisch is.  Het lijkt erop dat dit
    voor beton al best veel afgifte van warmte is.

  * **Vriespunt:**
    Stel het is rond het vriespunt.  Dan moet 20 graden worden toegevoegd
    aan warmte.  Infraroodwarmte kost daarvoor TODO en heeft een vermogen
    nodig van TODO.  Isolatie levert TODO op.

  * **Vorst:**
    Stel het vriest 10 graden.  Dan moet 30 graden worden toegevoegd aan
    warmte.  Infraroodwarmte kost daarvoor TODO en heeft een vermogen
    nodig van TODO.  Isolatie levert TODO op.


