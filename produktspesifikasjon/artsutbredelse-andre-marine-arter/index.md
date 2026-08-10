---
title: "Artsutbredelse andre marine arter"
updated: "2026-08-10"
organization: "Havforskningsinstituttet"
logo: "https://register.geonorge.no/data/organizations/971349077_hi_liten.png"
---

# Produktspesifikasjon: Artsutbredelse andre marine arter

*Datasettet inneholder generaliserte utbredelseskart av andre marine arter i norske områder som ikke dekkes i kategoriene "fisk" eller "sjøpattedyr", basert på artsansvarlig sin tolkning av utberedelsen de siste 30 årene. Mer informasjon om datagrunnlaget og arten kan man finne hos Havforskningsinstituttet: <https://www.hi.no/hi/temasider/arter>. 

Kartlagene er delt inn i temalag for de forskjellige artene. Eksempler på temalag er utbredelsesområder og høsteområder. Det er definert et gyldighetsområde for de fleste artsutbredelseskartene. 

For å se på, finne tilgangslenker eller laste ned hele eller deler av dette datasettet, gå til kart.hi.no/datasett.*

**Nøkkelord:** Hav, Havets ressurse, Dypvannsreke, Haneskjell, Hummer, Kamskjell, Kongekrabbe, Sjøkreps, Snøkrabbe, Stortare, Taskekrabbe, Utbredelse, utbredelsesområde, høsting, gyldighetsområde, Art, artsutbredelse, Norske havområder, Artsfordeling, Norge digitalt, geodataloven, fellesDatakatalog, Kyst og fiskeri, Natur

**Emnekategorier:** Biologisk mangfold

**Geografisk utstrekning**:

- **Vest**: 60.0
- **Øst**: 85.0
- **Sør**: 0.0
- **Nord**: 90.0

**Tidsmessig utstrekning**:

- **Tidsperiode**:
  - **Fra**: 2017-10-05
  - **Til**: 2025-12-08

## Om spesifikasjonen
Denne produktspesifikasjonen beskriver datasettet og hvordan det skal forstås av brukere som skal lese, produsere eller utveksle data.

> **Denne versjonen av produktspesifikasjonen:** <br>
> **Opprettet dato:** 2017-10-05<br>
> **Endret dato:** 2025-12-08<br>
> **Språk:** nor<br>
> **Kontaktinformasjon:** Havforskningsinstituttet, [datahjelp@hi.no](mailto:datahjelp@hi.no)

## Om produktet Artsutbredelse andre marine arter
Beskriv kort hva produktet inneholder, hvem som forvalter det og hvordan det er strukturert.

> **Romlig representasjonstype:** Vektor<br>
> **Unik identifikator:** <https://data.geonorge.no/sosi/biomangfold/artsutbredelse><br>
> **Kontaktinformasjon:** Havforskningsinstituttet, [datahjelp@hi.no](mailto:datahjelp@hi.no)
>
> **Romlig oppløsning:**
>
> **Ekvivalent målestokk**: 1000
>
> **Begrensninger:**
>
> **Juridiske begrensninger**:
>
> - **Tilgangsbegrensninger**: Åpne data
> - **Bruksbegrensninger**: Lisens
> - **Lisens**: Creative Commons BY 4.0 (CC BY 4.0)
> - **Lisenslenke**: <https://creativecommons.org/licenses/by/4.0/>
>
> **Sikkerhetsbegrensninger**:
>
> - **Klassifisering**: Ugradert

### Formål

Basisdata for forskning og forvaltning. Artsutbredelseskartene viser utbredelsen av de ulike marine artene.

### Bruksområde

Datasettet kan brukes til eksempelvis forskning, forvaltning eller bare som generell informasjon.

## Identifikasjon

- **Kortnavn:** 
- **Versjon:** 
- **Dato:** 

## Avgrensning

Denne spesifikasjonen omfatter …
### Hele datasettet

**Nivå**: dataset

**Nivåbeskrivelse**: Gjelder hele datasettet. Hvis omfang ikke er oppgitt under en overskrift, gjelder teksten for hele datasettet og alle leveranser

### Artsutbredelse

**Nivå**: dataset

**Nivåbeskrivelse**: OGC API-Features fra Havforskningsinstituttet

## Datainnhold og struktur



### Datamodell - Artsutbredelse



<a href="artsutbredelse/artsutbredelse_feature_catalogue.png" title="Klikk for stor visning"><img src="artsutbredelse/artsutbredelse_feature_catalogue.png" alt="Datamodell Artsutbredelse" style="max-width: 100%; height: auto;" /></a>



➡️ [Se full datamodell for omfang "Artsutbredelse" (diagram per pakke og objektkatalog)](artsutbredelse/objektkatalog.html)

## Referansesystem

| EPSG-kode | Navn på referansesystem |
| --- | --- |
| [EPSG:4326](https://epsg.io/4326) | [WGS84 Geografisk](https://register.geonorge.no/epsg-koder) |

## Datakvalitet

**Nivå**: dataset

- **Kvalitetsmål**: Prosentvis dekning i forhold til datasettets utstrekning
  **Målebeskrivelse**: Datasettets faktiske kartlagte areal i forhold til datasettets spesifiserte utstrekning
  **Resultat**: 100

- **Kvalitetsmål**: Coverage
  **Resultat**: Prosentvis dekning i forhold til datasettets utstrekning: 100%

## Datafangst og produksjon

**Datainnsamling og prosessering**:

- **Prosesstrinn**:
  - **Beskrivelse**: Datasettet består av polygoner som representerer områder der artsansvarlig forsker ved Havforskningsinstituttet har definert artens utbredelse. Det er en ekspertvurdering som bygger på data fra de siste 30 år.

## Vedlikehold

**Vedlikeholdsfrekvens**: Etter behov

**Status**: Kontinuerlig oppdatert

## Leveranse

| Tjeneste | Endepunkt | Type | Format | Leveranseenheter |
| --- | --- | --- | --- | --- |
| Egen nedlastningsside | [Lenke](https://kart.hi.no/datasett) | WWW:DOWNLOAD-1.0-http--download | GML, GeoJSON, Shape | landsfiler |
| WMS-tjeneste | [Lenke](https://kart.hi.no/data/utbredelseskart/utbredelse_ovrig/ows?request=GetCapabilities&service=WMS) | OGC:WMS | [{}] | landsfiler |
| WFS-tjeneste | [Lenke](https://kart.hi.no/data/utbredelseskart/utbredelse_ovrig/ows?request=GetCapabilities&service=WFS) | OGC:WFS |  | landsfiler |
| OGC API-Features | [Lenke](https://kart.hi.no/data/utbredelseskart/utbredelse_ovrig/ogc/features/v1/collections?f=text%2Fhtml) | OGC:API-Features |  | landsfiler |
| Artsutbredelse andre marine arter WMS | [Lenke](https://kart.hi.no/data/) | WMS-tjeneste | WMS |  |
| Artsutbredelse WMS | [Lenke](https://kart.hi.no/data/utbredelseskart/wms/ows?request=GetCapabilities&service=WMS) | WMS-tjeneste | WMS-tjeneste |  |

## Metadata

**Metadatastandard**: ISO19115

**Metadatastandardversjon**: 2003

**Metadatadato**: 2026-01-08

**språk**: nor

**Kontakt**:

- **Organisasjon**: Havforskningsinstituttet
- **Kontaktperson**: Marte L. Strømme
- **Logo**: <https://register.geonorge.no/data/organizations/971349077_hi_liten.png>
- **Epost**: marte.stromme@hi.no
- **rolle**: pointOfContact

**Metadataidentifikator**:

- **Utsteder**: Geonorge
- **kode**: 7c36da6f-3bb3-49cc-8968-5d246ee9eb46
- **koderom**: <https://kartkatalog.geonorge.no/metadata/>
- **Metadatalenke**: <https://kartkatalog.geonorge.no/metadata/7c36da6f-3bb3-49cc-8968-5d246ee9eb46>

## Tilleggsinformasjon

Datasettet består av polygoner som representerer områder der artsansvarlig forsker ved Havforskningsinstituttet har definert artens utbredelse. Det er en ekspertvurdering som bygger på data fra de siste 30 år. 
Egenskapene omfatter artsnavn på norsk, engelsk og latin.

Full liste over arter og egenskaper er listet opp i produktarket
