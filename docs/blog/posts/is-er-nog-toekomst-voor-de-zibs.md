---
title: Is er nog toekomst voor de zibs?
date: 2023-06-30
authors:
  - gerdameijboom
slug: is-er-nog-toekomst-voor-de-zibs
description: >
  OpenEHR, FHIR en ontologieën spelen steeds belangrijkere rol in het digitaal uitwisselen van gezondheidsgegevens
categories:
  - Algemeen
---

# Is er nog toekomst voor de zibs?

Waarom zouden we nog zibs gebruiken? We hebben nu toch OpenEHR? En waarom gebruiken we geen ontologie, zoals men
momenteel in de verpleeghuiszorg beproeft? Het zijn vragen die ons vaak gesteld worden. Er is een brede discussie gaande
over de rol van verschillende standaarden: OpenEHR, FHIR, ontologieën en zibs. Bijvoorbeeld op de laatste HIMMS-
congressen en in de zib-transitie. Waar zijn die standaarden eigenlijk voor en hebben we ze allemaal wel nodig? Kunnen
we er niet eentje kiezen en daarmee alle uitwisselingsproblematiek wegnemen?

<!-- more -->

## Verschillen tussen standaarden

Het antwoord op die laatste vraag is helaas: 'nee'. Als je goed kijkt naar de verschillende standaarden zie je dat elke
standaard zijn eigen doel heeft en een eigen uitwerking om dat doel te bereiken. Zo is [OpenEHR](
https://www.openehr.org/about/what_is_openehr){: target="_blank" }  goed in het vastleggen van gegevens in een EPD,
liefst opgeslagen in een uniform datamodel. Daarbij biedt het handige tools voor leveranciers om snelle implementatie
mogelijk te maken. Wie wil dat nou niet? De grote zorg-ICT-systemen in Nederland zijn echter nog niet ingericht op basis
van OpenEHR, dus het zal nog even duren voordat we hiervan de voordelen kunnen benutten. Daarnaast zien we ontologieën
en FHIR. Voor het uitwisselen van gegevens tussen systemen maken beiden gebruik van resources, kleine setjes van bij
elkaar horende gegevens. FHIR is specifiek ontwikkeld voor uitwisseling in de zorg en beslaat een groot aantal klinische
domeinen. FHIR wordt steeds meer gebruikt door zorg-ICT-leveranciers, soms ook in combinatie met OpenEHR.

Een ontologie, een van de technieken uit de wereld van het Semantic Web, is een model waarmee een computerleesbare
beschrijving van de werkelijkheid wordt gegeven. Er is een brede variëteit aan ontologieën. Die zijn niet per definitie
zorgspecifiek maar zijn uit te werken voor allerlei domeinen, ook binnen de zorg. In de zorg wordt bij het verkrijgen
van verpleegkundige indicatoren gewerkt met een ontologie (KIK-V). Een andere vorm van een ontologie is SNOMED, een
ontologie die steeds meer wordt gebruikt.

## Vastleggen versus uitwisselen

Het onderscheid tussen vastleggen en uitwisselen is belangrijk. Beide activiteiten hebben eigen usecases en stellen
andere eisen aan systemen. Vastleggen van gegevens vindt plaats in het primaire proces bijvoorbeeld tijdens een
contactmoment of bij de vastlegging van de resultaten van een onderzoek. Zowel de user interface als de opslag van
gegevens in applicaties bij vastleggen is gericht op het gebruik van gegevens in het primaire proces.

Uitwisseling van gegevens gebeurt met een ander doel en tussen personen met een andere verantwoordelijkheid voor die
gegevens. Kijk bijvoorbeeld naar het doel bij uitwisseling tussen zorgverleners. Daar gaat het meestal niet om alle
gegevens van één consult maar om bijvoorbeeld een samenvatting van de medische voorgeschiedenis of om een lijst met
diagnoses. Applicaties die gegevens uitwisselen worden zo flexibel mogelijk ingericht om aan allerlei verschillende
informatiebehoeften te kunnen voldoen. Ook als die niet op voorhand bekend is. Dit vraagt om een andere techniek bij
uitwisselen dan bij het registreren van gegevens. Om die flexibiliteit mogelijk te maken, werkt Nictiz aan een
[API-strategie](https://developer.zorgapis.nl/){: target="_blank" }.

Uitwisselen en vastleggen vragen dus om een andere techniek. Dat is ook belangrijk bij het kiezen van een standaard.
OpenEHR is het meest geschikt voor registratie. Voor het beschikbaar stellen van gegevens zijn de resources van FHIR en
Semantic Web het meest geschikt. Met FHIR kun je overigens wel de opslag vormgeven. En het uniforme datamodel van
OpenEHR, als dat gebruikt is, maakt het gemakkelijker om uit te wisselen. Beide standaarden maken hierin andere keuzes
en hebben andere prioriteiten. OpenEHR vertaalt zich ook niet een-op-een naar FHIR en andersom. Systemen die bedoeld
zijn om uit te wisselen tussen partijen kunnen daarom beter kiezen voor resources terwijl systemen bedoelt voor
registratie OpenEHR kunnen gebruiken. Het beste is om meerdere standaarden naast elkaar te gebruiken: allen voor het
doel waarvoor ze het meest geschikt zijn.

## En zibs dan?

'Dan zijn we er toch?', zou je denken. Maar ook verbindende bouwstenen zijn nog hard nodig.
Zorginformatiebouwstenen (zibs) vervullen deze rol. Niet om mee te registreren, niet om mee uit te wisselen maar om te
zorgen dat registratie en uitwisseling verbonden blijven. Het zijn usecase-, functie- en techniekonafhankelijke
bouwstenen. Die zorgen ervoor dat vastgelegde gegevens ook met dezelfde betekenis en context worden uitgewisseld en
aankomen bij een andere zorgverlener of de patiënt. We stellen ons ook de vraag of internationale standaarden, zoals
archetypes uit OpenEHR of onderdelen van Semantic web de gewenste rol van zibs zouden kunnen invullen.

Betekenis, het begrijpen van elkaars taal is zeer belangrijk, zeker als meerdere partijen gebruikmaken van dezelfde
gegevens. De huidige zibs houden onvoldoende rekening met die verschillen in betekenis. Die verschillen moeten daarom
worden uitgewerkt in een betekenismodel. Daarmee kunnen we het gesprek met de zorgverleners in hun eigen taal beter
voeren en krijgen we helder hoe die verschillen in applicaties uitpakken. Zodra dat goed is ingeregeld, merkt een
zorgverlener of patiënt nog steeds niks van zibs maar garanderen deze wel interoperabiliteit en databeschikbaarheid.

## Het vervolg

Binnen de zib-transitie werken we samen met meerdere partijen aan het verbeteren van toepassing en gebruik van zibs.
Onder andere om te zorgen dat uitwisseling en registratie verbonden blijven en om hergebruik van data te bevorderen,
zowel primair als secundair. Ook houden we oog voor de aansluiting op internationale standaarden, maar we blijven ook
kritisch de genoemde noodzaak van zibs als verbindende factor beoordelen.

Geen enkele van de genoemde standaarden kan in zijn eentje alle problematiek rond uitwisseling of registratie invullen.
We moeten ons ervan bewust zijn dat er in ieder geval drie verschillende standaarden nodig zijn: een voor uitwisseling
(resources over FHIR) en een voor vastlegging (openEHR). Met daartussen een verbindende factor (zibs). Een heldere
rolverdeling tussen standaarden is dan ook belangrijk. Ook internationaal valt daar nog het nodige werk te verrichten.
Ook daar is een gesprek nodig over het onderscheiden van standaarden voor registratie en uitwisseling en  zibs. Nictiz
pakt deze handschoen op in de zib-transitie en gaat daarvoor in gesprek met de betrokkenen bij de verschillende
standaarden.

Nictiz heeft een verkenning gedaan naar diverse informatiemodelstandaarden, zoals OpenEHR, FHIR en Semantic web, maar
ook OMOP en ContSys. Binnenkort publiceren we deze verkenning en een uitgebreid advies dat het hierboven gewenste
scenario beschrijft. Houdt daarvoor onze website in de gaten.