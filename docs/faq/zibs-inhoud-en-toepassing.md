# Zibs - Inhoud en toepassing

## Zibs zijn techniek-onafhankelijk; wat betekent dat?

Zibs beschrijven de informatie die bij een bepaald (klinisch) concept hoort. Dit gebeurt met zorgvuldig gedefinieerde
termen die zoveel mogelijk herkenbaar zijn voor zorgverleners en patiënten. Een belangrijk onderdeel van een zib is het
informatiemodel. Op het moment dat je de informatie uit het model gedigitaliseerd wilt opslaan, verwerken, gebruiken,
overdragen, etc., moet je technische keuzes maken. Bijvoorbeeld: technische keuzes in het EPD, keuzes in het technische
formaat van overdracht, etc. De betekenis van de klinische concepten van de zibs moet echter binnen elke technische
keuze dezelfde zijn. We zeggen dan ook dat zibs onafhankelijk zijn van de techniek.

## Zibs zijn situatie-onafhankelijk; wat betekent dat?

Zibs beschrijven de informatie, die bij een bepaald (klinisch) concept hoort, zoveel mogelijk in herkenbare termen van
de zorgverleners en de patiënten. Een belangrijk principe achter de zibs is dat de informatie die bij het klinische
concept van de zibs hoort, in meerdere situaties dezelfde betekenis heeft. Bijvoorbeeld: de gegevens over het
lichaamsgewicht van de patiënt (aantal kilo's, hoe het is gemeten en door wie, etc.) weerspiegelt dezelfde informatie
tijdens een poliklinisch consult als tijdens een opname op een klinische afdeling. We zeggen dan dat de zib
'Lichaamsgewicht' situatieonafhankelijk is.

## Moet 'overal' een zib voor zijn?

Nee. Niet elk gegevenselement (van een gegevensset) hoeft te worden afgedekt door een zib. Bepalend is of een
gegevenselement alleen in een specifieke toepassing wordt gebruikt of dat er sprake is van (potentieel) meervoudig
gebruik van dit gegevenselement in meerdere toepassingen. Om antwoord te geven op deze vraag is een document opgesteld
de '[Richtlijnen bij afwezigheid zibs](
https://nictiz.nl/app/uploads/2022/05/Richtlijnen_bij_afwezigheid_zibs_V1_00-1.pdf){: target="_blank" }'.

## Hoeveel zibs zullen er in totaal nodig zijn?

Een concreet aantal te verwachten zibs is niet te noemen. Op dit moment zijn er rond de honderd ibs gepubliceerd. Omdat
(nog) niet voor alle klinische concepten zibs beschikbaar zijn, groeit het aantal zibs naar verwachting nog. Het totale
aantal zorgbrede zibs op termijn, is lastig te voorspellen. Het uiteindelijke aantal ontwikkelde zibs zal zeker niet
meer dan duizend zijn.

## Wat is de Basisgegevensset Zorg (BgZ)?

De Basisgegevensset Zorg (BgZ) is een gedefinieerde gegevensset van patiënt gerelateerde (medische) gegevens waarvan
door zorgverleners is bepaald dat die specialisme, ziektebeeld en beroepsgroep overstijgend relevant is en van belang
voor de continuïteit van zorg. De BgZ is gebaseerd op de zibs.

## Elke zib (tot aan Publicatie2017) bevat zogenaamde basiselementen. Wat zijn dat?

Alle zibs bevatten impliciet een aantal basiselementen. Deze basiselementen zijn in de informatiemodellen van de
afzonderlijke bouwstenen in de meeste gevallen niet opgenomen, maar worden wel verondersteld aanwezig te zijn. Het
betreft concepten die meer technisch van aard zijn. De concepten hebben vaak geen of weinig klinische relevantie, maar
voor de eenduidigheid en de herleidbaarheid van de gegevens zijn ze wel noodzakelijk. In de gevallen waarin deze
elementen wél een klinische betekenis hebben, zijn ze meestal wel expliciet in de bouwsteenmodellen zichtbaar.

## Wordt SNOMED CT gebruikt in de zibs?

[SNOMED CT](https://nictiz.nl/wat-we-doen/activiteiten/terminologie/snomed/){: target="_blank" } is een internationaal,
medisch terminologiestelsel. In SNOMED CT vind je veel (medische) termen met hun synoniemen, en de verbanden tussen deze
termen. In de zibs wordt veel gebruik gemaakt van SNOMED CT. Bij gegevenselementen van een zib wordt vaak gebruik
gemaakt van SNOMED CT om de betekenis te beschrijven van zo'n gegevenselement. Daarnaast vind je SNOMED CT in de zibs
terug bij een waardenlijst bij een gegevenselement: om de betekenis van de elementen in een waardenlijst te bepalen
wordt dan verwezen naar SNOMED CT.

## Wat is een zib-blauwdruk zib (of een blauwdruk-zib)?

Zib-blauwdruks zijn constructies 'achter de schermen' die de consistentie van zibs moeten bevorderen en de implementatie
van zibs faciliteren.

Een zib-blauwdruk is in feite een sjabloon voor een groep van zibs die veel gemeenschappelijke dataelementen hebben. Het
is voor de consistentie en voor de implementatie wenselijk om de individuele zibs binnen zo'n groep volgens een vaste
structuur te definiëren. Dit heeft de volgende voordelen:

- Het consequent en systematisch ontwerpen van individuele zibs volgens het sjabloon. Er ontstaat geen onnodige variatie
  in structuur en naamgeving. Ook is de kans kleiner dat data-elementen over het hoofd worden gezien.
- Zibs met veel overeenkomsten zijn zo ook efficiënt en consequent te reviewen.
- Een leverancier kan zijn implementatie baseren op de structuur van de zib-blauwdruk (het sjabloon). Dit betekent
  minder ontwikkelinspanning en grotere betrouwbaarheid bij implementatie van de van het sjabloon afgeleide zibs door de
  leverancier.

## Wat is de relatie tussen de zibs en de informatiestandaarden?

Een [informatiestandaard](https://nictiz.nl/standaarden/informatiestandaarden/){: target="_blank" } is een verzameling
afspraken voor een bepaald zorgproces. Die verzameling afspraken moet ervoor zorgen dat de informatie die van belang is
bij dat zorgproces, met de juiste kwaliteit kan worden vastgelegd, opgevraagd, gedeeld, uitgewisseld en overgedragen.
Binnen een informatiestandaard wordt aan de hand van een gegevensset afgesproken welke gegevenselementen relevant zijn
voor de betreffende informatiestandaard. Bij het samenstellen van de gegevensset worden de elementen waar mogelijk
gerepresenteerd door zibs. Daarnaast kunnen extra gegevens worden toegevoegd die alleen voor een specifiek zorgproces
gelden en niet zorgbreed zijn. Informatiestandaarden combineren dus zorgbrede gegevens (op basis van zibs) met losse,
specifieke gegevens voor een bepaald zorgproces.

## Zijn de zibs zorgbreed toepasbaar?

Ja, de zibs zijn zorgbreed van aard geformuleerd. Elke zib beschrijft een (klinisch) concept, dat meerdere gegevens in
zich herbergt met een afgesproken inhoud, structuur en onderlinge relaties. De zibs zijn daardoor in de aard zorgbreed.
Neem bijvoorbeeld de zib AllergieIntollerantie, die de allergieën van de patiënt beschrijft. De informatie over de
allergieën van een patiënt is onafhankelijk van de sector of setting waarin de patiënt op dat moment zorg ontvangt.

!!! note

    Wanneer een zib nog niet in alle zorgsectoren toepasbaar blijkt, is het mogelijk om wijzigingen of aanvullingen voor
    te stellen.

## Beschrijft een zib ook de selectie van gegevens voor de vulling?

Nee. Het belangrijkste onderdeel van een zib is – naast de tekstuele definitie – het informatiemodel. Het
informatiemodel van een zib beschrijft welke gegevenselementen bij het concept horen, wat ze betekenen en hoe ze zich
tot elkaar verhouden. Bijvoorbeeld, de zib LabUitslag bevat gegevenselementen over de laboratoriumbepaling, de uitslag,
de meeteenheid, het soort monster, etc. Pas bij de afspraken over een informatiestandaard waarbinnen een zib als
LabUitslag wordt gebruikt, worden afspraken gemaakt over welke Labuitslagen tot de gegevensset van de
Informatiestandaard behoort (bijvoorbeeld: zijn dat alle of alleen de laatste?). Een zib beschrijft dus het
informatiemodel van 'LabUitslag' maar niet welke laboratoriumuitslagen erin voor moeten komen want dat is de
inhoud/vulling. Dat is immers afhankelijk van de toepassing en implementatie.

## Waarom zit er in zib A wel een verwijzing naar zorgverlener en in zib B niet?

Als algemene regel bevat een zib een verwijzing als deze relevant is voor het rootconcept.

Er zijn zibs die niet op zichzelf staan en waarnaar alleen verwezen wordt vanuit een andere zib. In zo'n situatie kan
het zijn dat de zorgverlener wel relevant is voor het rootconcept van zib A, maar bij een verwijzing naar zib B niet
meer gespecificeerd hoeft te worden in zib B.

De zib MedicatieAfpsraak heeft een verwijzing naar Zorgverlener, omdat het relevant is welke zorgverlener de
voorschrijver is. De zib Gebruiksinstructie staat niet op zichzelf. Een instance van gebruiksinstructie hoort altijd bij
een bepaalde instance van een medicatiefaspraak. De zorgverlener van de medicatieafspraak geldt daarmee ook voor de
gebruiksinstructie.

## Waarom zit patiënt (als verwijzing) niet in alle zibs?

In principe heeft elke zib betrekking op de patiënt waarover gegevens worden uitgewisseld. Alleen als de patiënt zelf
een actieve rol speelt in de gegevens die worden uitgewisseld en waarbij het relevant is om die rol te specificeren, zal
de zib een verwijzing hebben naar de patiënt.

Bij een MedicatieAfspraak is het niet nodig om een verwijzing naar de patiënt op te nemen. De medicatie is bedoeld voor
de patiënt. Bij een ZorgAfspraak kan de patiënt een rol spelen in het maken van de afspraken en daarnaast kan de patiënt
zelf een rol hebben in het uitvoeren van de afgesproken activiteiten. Daarom is het in de zib ZorgAfspraak van belang om
de rol van de Patiënt als mogelijke deelnemer aan de afspraak en aan de uitvoering daarvan te kunnen specificeren.