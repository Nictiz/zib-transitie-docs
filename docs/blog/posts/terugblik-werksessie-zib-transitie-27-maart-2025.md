---
title: Terugblik op de werksessie rondom de zib-transitie van 27 maart 2025
date: 2025-04-03
authors:
  - arjanvanbremen
slug: terugblik-werksessie-zib-transitie-27-maart-2025
categories:
  - Terugblik
---

# Terugblik op de werksessie rondom de zib-transitie van 27 maart 2025

De elfde werksessie van de zib-transitie vond plaats op donderdag 27 maart 2025 bij Nictiz. De meeste deelnemers waren
fysiek aanwezig en een aantal online. De bijeenkomst werd geopend door Dave met een update over een aantal zaken. De
rest van de dag was gericht op het beproeven en ervaring opdoen in het modelleren van zibs, archetypes en FHIR-profielen
in hun samenhang. Voor de lunch werd een aantal korte presentaties gehouden rond modellering. Na de lunch gingen de
deelnemers actief aan de slag in een hands-on werksessie.

<!-- more -->

Tijdens de opening gaf Dave een update over het Plan van Aanpak dat wordt opgesteld naar aanleiding van de reactie van
VWS op het Architectuur-advies. De zib-transitie gaat een nieuwe fase in: realisatie. De intentie is om de "inclusieve
werkwijze" met de (zib-transitie) community voort te zetten en de belangrijkste thema's een goede, structurele plek te
geven in de manier van werken en organisatie van Nictiz. De volgende thema's dienen daarin te worden overgenomen:
innoveren van en met zibs (zibs2.0), geheel van afspraken, richtlijnen, documentatie met stakeholders
(gereedschapskist), flexibilisering zibreleases, co-creatie methodieken (living lab, designathons), eenduidige
registratie en meervoudig gebruik stimuleren, betrekken van zib-transitie en andere communities, architectuurkaders.
Daarnaast moet er focus zijn op de verbinding met kernconcepten EHDS. Verder meldde Dave dat inzichten over
databeschikbaarheid die zijn opgedaan aan de hand van werksessies rond de Zorgviewer (RIVO Noord) op basis van het
implementatiemodel verder worden uitgewerkt. Het document waarin dit beschreven staat zal worden gedeeld met de
community.

De presentaties voor de lunch werden afgetrapt door Igor Schoonbrood (MUMC+). Hij vertelde over de bevindingen van de
IBD Hackathon die in juni van 2024 bij het MUMC+ plaatsvond met diverse deelnemers. Er is een uitgebreid rapport
gepubliceerd met de gebruikte methode en de resultaten. De rapportage van de Hackathon is overhandigd aan het ministerie
van VWS. Daarnaast ging Igor in op diverse internationale ontwikkelingen op het gebied van open standaarden op het
gebied van zorg en gezondheid zoals openEHR, FHIR en OMOP met diversen betrokken organisaties die daarop samenwerken
zoals openEHR, HL7, OHDSI, SNOMED, IEEE802 en IHE. In die context worden meer hackathons uitgevoerd. 

Astrid van Ginniken (Nictiz) ging daarna in op het modelleren van een informatiebehoefte naar zibs. Als voorbeeld
gebruikte ze de zib Overgevoeligheid. Na een analyse van de informatiebehoefte wordt een voorstel zib gemaakt.
Vervolgens liep ze langs een aantal punten die bij de evaluatie van belang zijn. Ten eerste: sluiten de elementen en de
kardinaliteit van de zib goed aan bij de informatiebehoefte? Ten tweede: is het een zib in de zuivere zin? Voldoet het
informatiemodel aan de principes van een zib? De belangrijkste principes zijn: één concept per zib, dataelementen zijn
eigenschappen van het rootconcept, (vooralsnog) conceptuele kardinaliteit. Bij die evaluatie van het voorbeeld blijkt
dat de zib Overgevoeligheid daar niet aan voldoet, de zib bevat meerdere concepten. Dat is de reden geweest om die zib
te splitsen in de zib OvergevoeligheidIntolerantie en de zib BewakingsBesluit.

Wouter Zanen (in zijn rol als bestuursvoorzitter openEHR Nederland) gaf een introductie in openEHR. Als eerste noemde
hij de uitspraak van Rachel Dunscombe (CEO openEHR): Data is for life not just for one system. En dat stelt specifieke
eisen aan de manier waarop data worden vastgelegd en beschikbaar worden gesteld. Wouter lichtte de achtergrond van
openEHR als internationale community toe en liet zien waar alle relevante informatie te vinden is. Vervolgens legde hij
uit dat er sprake is van multi-level modelling(reference model – archetypes – templates) waarbij domein experts in hun
eigen technische (IT) of klinische domein werken. Archetypes vormen de basis voor hergebruik in verschillende casussen
op basis van verschillende templates. Er is uitgebreide tooling beschikbaar om de modellering te ondersteunen.

Als laatste spreker voor de lunch ging Pieter Edelman (Nictiz) in op FHIR profiling. Uitgangspunt daarbij is dat alle
data gemodelleerd worden in een beperkte set universele resources (er zijn ongeveer 120-130 resources beschikbaar voor
medische toepassingen). Deze resources vertegenwoordigen een event of een request. Bijvoorbeeld [Observation](
https://www.hl7.org/fhir/R4/observation.html) (lengte, sociale anamnese, ziektebeleving, etc.), [Condition](
https://www.hl7.org/fhir/R4/condition.html) (longemfyseem, gebroken been, zwangerschap, etc.), [AllergyIntolerance](
https://www.hl7.org/fhir/R4/allergyintolerance.html) (specifieker dan Condition), [Patient](
https://www.hl7.org/fhir/R4/patient.html). Daarbij zorgen SNOMED/LOINC etc. voor duiding. Verder geldt de 80/20-regel en
is er een extensie-mechanisme voor randgevallen (waarmee uitbereidingen gemaakt kunnen worden). Voor specifieke
toepassingen van een resource zijn afspraken nodig rond te gebruiken terminologie, kardinaliteiten, constraints etc die
worden vastgelegd in profielen. Pieter legt uit hoe je een profiel maakt (zoek of er al iets bestaat, zo nee, zoek een
resource die semantisch overeenkomt met de zib, maak het profiel m.b.v. beschikbare tooling (constraints, waardelijsten,
omschrijvingen etc). De ervaring leert dat je daarbij tegen diversen knelpunten aanloopt waar voorbeelden van werden
gegeven.

Na de lunch is het tijd voor het hands-on onderdeel, het modelleren van een openEHR Template en een FHIR profiel voor de
zib BehandelAanwijzing2. De deelnemers gingen daar in 4 groepen mee aan de slag. Twee groepen werkten onder begeleiding
van Wouter Zanen aan het maken van een openEHR template. Daarbij maakte ze gebruik van de openEHR Archetype Designer.
Twee andere groepen werkten onder begeleiding van Pieter Edelman en Ardon Toonstra aan een FHIR profiel. Daarbij maakten
ze gebruik van Simplifier en de tool Forge voor R4.

In de praktijk blijken beide opdrachten nog niet zo simpel te realiseren. Dat leidde dan ook tot levendige discussies en
interessante ervaringen en inzichten. Een voorbeeld daarvan: de eerste uitdaging is om het juiste openEHR archetype en
FHIR resource te kiezen. Verder blijkt bij het beschikbare archetype een fundamenteel andere keuze te zijn gemaakt
t.o.v. van de zib doordat het archetype een model is dat ruimte biedt aan een verzameling behandelaanwijzingen die op
een bepaald moment bij een patient horen, terwijl bij de zib daarvoor meerdere instantiaties nodig zijn (één
behandelaanwijzing per instantiatie). En bij het uitwerken van het FHIR profiel bleek dat er meerdere (3) extensies
(aanvullingen op de bestaande resource) nodig zijn om de juiste mapping te kunnen maken, waarvan één "modifier
extension": een extensie die de semantiek van de resource verandert. De tijd was (veel) te kort om alles volledig uit te
werken, maar alle deelnemers waren het erover eens dat het al met al een zeer interessante en leerzame werksessie was.

De bijeenkomst werd plenair afgerond door Dave. De volgende sessie is op dinsdag 15 april 2025 bij Nictiz, waarin hier
een vervolg aan wordt gegeven.