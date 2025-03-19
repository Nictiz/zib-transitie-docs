---
title: Terugblik op de werksessie rondom de zib-transitie van 20 februari 2025
date: 2025-02-27
authors:
  - arjanvanbremen
slug: terugblik-werksessie-zib-transitie-20-februari-2025
categories:
  - Terugblik
---

# Terugblik op de werksessie rondom de zib-transitie van 20 februari 2025

De tiende werksessie van de zib-transitie vond plaats op 20 februari 2025 bij Nictiz. De meeste deelnemers waren fysiek
aanwezig en een aantal online. De bijeenkomst werd geopend door Dave met een update over een aantal zaken. Vervolgens
was er een plenaire sessie waarin Egbert van Gelder zijn overwegingen over (conceptuele) informatiemodellen en zibs met
ons deelde. Daarna was er een werksessie over het concept document *Architectuur zibs 2.0* o.l.v. Gerda en Wouter. Na de
lunch gaf Gé een terugkoppeling van het werkbezoek aan RIVO Noord en de Zorgviewer en was er een discussie over wat je
van zo'n praktijkimplementatie kunt leren in het kader van databeschikbaarheid. De laatste werksessie van de dag was een
oefening rond de totstandkoming van zibs 2.0 door Gerda en Wouter.

<!-- more -->

Tijdens de opening gaf Dave een update over de status van het architectuur-advies dat aangeboden is aan VWS. Inmiddels
is er een eerste terugkoppeling van VWS waaruit blijkt dat VWS voornemens is om het advies over te nemen. Daarbij wordt
wel gevraagd om een concreet plan van aanpak dat beschrijft hoe de resultaten bereikt worden, m.n. op de onderwerpen
transitie naar zibs 2.0 met de prioritering van concepten die aansluiten bij de EPS, flexibeler publiceren van zibs in
relatie tot het tijdslijn/baseline advies en de gereedschapskist voor het oplossen van knelpunten bij de implementatie
van zibs. Aan dat plan wordt nu gewerkt. De volgende werksessie verwachten we daar meer over te kunnen delen. Ook ging
Dave nog kort in op de nieuwe fase van de zib-transitie waarin activiteiten zoveel mogelijk belegd gaan worden in de
staande organisatie en werkwijze van Nictiz. Hoe dat precies vormt krijgt, zal in de komende periode blijken. In ieder
geval is er nog een volgende werksessie gepland bij Nictiz op donderdag 27 maart. Het voornemen is dat dat een hands-on
modelleersessie (zibs, openEHR archetype, FHIR resource) wordt.

Egbert van Gelder nam daarna de aanwezigen mee in zijn overwegingen rond (conceptuele) informatiemodellen en zibs. Zijn
constatering is dat we binnen de zib-transitie op meerdere plekken spreken over informatiemodellen en dat we daar niet
altijd hetzelfde mee lijken te bedoelen. Dat maakt het volgens hem ingewikkeld. Zo kun je een informatiemodel 'zien op
zib(CIM)-niveau' maar ook een informatiemodel dat 'overkoepelend is voor de combinatie van alle zibs (CIMS)'. En dat
laatste ontbreekt. Daardoor is er volgens Egbert de kans dat op zib niveau overlappende delen zijn, hetgeen kan leiden
tot conflicten bij implementatie. Ook worden niet alle relaties die er kunnen bestaan tussen entiteiten in de
afzonderlijke zibs gemodelleerd. Er ontstaat een levendige discussie naar aanleiding van zijn inbreng. Zo worden de
genoemde knelpunten in de meeste reacties uit de groep herkend en wordt het nut van een achterliggend overall
informatiemodel door de meeste aanwezigen onderschreven. Wel zijn er verschillende ideeën over mogelijke oplossingen
hiervoor en over hoe daar te komen. De meeste aanwezigen onderschrijven dat het beter is een dergelijk model geleidelijk
aan te laten ontstaan en niet op voorhand helemaal op papier proberen uit te werken. Een verbetering zou ook kunnen
komen uit het strakker vasthouden aan de ontwerpregels voor zibs (zoals het feit dat er geen overlap moet zijn tussen
zibs) en de praktische uitwerking van zibs2.0. Over verdere opvolging zal worden nagedacht in het transitieteam.

Het volgende onderdeel was een werksessie rond het concept document "Architectuur zibs 2.0" versie 0.8. Dat document is
in de week voorafgaand aan de werksessie door Gerda met de community gedeeld. In dit document worden de
architectuurprincipes voor de zibs 2.0 beschreven:

- P1. Een zib is een afgesproken herbruikbaar logisch formeel model.
- P2. Een zib is een model voor informatie waaraan behoefte bestaat binnen het zorg- en gezondheidsdomein.
- P3. Een zib is gebaseerd op een zorg of gezondheid gerelateerd concept.
- P4. Een zib is ontworpen op basis van beschikbare patronen en spelregels.
- P5. Zibs worden toegepast in uitwisselings- én verwerkingsspecificaties.
- P6. Een zib kan uitgedrukt worden in een gekozen specifiek technologieformaat.
- P7. Een zib wordt landelijk beheerd.

Elk van deze principes kent weer een aantal sub-principes. Deze (sub-)principes zijn al meerdere keren aan de orde
geweest in de werksessies van de community. De huidige versie van het document is tot stand gekomen in een sub-werkgroep
met deelnemers van de community. Dank aan Lonneke, Michael, Gerard, Igor, Tom, Wouter en Gerda voor hun voorbereidende
werk.

Tijdens de werksessie is het document uitgeprint op posters aan de wand gehangen. Vervolgens is aan de deelnemers
individueel gevraagd om één post-it met een + (plus-teken) te plakken bij het (sub)principe dat heel goed/belangrijk is.
En maximaal twee post-its met een – (min-teken) en bijbehorende argumentatie bij (sub-)principes die nog aanscherping
behoeven/onduidelijk zijn of zelfs onjuist etc. Als afronding is Wouter langs alle principes gelopen en heeft kort de
opmerkingen op de post-its benoemd en becommentarieerd. De resultaten zullen worden meegenomen bij het definitief maken
van het document. De aanwezigen stemden in met het gebruik van deze versie als vertrekpunt voor de ontwikkeling van
zibs2.0. Ervaringen uit de ontwikkeling van zibs2.0 worden, waar nodig, in de loop van de tijd aan het document
toegevoegd.

Aan het begin van de middag heeft Gé een terugkoppeling gegeven van een werkbezoek dat in december 2024 geweest is aan
RIVO Noord (UMCG) betreffende de zorgviewer. In het kader van de zib-transitie is het van groot belang om inzicht te
hebben in de praktische knelpunten die opkomen bij de implementatie van oplossingen voor hergebruik van informatie op
basis van zibs. Als hulpmiddel daarbij is het implementatiemodel ontwikkeld. Tijdens het bezoek aan RIVO Noord is de
implementatie van de zorgviewer en de geplande doorontwikkeling gemapt op het implementatiemodel waarbij de ervaren
knelpunten benoemd zijn. Ook is tijdens het bezoek uitgebreid gesproken met twee zorgprofessionals uit het UMCG die de
zorgviewer daadwerkelijk gebruiken. Die discussie leverde interessante inzichten op. Dat geldt ook voor de
praktijkervaringen op het gebied van lab-uitwisseling die besproken zijn met een vertegenwoordiger van het
UMCG-laboratorium.

De zorgviewer is een van de initiatieven die een vorm van databeschikbaarheid realiseren. In de praktijk blijken daar
toch de nodige knelpunten op te komen, met name als het gaat om opschaling. Zo is het zo dat voor de
gegevensuitwisseling tussen de systemen in de context van de zorgviewer (dat wil zeggen de zorgviewer applicatie
enerzijds en de betrokken bronsystemen anderzijds) gebruik wordt gemaakt van FHIR API's die specifiek zijn per systeem.
In een relatief beperkte (regionale) setting kan dat werken, maar het staat bredere (landelijke) opschaling in de weg.
Een belangrijk inzicht uit de discussie met de zorgprofessionals van het UMCG is dat de opvragende gebruiker bepaalt
welke informatie essentieel is. Ook de vorm waarin deze informatie beschikbaar komt, ligt bij de gebruiker. Dit soort
inzichten leidt tot de vraag of we wel scherp hebben wat databeschikbaarheid eigenlijk inhoudt en wat ervoor geregeld
moet worden om het landelijk te realiseren. Om die vraag te adresseren is het concept van databeschikbaarheid
gemodelleerd op de zeven stappen van het implementatiemodel. Die zeven stappen zijn afzonderlijk uitgeprint op posters
en de deelnemers is gevraagd om in groepjes voor elk van de stappen een aantal vragen te adresseren: wat zou er voor die
stap geregeld moeten worden, hoe kan dat gedocumenteerd worden, wie moet dat regelen en hoe krijgen we het
geïmplementeerd. Er ontstond een interessante discussie maar het bleek ook dat er meer tijd nodig is om dit goed uit te
werken. Wel gaven deelnemers aan dat het een interessante manier is om te kijken naar databeschikbaarheid en een
aanvulling kan zijn op andere initiatieven. Wordt vervolgd.

De laatste werksessie van de dag was een vingeroefening rond de totstandkoming van zibs 2.0. De opzet was om voor een
bestaande zib (Vaccinatie) te kijken in hoeverre de eerder besproken (sub)principes toetsbaar zijn, zo ja hoe en in
welke mate de specifieke zib daaraan voldoet. De deelnemers werden in driegroepen verdeeld en elk van de groepen kreeg
een aantal (sub)principes toegewezen met de vraag die uit te werken. Na afloop werden de resultaten per groep kort
gedeeld. Ze zullen gebruikt worden voor de verdere uitwerking.

De werksessie werd plenair afgerond door Dave. De volgende sessie is op 27 maart 2025.