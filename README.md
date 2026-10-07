# GPØ — interaktiv hallplan, 550 m²

Løsning 1, med maskinlinjen plassert i den nye hallen. Appen er på norsk bokmål.

## Åpne planen

[Åpne hallplanen på GitHub Pages](https://kamiloleszczynski.github.io/gpo-plan-hali-550/)

- Zoom og panorering, også på berøringsskjermer.
- Valg av tegningselementer, maskinsøk og snarveier til soner.
- Vis eller skjul elementkategorier og tekst.
- To klikkbare tomteomriss, felles grense og snarveien «Eiendommer».
- Rabben og intern adkomstvei bak bygningene, med forbindelser til Rabben, tegnet etter flyfotoet.
- Bytt mellom «Tegning» og «Satellitt», med valgfri tegningsvisning over fotoet.
- Se hele originalfotoet med «Vis originalfoto». Fotoet følger også med i HTML-filen for bruk uten internett.
- Veiledende avstandsmåling mellom to valgte punkter.
- Legendefelt og måleresultat utenfor kartflaten. Hallens mål og arealtekster er samlet i panelet «Mål og arealer» under tegningen.
- Del gjeldende visning med en lenke, eller last ned en HTML-fil.

Filen `index.html` inneholder hele appen og tegningsgeometrien. Den kan åpnes i en nettleser uten installasjon eller server. Panorering endrer bare visningen, ikke maskinenes plassering.

GitHub Pages publiserer fra rotmappen i grenen `main`. Filen `.nojekyll` gjør at appen vises uten behandling i Jekyll.

## Tegningsdata

Kildedata inneholder 46 508 CAD-elementer. 17 utvendige mål- og tekstelementer for hallen vises som informasjon i panelet under tegningen i stedet for over eiendommen. Bygnings- og maskingeometri er uendret. Ny hall: produksjon 210,3 m², kjølerom 287,2 m² og rom ved lastedokken 52,5 m². Arealene er oppgitt før fradrag for veggtykkelse. Kapasitet ved stabling og skjermmålinger er veiledende.

Repositoriet inneholder den publiserte visningen, uten originale DWG-filer eller innloggingsopplysninger.

## Eiendomsgrenser

Tomt 1 og Tomt 2 følger de synlige hvite grenselinjene i brukerens flyfoto. Knekker langs Rabben og hjørnene er sporet i bildet. Foto, veier og tomter bruker samme koordinattilpasning; felles grense har identiske endepunkter i begge omriss. Tilpasningen er orienterende, og CAD-geometrien er uendret. Omrissene er ikke innmålte matrikkelgrenser; navnene er visningsnavn, ikke gårds- og bruksnummer. Eiendomsareal er derfor ikke oppgitt.

## Flyfoto og vei

Satellittvisningen bruker brukerens vedlagte bilde, ikke en løpende karttjeneste. Bildet er omtrentlig tilpasset samme bygning på 25 × 25 m. Opptaksdato er ikke oppgitt. Veiomriss og bredde er veiledende. Den originale bildefilen er innebygd uten endringer; visningen roteres sammen med planen. Delte lenker bevarer valg av bakgrunn og tegningsvisning.
