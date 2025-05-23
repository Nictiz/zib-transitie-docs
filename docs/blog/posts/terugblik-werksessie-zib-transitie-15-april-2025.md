---
title: Terugblik op de werksessie rondom de zib-transitie van 15 april 2025
date: 2025-04-22
authors:
  - arjanvanbremen
slug: terugblik-werksessie-zib-transitie-15-april-2025
categories:
  - Terugblik
---

# Terugblik op de werksessie rondom de zib-transitie van 15 april 2025

De twaalfde werksessie van de zib-transitie vond plaats op dinsdag 15 april 2025 om 10 uur bij Nictiz. De meeste
deelnemers waren fysiek aanwezig en een aantal online. De bijeenkomst werd geopend door Dave met een update over een
aantal zaken. Het doel en de opzet van de rest van de werksessie was een vervolg op het beproeven en ervaring opdoen in
het modelleren van archetypes, FHIR-profielen en zibs in hun samenhang.

<!-- more -->

Tijdens de opening gaf Dave een update over het Plan van Aanpak dat wordt opgesteld naar aanleiding van de reactie van
VWS op het Architectuur-advies. Er ligt nu een eerste versie voor met als inhoud de volgende onderwerpen:

- Samenvatting architectuur advies
- Transitie naar zibs 2.0
- Flexibeler releasen van zibs in relatie tot baseline besluit
- Documentatie ontsluiting en community participatie ("gereedschapskist")
- Ondersteunende activiteiten

De thema's "Transitie naar zibs 2.0" en "Flexibeler releasen van zibs" zijn al wat verder uitgewerkt in een voorlopige
fasering. De deadline voor oplevering van het PvA is 30 april. Binnen dat tijdsbestek zal gekeken worden hoe de
community inbreng kan geven.

Dave meldde verder dat vervolg op de discussie Databeschikbaarheid aan de hand van het implementatiemodel beschikbaar is
in een blog van Gerda Meijboom en Gé Klein Wolterink: Databeschikbaarheid - bekijk het eens van de andere kant.

Na de opening deelde Wouter Zanen een reflectie op de modellering van de zib Behandelaanwijzing2 in openEHR, een
exercitie waar de community tijdens de vorige werksessie mee aan de slag ging. Hij liep langs de knelpunten en
uitdagingen waar je bij zo'n modelering tegen aan loopt. Dat begint bij de keuze welk archetype de juiste is voor de
modellering en of de betekenis van het concept dat hoort bij de zib en het archetype overeenkomen. Dat op zich is soms
al lastig om dat helemaal scherp te krijgen. Het juiste archetype in dit voorbeeld is "Advance intervention decisions"
en niet "Advance care directive" zoals aan de hand van de naam gedacht kan worden. Sommige data-elementen van de zib
zijn vervolgens (redelijk) goed te mappen, sommige (helemaal) niet of lastiger. Een fundamenteel verschil is dat het
archetype bedoeld is voor een setje van afspraken over meerdere interventies terwijl bij de zib er voor elke interventie
een aparte instantiatie nodig is. Ook opmerkelijk is dat in het archetype een CPR (cardiopulmonale reanimatie)
interventie apart gemodelleerd is van de andere interventies. Ook is er bijvoorbeeld een verschil in de waardenlijsten
die gebruikt worden bij het behandelbesluit: recommended, conditional recommendation, not recommended, unknown versus
wel uitvoeren, anders, niet uitvoeren. Ook hier is de mapping een uitdaging.

Pieter Edelman gaf vervolgens een terugkoppeling van de FHIR profiling voor de zib Behandelaanwijzing2, waarmee de
community ook aan de slag is geweest tijdens de vorige werksessie. Hij liet zien dat Behandelaanwijzingen in FHIR zijn
vertegenwoordigd met de [Consent](https://www.hl7.org/fhir/R4/consent.html)-resource, maar dat de usecase "advanced
care" nog niet goed is uitgewerkt in Consent. Sommige zib-concepten zoals RedenBeeindigd, Toelichting, Wilsverklaring
zijn slechts 1x mogelijk (bug in FHIR), BehandelBesluit/SpecificatieAnders zijn niet goed te mappen. Daarnaast zijn er
FHIR-elementen die niet terugkomen in de zib: Consent.status, Consent.policy of Consent.policyRule. Vervolgens liet hij
zien hoe het in de praktijk uitgewerkt is in het profiel [zib-TreatmentDirective2](
https://simplifier.net/nictiz-r4-zib2020/zibtreatmentdirective2) en hoe daar oplossingen zijn gecreëerd voor de
knelpunten.

Na deze inleidingen was het tijd voor alle deelnemers om aan de slag te gaan. Als onderwerp was gekozen een formulier
voor het uniform vastleggen van proactieve zorgplanning (PZP) zoals dat is ontwikkeld voor de palliatieve fase. Het
[formulier](https://palliaweb.nl/overzichtspagina-hulpmiddelen/uniform-vastleggen-proactieve-zorgplanning) is te vinden
op [palliaweb.nl](https://palliaweb.nl/). Leidend is de [Richtlijn Proactieve Zorgplanning](
https://palliaweb.nl/richtlijnen-palliatieve-zorg/richtlijn/proactieve-zorgplanning).

Van belang om te vermelden is dat het thema PZP/Behandelaanwijzing hier enkel is gekozen als inhoudelijk onderwerp om
ervaring op te doen met de methode, niet om te komen tot oplossingen voor de praktijk of om naast andere initiatieven
die op dit onderwerp lopen iets nieuws te doen.

Aan de deelnemers werd gevraag om van het formulier de onderdelen 2 (Gesprek gevoerd in bijzijn van ...), 3
(Belangrijkste doel van overeengekomen beleid) en 4 (Behandelgrenzen) te modelleren zoals Zib2.0 en daarbij te kijken in
hoeverre de architectuurprincipes daarbij helpen. De aanwezige deelnemers gingen daarmee in 4 groepen aan de slag.
Tussendoor was er tijd voor lunch. Tot slot werden de resultaten en bevindingen van de groepen plenair gedeeld.

Tijdens de plenaire terugkoppeling bleek dat de groepen een behoorlijk verschillende aanpak hadden gekozen met ook heel
verschillende resultaten (voor de resultaten zie de volgende pagina). Zo had een groep feitelijk het formulier
gemodelleerd en ging het bij een andere groep vooral over de betekenis van de concepten en hoe dat vertaalt naar
bouwstenen en sub-bouwstenen. Een andere groep ging sterk uit van de architectuur principes en m.n. het principe: ga uit
van Internationale standaarden. Zij begonnen bij het archetype dat het best bij de te modelleren concepten past.

Een van de conclusies van de dag was dat het handig zou zijn om een handleiding of stappenplan te hebben dat beschrijft
hoe je deze thematiek aanpakt. Welke stappen doe je achtereenvolgens en hoe gebruik je de architectuurprincipes daarin.
Dit zal worden meegenomen in de aanpak van het vervolg.

Een andere observatie was dat heel veel discussie gedurende de hele werksessie ging over de vraag wat er precies bedoeld
wordt met de verschillende concepten waarover gesproken wordt en feitelijk over hoe het werkt in de zorg. Alleen als dat
helder is kunnen eenduidige besluiten genomen worden over de modellering. Er werd een oproep gedaan om te kijken hoe
zorgverleners bij deze sessies of mogelijk op een andere manier betrokken kunnen worden. En of er niet steviger ingezet
moet worden op betekenismodellering zoals eerder in de zibtransitie besproken.

De bijeenkomst werd tegen 14:30 uur afgerond door Dave met de conclusie die door iedereen onderschreven werd dat het
weer een bijzonder nuttige en leerzame sessie was. De volgende werksessie is op donderdag 15 mei 2025 bij Nictiz.