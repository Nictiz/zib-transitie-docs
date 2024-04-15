# Zib-transitie

## Waarom een zib-transitie?

Zibs zijn in Nederland zorgbreed de basis voor Eenheid van Taal en Eenheid van Techniek. Ze zijn ontwikkeld om
hergebruik van zorginformatie te kunnen realiseren. Bij de toepassing van zibs in de praktijk blijkt dat daadwerkelijk
hergebruik van informatie ingewikkeld is en achterblijft bij de verwachtingen. Daarvoor zijn diverse oorzaken aan te
wijzen die te maken hebben met de manier waarop zibs in de praktijk worden toegepast en geïmplementeerd. De zib-
transitie is opgezet om die oorzaken aan te pakken.

## Door wie is de zib-transitie geïnitieerd, vanuit welke urgentie en wat gaat er nu niet goed?

In het voorjaar van 2018 zijn zibs door het IB aangewezen als fundamenteel onderdeel van het zorginformatiestelsel. Zibs
worden inmiddels breed toegepast in tal van initiatieven. Waaronder landelijke programma's als BabyConnect, MedMij,
Medicatie Overdracht (MO), eOverdracht en verschillende VIPP-programma's, maar bijvoorbeeld ook op het gebied van
kwaliteitsregistraties, uitkomstgerichte zorg, oncologische netwerken. Met de toepassing van zibs in de praktijk blijken
zich de nodige problemen voor te doen. Daarbij wordt vaak gewezen op een gebrek aan zib-compliance, dat wil zeggen:
processen en systemen voldoen niet aan hoe zibs bedoeld zijn.

Nictiz heeft in het voorjaar van 2022 de [Visie op Zibs](
https://nictiz.nl/publicaties/visie-op-zibs/){: target="_blank" } gepubliceerd waarin we diverse knelpunten en
ontwikkelvragen rond de toepassing van zibs hebben geformuleerd.

Medio 2022 is door Melius Health Informatics (MHI) een onderzoek uitgevoerd in opdracht van het ministerie van VWS naar
de problematiek van zib-compliance. De resultaten die zijn gepubliceerd in [het rapport](
https://www.tweedekamer.nl/kamerstukken/brieven_regering/detail?id=2022Z25274&did=2022D54331){: target="_blank" } *Van
zib-compliance naar hergebruik van zorginformatie* (september 2022), zijn als uitgangspunt genomen voor inhoud en aanpak
van de zib-transitie. Het rapport noemt zeven grondoorzaken voor knelpunten bij het toepassen van zibs in systemen en
processen:

1. *Zibs kunnen moeilijk op grote schaal worden geïmplementeerd in systemen doordat zij onvoldoende samenhangend zijn
  gemodelleerd en ontwerppatronen onvoldoende sterk zijn.* Voorbeelden zijn de introductie van *breaking changes* in
  bestaande versies van zibs, divergente modellering (gelijksoortige concepten worden verschillend gemodelleerd),
  overstructurering (meer structuur dat nodig of wenselijk), onvoldoende modellering van context (in welke situatie
  wordt informatie vastgelegd en door wie) en ontbreken van een *comply-or-explain-regime* ten aanzien van hergebruik
  van internationale standaarden zoals de internationale openEHR clinical models.
2. *Onvoldoende geïntegreerde ontwikkeling van zibs en afgeleide informatiestandaarden.* Voorbeelden zijn het toevoegen
  of verwijderen van data-elementen, toevoegen of verwijderen van waarden in waardenlijsten en aanpassingen van de
  kardinaliteit van data-elementen in specifieke informatiestandaarden. Hoewel hiervoor soms goede redenen zijn, doen
  dit soort aanpassingen de meerwaarde van zibs teniet: generieke datamodellen als basis voor alle
  informatiestandaarden.
3. *Te grote kloof tussen het ontwikkelproces van zibs en de toepassing in systemen en processen, waardoor zibs soms te
  veel van de praktijk van de zorg en van zorg-ICT-systemen afwijken.* Zowel zorgverleners als leveranciers geven aan
  zich te weinig betrokken te voelen bij de ontwikkeling van zibs. Vanuit de zorg geeft men aan dat zibs eerder een
  ideaalbeeld dan een reële weerslag van de zorgpraktijk zijn. Ook zijn zibs vaak te specifiek voor de medisch
  specialistische (ziekenhuis) zorg en worden zij onvoldoende herkend binnen bijvoorbeeld de GGZ en de huisartsenzorg.
  Vanuit de industrie geeft men aan dat zibs vaak te specifiek (zoals bloeddruk) of juist te generiek (zoals probleem)
  zijn om (zonder aanvullende handreiking) goed te worden geïmplementeerd in systemen. Partijen geven aan dat de impact
  van wijzigingen in zibs vaak onvoldoende duidelijk is en dat zij onvoldoende ondersteuning bij het implementeren van
  dit soort wijzigingen ervaren.
4. *Zibs worden nog onvoldoende toegepast in de zorgpraktijk.* Bij uitblijvend gebruik in de zorgpraktijk zal niet
  geleerd worden, worden systemen niet aangepast en worden zibs en gerelateerde informatiestandaarden niet verbeterd.
  Dit is natuurlijk een kip-en-eiprobleem: men wil zibs pas toepassen als ze goed genoeg zijn, maar ze worden alleen
  goed genoeg door te leren van toepassing. Meetbaar maken van registratiekwaliteit en hergebruik kan bijdragen aan het
  leerproces en gebeurt nog onvoldoende.
5. *Een breed gedragen visie op (de route naar) hergebruik van zorginformatie en de rol van zibs daarbij ontbreekt.* Dit
  probleem is voor een belangrijk deel getackeld met de
  [nationale visie en strategie op het gezondheidsinformatiestelsel](
  https://nictiz.nl/wat-we-doen/zorginformatiestelsel/nationale-visie/){: target="_blank" }.
6. *Verwachtingen, doelstellingen en eisen zijn niet SMART.* Wanneer is een systeem zib-compliant? En wanneer een
  proces? Welke eisen stellen we aan registratie en hergebruik?
7. *Er is geen strategie om de impact van terminologische verschillen te beperken.* Eenduidigheid van taal vraagt een
  landelijke aanpak. Op dit moment worden in de Nederlandse zorg veel codestelsels naast elkaar gebruikt. Ook binnen
  gecodeerde data-elementen van zibs worden vaak verschillende codelijsten toegestaan, omdat dit in overeenstemming is
  met de huidige zorgpraktijk. Een actueel voorbeeld is het gebruik van verschillende codestelsels binnen de
  verpleegkunde (zoals *Nanda* en *Omaha*) waardoor eenduidig begrip van gecommuniceerde informatie wordt bemoeilijkt.

## Waarom kiezen we voor een zib-transitie en sluiten we niet aan op andere lopende (inter)nationale initiatieven zoals openEHR of FHIR profiles, waarom zijn deze niet afdoende en is er meer nodig?

De zorginformatiebouwstenen beschrijven de zorginformatie zelf. Los van technologie en standaarden voor opslag (zoals
openEHR) en uitwisseling (zoals FHIR). Dat is wenselijk omdat standaarden voor opslag en uitwisseling een hoge
veranderlijkheid kennen, de adoptie van nieuwe standaarden en technieken geleidelijk verloopt en er daardoor doorgaans
meerdere (versies van) standaarden naast elkaar bestaan. Door afspraken over de inhoud van klinische concepten te maken,
los van hun opslag en hun uitwisseling, kan hetzelfde klinisch concept worden uitgedrukt in verschillende standaarden
voor opslag en uitwisseling. Zo kan een zorginformatiebouwsteen worden uitgedrukt in een openEHR archetype (voor openEHR
compatible opslag van informatie) en een FHIR profile (voor FHIR compatible uitwisseling van informatie) om te borgen
dat informatie die wordt uitgewisseld ook daadwerkelijk wordt opgeslagen.

Bij het ontwikkelen van de zibs is het wel van belang dat deze worden afgestemd op bestaande internationale
initiatieven, zoals de internationale *openEHR knowledge manager* (internationale repository van klinische concepten in
de vorm van openEHR archetypes) en de internationale FHIR-profielen. De zib-transitie ontwikkelt voorstellen om die
afstemming te verbeteren.

## Waarom heet het nu een transitie en niet een programma?

We kiezen voor de term transitie om een bepaalde vorm van sturing te duiden, die afwijkt van meer traditionele
projectplanning. We stellen dat hergebruik van zorginformatie, door meer zib-compliance, een *wicked problem* is:
oplossingen zijn onzeker en kunnen niet worden afgedwongen, omdat er te veel bepalende stakeholders en factoren zijn.
Bij het oplossen van een wicked problem hoort een vorm van sturing waarbij de nadruk meer ligt op het **aanjagen** van
ontwikkelingen, het **verbinden** en **faciliteren** van partijen en **continu bijsturen**, dan op verplichting en
traditionele planning vooraf.'

Omdat we én met veel partijen samen moeten werken, én werkenderwijs complexe oplossingen moeten zien te vinden, stelt
dat hele hoge eisen aan het onderlinge vertrouwen en de bereidwilligheid tot samenwerking. Het 'naar elkaar wijzen' ligt
op de loer, en ook de onzekerheid van consequenties van besluiten maakt het voor alle partijen moeilijk om
verantwoordelijkheid te nemen. Vandaar dat wij de term zib-transitie hebben gekozen, en in een werk-community met de
beste professionals op dit gebied samen de stappen zetten die nodig zijn. Dit doen we op *Agile/Scrum*-achtige wijze als
antwoord op de karakteristiek van een wicked problem. Zie daarvoor onze [Rolling Roadmap](
https://nictiz.nl/publicaties/zib-transitie-doel-aanpak/){: target="_blank" }.

## Hoe passen de zibs in de internationale ontwikkelingen? Maakt dit de koppeling met de EHDS meer evident, eenvoudiger of sneller? Houden de Nederlandse zibs al rekening met bijvoorbeeld de Patient Summary?

De EHDS zal in de toekomst een digitale uitwisseling verlangen van de Patient Summary tussen Europese landen onderling.
Wanneer je op detail- of zib-niveau naar de Patient Summary kijkt, kun je stellen dat deze een zeer grote mate van
overeenkomst vertonen met de zeven geprioriteerde zibs zoals voorgesteld door de FMS (Patient, Diagnose, Verrichtingen,
Behandelaanwijzing, Allergie, Lab Uitslagen en Medicatie).

In het antwoord op vraag 3 betogen we dat zibs zorginformatie modelleren los van specifieke (nationale én
internationale) informatiestandaarden. Harmonisatie van bestaande nationale standaarden en hun implementatie in systemen
met internationale standaarden zoals de EU patient summary, is gemakkelijker wanneer die nationale standaarden zijn
gebaseerd op een consistente set van klinische modellen: de zibs. Immers, door de zibs waar nodig te harmoniseren met de
EU patient summary, kunnen alle van die zibs afgeleide nationale informatiestandaarden eenvoudiger worden
geharmoniseerd.

## Wat moet van deze transitie het resultaat zijn?

Het resultaat **voor de zorg** is dat zibs gemakkelijker kunnen worden gebruikt in zorgprocessen, onder andere (maar
niet uitsluitend) door:

- Eenduidige afspraken in het zorgveld over adequate registratie en adequaat hergebruik, primair en secundair.
- Eisen aan ondersteuning door informatiesystemen.
- Eenheid van Taal: de huisarts en de medisch specialist moeten eenzelfde taalgebruik gaan hanteren, dus dezelfde termen
  en codelijsten met een vastgestelde betekenis.

Het resultaat **voor leveranciers** is dat zorginformatiebouwstenen en de daarvan afgeleide informatiestandaarden
makkelijker kunnen worden ingebouwd in systemen en koppelvlakken, onder andere (maar niet uitsluitend) door:

- Minder divergente modellering.
- Waar nodig het realiseren van betere, vindbare en meer eenduidige documentatie, richtlijnen en handreikingen.
- Het uitbannen van hiaten en tegenstrijdigheden tussen zibs, de van zibs afgeleide informatiestandaarden en
  kwalificatiemechanismen.
- Voorspelbaar en samenhangend releasebeleid.

**Architectuur** verbindt zorg en bouw. Het resultaat van goede architectuur is dat de informatiebehoefte vanuit de zorg
wordt vertaald naar gebruiksvriendelijke systemen. Zorginformatiebouwstenen zijn de verbinding tussen de
informatiebehoefte en de technische implementatie in systemen. Architectuur werkt aan deze verbinding door:

- Versterking van de positionering en rol van zibs in het gezondheidsinformatiestelsel ten opzichte van onder andere
  openEHR, FHIR, informatiestandaarden, API's en ontologieën.
- Consistente uitwerking van onder andere zibs, herbruikbaarheid en relaties tussen zibs. Dit op basis van een
  samenhangende architectuur.
- Bieden van handvatten ter ondersteuning van zorgverleners bij het definiëren van hun informatiebehoefte en wensen ten
  aanzien van gebruikersvriendelijkheid van systemen.
- Maken van afspraken om Eenheid van Taal te borgen in het gezondheidsinformatiestelsel en de zibs in het bijzonder.

## Wanneer zien we hier concreet iets van, wat zijn de eerste resultaten? Hoe merken we dat we voortgang maken in die transitie?

Op korte termijn worden de volgende zaken opgeleverd:

Door de werkgroep **Gebruik**:

- Voorstel over geprioriteerde zeven zibs: Welke als eerste oppakken en waarom? Wat zijn daarvan de consequenties? Wat
  is de relatie tot de European Patient Summary? Inzicht in wat er nodig is om een governance met betrekking tot de zibs
  (vraagstukken) in te richten.
- Een eerste *Living lab* voor de zomer 2023 voor het in de praktijk testen van onder andere in de transitie ontwikkelde
  ideeën, richtlijnen en handreikingen.
- Een werkconferentie over 'adequate registratie' op 15 mei met een groot aantal betrokken partijen. De bedoeling
  hiervan is inzichtelijk te maken welke partij wat kan of moet doen om adequate registratie te bevorderen. Er liggen
  veel goede aanbevelingen, maar wat kunnen we (meer) doen om deze tot realisatie te brengen?

Door de werkgroep **Bouw**:

- Een overzicht van alle onderdelen van het zib-ontwikkelproces waarbinnen afspraken en hulpmiddelen nodig zijn om de
  implementeerbaarheid in systemen en processen te verhogen. Dit wordt de [zib gereedschapskist](
  ../index.md#gereedschapskist).
- Initiële vulling van de gereedschapskist met bestaande afspraken en hulpmiddelen die op voldoende support vanuit de
  community kunnen rekenen.
- Eerste aanvullende eenduidige documentatie, handreikingen en eenduidige richtlijnen ten aanzien van het gebruik van
  terminologie binnen zibs en de consequenties voor systemen en processen.
- Eerste aanvullende eenduidige documentatie ten aanzien van zib-blauwdrukken.

Op basis van ervaren prioriteiten zullen geleidelijk meer concrete onderdelen van de gereedschapskist worden ingevuld.
Daarnaast zal na de zomer aan Nictiz een voorstel worden voorgelegd over het publiceren van de (onderdelen van) de
gereedschapskist en de directe communicatie met de community.

Door de werkgroep **Architectuur**:

- Verkenning standaarden voor informatiemodellen.
- Architectuurdocument met positionering standaarden voor informatiemodellen (zibs, openEHR en Web resources/FHIR
  resources) op een specificatiecanvas, vergelijking van diverse scenario's, advies voor het te volgen scenario en
  duiding van dat advies.
- Betekenismodellen: methodiek en eerste modellen gereed.
- Uitwerking architectuur voor belangrijke knelpunten zoals blauwdruk, kardinaliteit en releasemanagement.
- Plan van aanpak implementatie SNOMED.

## In hoeverre leren we nu al van deze transitie voor het eigen werk van Nictiz in het ontwikkelen en 'saneren' van zibs? Zijn er voorbeelden?

Een aantal specifieke voorbeelden zijn:

- De ontoereikendheid van de huidige documentatie voor leveranciers. Zowel qua inhoud, gebrek aan eenduidigheid als de
  vindbaarheid en (doelgroepspecifieke) toegankelijkheid van informatie.
- Specifieke terreinen waarop nadere specificatie van richtlijnen noodzakelijk is.
- Specifieke terreinen waarop inconsistenties (zijn) ontstaan tussen zibs en afgeleide informatiestandaarden.
- De wijze waarop (voorgestelde) wijzigingen in zibs en informatiestandaarden beter kunnen worden verwerkt, door
  integrale impactanalyse en gericht betrekken van de community.
- De (zorg)praktijk nog beter betrekken bij de ontwikkeling van de zibs.
- Het definiëren van de inhoud van klinische concepten is primair de verantwoordelijkheid van de zorg.

## Richt de zib-transitie zich volledig op een set knelpunten zoals geconstateerd in het zib-compliancerapport of omvat het nog meer?

De zib-transitie neemt de thema's die in het rapport zijn geformuleerd als uitgangspunt maar zal afhankelijk van de
ervaringen die opgedaan worden bijsturen en ook andere zaken oppakken.  Een groot deel van de problemen bevindt zich
niet binnen de *circle of control* (en beperkt binnen de *circle of influence*) van het zib-transitieteam. Het zib-
transitieteam ontwikkelt zelf dan ook geen oplossingen. Het faciliteert een community van betrokken partijen, waaronder
zorgverleners, leveranciers, landelijke programma's en diverse afdelingen van Nictiz, bij het ontwikkelen, testen en
implementeren van oplossingen. Zib-compliance is een zorgbreed probleem dat van alle stakeholders verantwoordelijkheid
en mogelijk parallelle projectvoering vraagt.

Ook de inbreng van lopende initiatieven zoals de diverse implementatieprogramma's kan aanleiding zijn om nieuwe
onderwerpen op te pakken. Iedere eendaagse wordt een landelijk programma uitgenodigd om knelpunten te presenteren en
agenderen. Waar wenselijk maken we met die programma's aanvullende afspraken voor verdere opvolging. Zo heeft een lid
van het transitieteam toegang tot issues die voorkomen uit ketentests van MedMij.  Dit zodat verdere afspraken over
onderlinge samenwerking en versterking kunnen worden gemaakt.

## Welke geconstateerde knelpunten van de zib-compliance (rapport Melius) lossen we nu precies op met deze transitie, en welke niet – kortom wat is de scope?

De thema's uit het rapport van Melius Health Informatics zijn een uitgangspunt voor de zib-transitie. Dit betekent dat
alle knelpunten en grondoorzaken bij die thema's in de scope van de zib-transitie passen. Het zib-transitieteam
ontwikkelt zelf geen oplossingen, maar faciliteert betrokken partijen, waaronder zorgverleners, leveranciers, landelijke
programma's en diverse afdelingen van Nictiz, bij het ontwikkelen, testen en implementeren van oplossingen.

De zib-transitie zoekt hierbij nadrukkelijk de verbinding met andere initiatieven die het gebruik van zibs in systemen
en processen beogen te bevorderen. Denk bijvoorbeeld aan initiatieven in het kader van *MedElkaar* en initiatieven op
het gebied van Eenheid van Taal en terminologiegebruik(kernthema 5 uit het Melius Health Informatics rapport).

## Wat merken we nu al van de zib-transitie? Wat merken de huidige grote landelijke programma's daar nu al van?

In de eendaagse bijeenkomsten is telkens een van die huidige grote landelijke programma's uitgenodigd (Medmij,
BabyConnect, e-Overdracht, Medicatieoverdracht). We organiseren daar een onderzoekende dialoog, om én voor de
langere termijn te leren wat er beter moet aan zibs, én voor de korte termijn de *low-hanging-fruit*-oplossingen voor
operationele problemen aan te dragen of geregeld te krijgen. Wat in dat tweede spoor gebeurt, is op korte termijn
merkbaar. Voorbeelden daarvan zijn:

- Verbetering van de documentatie ten behoeve van leveranciers, op gebieden waar misverstanden blijken te bestaan.
- Eenduidige afspraken op een aantal thema's, waaronder gebruik van terminologie in zibs en kardinaliteit.
- Adresseren en zo veel mogelijk beperken van inconsistenties tussen zibs en informatiestandaarden en daardoor tussen
  informatiestandaarden onderling.
- Duidelijkheid over de toepassing van zib-blauwdrukken, bijvoorbeeld voor metingen.

## Hoe werken we er nu aan, wat betreft inhoud, vorm en proces? En waarom kiezen we voor deze vorm en werkwijze?

De essentie van de zib-transitie is het bijeenbrengen van experts uit verschillende richtingen en achtergronden om de
complexe problemen en uitdagingen van de zib-compliance op te lossen. Voor de uitvoering is gekozen voor een
transitieteam (TT) bestaande uit acht personen te weten: een voorzitter, twee ondersteuners van de voorzitter, drie
werkgroepvoorzitters en twee collega's van het zib-centrum. Zij vergaderen tweewekelijks.

Daarnaast zijn er drie werkgroepen die vanuit de verschillende relevante richtingen kennis en expertise inbrengen. Naast
hun eigen werksessies komen deze werkgroepen elke zes á acht weken onder leiding van het TT bijeen in zogenaamde
ééndaagse meetings. De werkgroepen zijn:

- De werkgroep **Gebruik** met zorgprofessionals als belangrijkste deelnemers, maar ook 'secundaire' gebruikers: *hoe
  zorgen we voor een betere aansluiting tussen zibs en de gebruikspraktijk?*
- De werkgroep **Bouw** met leveranciers als belangrijkste deelnemers: *hoe zorgen we voor betere implementeerbaarheid
  van zibs in de systemen?*
- De werkgroep **Architectuur** met architecten en informatieanalisten: *hoe borgen we de architecturale samenhang?*

Ten slotte is er nog een grotere referentiegroep bestaande uit ongeveer 50 leden. Deze is bij de aanvang in juli 2022
bijeengeweest, na een eerste online werkcongres in januari dat jaar. Het voornemen is deze groep ieder kwartaal bij te
praten en feedback te vragen, maar die frequentie is er nu nog niet. Een volgende bijeenkomst wordt gepland voor de
zomer van 2023.

Nictiz is weliswaar de opdrachtnemer van VWS voor de zib-transitie, maar de opzet en het doel is nadrukkelijk met alle
partijen in het veld te werken aan de zib-compliance. Dit omdat het een vraagstuk is dat niet alleen door Nictiz kan
worden opgelost.

Opdrachtgever voor de zib-transitie is VWS, die als publiek houder voor het stelsel van standaarden ook het houderschap
(de bestuurlijke eindverantwoordelijkheid) voor de zibs op zich heeft genomen. Het transitieteam informeert VWS
periodiek over de voortgang. Besluitvorming is tot nu toe niet aan de orde (we zijn nog volop aan het ontwikkelen), maar
in een later stadium ligt het voor de hand dat gekozen oplossingsrichtingen worden voorgelegd aan de houder om ook
bestuurlijk te verankeren. Ook is denkbaar dat dilemma's of moeilijk overbrugbare verschillen van inzicht tussen
verschillende belanghebbenden aan de houder worden voorgelegd ter besluitvorming.

## Wie zijn betrokken en waarom zij? Is men in de volle breedte over domeinen heen betrokken (ook het sociaal domein bijvoorbeeld) en over meerdere gebruiksdoelen (ook kwaliteitsregistraties en onderzoek bijvoorbeeld)?

Bij de werkgroep bouw zijn op dit moment betrokken vertegenwoordigers van ChipSoft, Epic, Nexus, Nedap, VZVZ, UMCU en
Nictiz. Waar nodig zoeken we vanuit de werkgroep contact met andere relevante stakeholders zoals NedHIS en kleinere
leveranciers met een specifieke doelgroep. Experts binnen de werkgroep bouw zijn betrokken omwille van hun expertise
maar hebben ook mandaat om namens hun organisatie (bijvoorbeeld leverancier) te spreken. Wanneer belangen van
individuele organisaties in tegenspraak zijn met de *expert opinion* of wanneer geen eenduidige expert opinion kan worden
bereikt, zal de werkgroep Bouw de stelselhouder (of het DTO) vragen om een uitspraak.

Bij de werkgroep architectuur vertegenwoordigers van VZVZ, NHG, VWS, MedMij, UMCG, UMCA, IKNL, Health-RI en Nictiz. Ook
hier geldt dat experts zijn betrokken omwille van hun expertise, maar ook mandaat hebben vanuit hun organisatie.

Bij de werkgroep gebruik vertegenwoordigers van het CMIO netwerk (Ruud de Waal CMIO Amphia), FMS (Erik van der Velde),
het CNIO netwerk (Arjen Wignand CNIO AUMC), verpleegkundige (Wikje Muller), huisarts (Bram Smits), CMIO netwerk eerste
lijn (Mariëtte Willems), Patiënten Federatie (Marcel Heldoorn) en Nictiz. Deelnemers vanuit de werkgroep zorg nemen soms
deel op eigen titel, soms als vertegenwoordiger van hun achterban. Daar waar sterker mandaat vanuit koepels gewenst is,
zal dit vanuit de werkgroep gebruik aan de stelselhouder worden voorgelegd.

Dat betekent dat er in deze beginfase nog geen betrokkenheid over de volle breedte van domeinen en over alle
gebruiksdoelen is. Het is de intentie dat de community gaandeweg het transitietraject zal groeien, waar van belang en
ook afhankelijk van de thema's die aan de orde zijn.

## Wie is de opdrachtgever van de zib-transitie?

De opdrachtgever voor de zib-transitie is het ministerie van VWS als houder van het stelsel van standaarden op het
gebied van zorginformatie. Opdrachtnemer is Nictiz als stelselbeheerder van standaarden. De uitvoering hiervan is belegd
bij het zib-transitieteam.

## Hoe communiceren we over de zib transitie?

Huidig:

- Op dit moment is de kern van het werk de werkcommunity die groeiende is. De communicatie daarbinnen (30 á 50 personen)
  vindt plaats per e-mail, en bestaat uit de Rolling Roadmap en alle tussentijdse resultaten die werkgroepen opleveren.
- Op [de site van Nictiz](https://nictiz.nl/wat-we-doen/activiteiten/zibs/zib-transitie/){: target="_blank" } is
  algemene informatie beschikbaar en zijn nieuwsberichten over de zib-transitie bijeenkomsten geplaatst.
- aarnaast zijn eerder online conferenties en een grotere bijeenkomst met 'referentiegroep' gehouden (vorig jaar). Op
  allerlei in de sector relevante congressen wordt door het TT regelmatig gepresenteerd.

Binnenkort:

- De 'referentiegroep' (50 à 100 personen) gaat op regelmatige basis worden georganiseerd (Q2 de eerstvolgende) om naast
  online ook live contact te houden.
- Het regelmatig houden van presentaties zetten we door en trachten we nog strategischer in te zetten (waar willen we
  precies ons verhaal houden).
- We willen vaker of meer, samen met MT Nictiz en anderen kijken op welke tafels wij ons verhaal moeten houden, of het
  gesprek kunnen aangaan.

## Wie is aan de slag met de andere knelpunten? Hoe zijn zij georganiseerd en welke afhankelijkheden zijn er met acties van anderen?

Zoals aangegeven in het antwoord op vraag 10, passen alle knelpunten en grondoorzaken bij de thema's uit het rapport van
Melius Health Informatics in de scope van de zib-transitie. Voor een aantal in het rapport genoemde thema's bestaan
aanpalende initiatieven, zoals bijvoorbeeld:

- Vanuit het MedElkaar initiatief worden Vippthatons en continue monitoring van uitwisseling met het PGO georganiseerd.
  Prioriteiten van de zib-transitie zullen worden afgestemd op de hier gevonden knelpunten.
- Aansluiting met nationale programma's op het gebied van eenheid van taal wordt geborgd door directe betrokkenheid van
  het terminologiecentrum bij de zib-transitie.
- Door de samenwerkende Epic ziekenhuizen wordt gewerkt aan het inzichtelijk maken van de zib-compliance van
  registraties. Vanuit de zib-transitie wordt voortgang gevolgd.

Van belang is om op te merken dat de zib-transitie niet gaat over infrastructuur. Zibs zijn zoals gesteld onafhankelijk
van techniek en infrastructuur. Mogelijk is er op termijn wel sprake van een afhankelijkheid met de [API-strategie](
https://developer.zorgapis.nl/){: target="_blank" }, op het niveau van 'volledig gestandaardiseerde API's'. Nictiz
medewerkers die bij beide programma's betrokken zijn, borgen de samenhang waar nodig.