# Bris

## Prosjektoversikt

Bris er en løsning som analyserer og visualiserer strømdata fra ulike åpne kilder for å gi innsikt i strømpriser og energimiks i Norge.

### Datakilder

Vi har integrert flere åpne datasett fra:
- **Entsoe** - Europeisk nettverk for elektrisitetsoverføringssystemer
- **Elhub** - Norsk nasjonal dataplatform for strømmåling
- **Nord Pool** - Europeisk kraftbørs

Disse kildene gir oss robuste data om:
- Strømforbruk
- Energiproduksjon
- Spotpriser

### Nøkkelfunksjoner

Vår løsning viser sammenhengen mellom:
- Marginalkostnadskurven for strømproduksjon
- Energimiks (vannkraft, vindkraft, termisk kraft, etc.)
- Faktiske strømpriser

Dette gir brukere en tydelig forståelse av hvilke faktorer som påvirker strømprisene til enhver tid.

### Teknisk implementering

- Frontend: React.js
- Data: Integrert via API-er fra de ulike datakildene
- AI-komponent: Azure AI for sikker databehandling og analyse

### Sikkerhet

Vi prioriterer datasikkerhet og beskyttelse av brukernes informasjon. Gjennom integrasjon med Azure AI sikrer vi:
- Dataintegritet
- Sikker databehandling
- Personvernbeskyttelse

## Målsetting

Vårt mål er å gi forbrukere, energiselskaper og beslutningstakere bedre innsikt i energimarkedets dynamikk, for å bidra til mer informerte valg og en mer bærekraftig energibruk.