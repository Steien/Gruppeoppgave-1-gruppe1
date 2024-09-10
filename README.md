# Gruppeoppgave: Reliabilitet og verktøy for reproduserbar datavitenskap

## Prosjektbeskrivelse
Dette prosjektet er en del av kurset IDR4000-1 24H Kvantitativ metode og statistikk i første året master i treningsfysiologi ved Høyskolen i Innladet. Formålet er å presentere estimater for reliabilitet av målinger samlet i fysiologilaboratoriet og å bruke verktøy for reproduserbar datavitenskap.

## Gruppemedlemmer
- Trond Steien
- Andrine Juveng
- Simon Trygve Haslum Kristiansen
- Anders Nybakk

## Prosjektstruktur DETTE ER BARE ET EKSEMPEL!!!
- `data/`: Inneholder datasettene som brukes i analysen
- `scripts/`: R-skript for dataanalyse
- `docs/`: Quarto-dokumenter for rapportskriving
- `output/`: Genererte figurer og tabeller

## Bruk av referanser

Vi bruker en bibliografi-fil (referanser.bib) for å håndtere referanser i prosjektet. For å sitere en kilde i Quarto-dokumentet:

1. Åpne referanser.bib-filen for å se nøklene til hver referanse.
2. I Quarto-dokumentet, bruk [@nøkkel] for å sitere en kilde. For eksempel:

   - [@halperin2015] for Halperin et al. (2015)
   - [@hopkins2000] for Hopkins (2000)
   - [@tanner2012] for Tanner & Gore (2012)

3. For å sitere flere kilder sammen, bruk [@nøkkel1; @nøkkel2].

4. For å nevne forfatteren i teksten, bruk @nøkkel. For eksempel:
   "Som nevnt av @halperin2015, er det viktig å..."

Quarto vil automatisk generere en referanseliste i slutten av dokumentet basert på de kildene du har sitert.

Husk å inkludere denne linjen i YAML-headeren til Quarto-dokumentet:

```yaml
bibliography: referanser.bib



## Kontakt
For spørsmål eller tilbakemeldinger, vennligst kontakt Trond Steien på steientrond@hotmail.com