# Zibs - Algemeen

## Wat is een zib?

Een Zorginformatiebouwsteen (zib) definieert in detail een (klinisch) concept, dat relevant is in het zorgproces. Zibs
zijn gebaseerd op een internationale standaard (ISO13972). De belangrijkste onderdelen van een zib zijn de concept-
beschrijving en het informatiemodel.

## Waarom zijn er zibs?

Zibs zijn een middel om eenheid van taal te bereiken. En eenheid van taal is noodzakelijk om het doel, namelijk het
hergebruiken van informatie uit het zorgproces te bereiken. Dat hergebruik van informatie kan zijn ten dienste van het
zorgproces zelf, maar ook ten dienste van bijvoorbeeld kwaliteitsverbetering en klinisch onderzoek.

## Is 'zib' een Nederlandse uitvinding?

Nee. De hoofdgedachte achter de zibs – namelijk om de betekenis van (klinische) concepten te beschrijven los van
technische keuzes en los van implementaties – heet internationaal 'clinical modelling'. Deze gedachte heeft
internationaal veel aandacht en vind je onder meer terug in FHIR, Archetypes (OpenEHR), CIMI en Clinical Element Models
van Intermountain Healthcare. Daarnaast gebruiken de zibs een internationaal, gestandaardiseerd format; en zijn zibs
gebaseerd op (voldoen aan) een internationale ISO standaard: ISO13972, Clinical Information Models (CIM's).

## Maken zibs gebruik van bestaande (inter)nationale standaarden?

Jazeker. Je zou kunnen zeggen dat er vrijwel geen zib of onderdeel van een zib bestaat waarbij geen gebruik is gemaakt
van bestaande standaarden. Zo is bij het opstellen van de eerste release van de zibs in 2013 vooral gebruik gemaakt van
HL7 Continuity of Care Record (CCR); een toen veel gebruikte Amerikaanse standaard. N.B. In 2013 bestond HL7 FHIR nog
niet en trok HL7 CCR veel aandacht. Ook wordt bij het opstellen van zibs gebruik gemaakt van bijvoorbeeld OpenEHR, IHE,
HL7, SNOMED CT, maar, indien relevant, ook van bestaande nationale standaarden, zoals NHG-tabellen, G-standaarden etc.

## We hebben HL7 FHIR (resources en profielen), waarom hebben we dan nog zibs nodig?

De resources en profielen van HL7 FHIR beschrijven, net als de zibs, weliswaar conceptueel klinische concepten, maar
zijn gebonden aan een specifiek technisch format voor uitwisseling, namelijk HL7 FHIR. Dat geldt niet voor de zibs: de
zibs zijn techniek onafhankelijk. In de ISO-standaard over de zibs (CIM's), namelijk ISO13972, staat beschreven hoe zibs
zich verhouden tot HL7 FHIR Resources en hoe je komt vanuit een zib tot een Resource in FHIR of een Archetype in
OpenEHR.

## We hebben SNOMED CT, waarom hebben we dan nog zibs nodig?

SNOMED CT is een terminologiestelsel, waarbinnen losse klinische concepten hiërarchisch zijn ingedeeld volgens een
aantal hoofdcategorieën, zoals bijv. Disorder, Finding, Body structure, Procedure, Observable entity. SNOMED beperkt
zich tot de eigenschappen van deze losse concepten op zich en definieert geen informatie modellen die zijn toegesneden
op verzamelingen van losse concepten, die samen een bovenliggend klinisch concept beschrijven. Een van de belangrijkste
elementen in een zib, namelijk het informatiemodel, ontbreekt in SNOMED CT.