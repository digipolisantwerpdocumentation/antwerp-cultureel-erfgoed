# Inleiding

> Antwerpen - Cultureel Erfgoed

De Antwerpse erfgoed objecten zijn zeer divers en worden in meerdere collectiebeheersystemen bijgehouden: Adlib, Brocade Bibliotheek en Brocade Archief/Arches/ArchivesSpace. Beeldmaterieel en bijhorende metadata worden opgeslagen in een eigen Digital Asset Management Systeem. Dat maakt de ontsluiting en uitwisseling van collectiedata tussen de Antwerpse stedelijke musea (MAS, Rubenshuis, Red Star Line, Middelheim, Mayer van den Bergh, Plantin Moretus en Vleeshuis), de Erfgoedbibliotheek Hendrik Conscience en het Letterenhuis onmogelijk. Sommige musea (zoals Plantin Moretus) gebruiken drie collectiebeheersystemen tegelijkertijd (museum, bibliotheek, archief) en moeten dus via drie platformen hun collecties opzoeken. 

> De datahub als aggregatieplatform

Daarom werd er gekozen om intensief in te zetten op een aggregatie platform - de datahub. Deze werd ontwikkeld om de data samen te brengen en te integreren gebruik makend van semantische web technologie en gemeenschappelijke standaarden zoals CIDOC CRM. Deze internationale ontologie werd binnen de erfgoedsector reeds 20 jaar geleden opgestart en is uitgegroeid tot de de-facto standaard binnen het domein van cultureel erfgoed. Met deze standaard is het mogelijk om erfgoed data van archieven, bibliotheken en musea met elkaar te verbinden.

> Gefaseerde aanpak

In Antwerpen gebeurde de omzetting van deze data in een fasering: eerst werden de museale data omgezet in een semantisch referentiemodel. Hierbij werd inspiratie gehaald bij het Linked Art profiel van CIDOC-CRM, maar ook (ondermeer) de modellen opgemaakt door het Swiss Art Research Institute, National Gallery en Netwerk Digitaal Erfgoed. Vervolgens werd een bibliografisch referentiemodel uitgewerkt. Hier werd tevens gebruik gemaakt van de FRBRoo standaard (intussen ondergebracht binnen de bredere CIDOC-CRM koepel). Tenslotte kwam een referentiemodel voor de archieven tot stand als onderdeel van de migratie naar een nieuw archiefbeheersysteem. Dit gecombineerd model werd vervolgens omgezet naar de OSLO applicatieprofielen voor cultureel erfgoed van Digitaal Vlaanderen.

We willen het bestaande model ook nog uitbreiden met een mapping die ook voor immaterieel erfgoed gebruikt kan worden.

Stap voor stap werden al deze bronnen geïntegreerd via één data platform waardoor de data gezamenlijk aangeboden en uitgewisseld kunnen worden aan de hand van web technologie, zoals via API’s en SPARQL queries.