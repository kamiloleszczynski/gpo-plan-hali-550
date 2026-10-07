# GPØ — interaktiv hallplan, 550 m²

Løsning 1, med maskinlinjen plassert i den nye hallen. Appen er på norsk bokmål.

## Åpne planen

[Åpne hallplanen på GitHub Pages](https://kamiloleszczynski.github.io/gpo-plan-hali-550/)

- Zoom og panorering, også på berøringsskjermer.
- Valg av tegningselementer, maskinsøk og snarveier til soner.
- Enkelt panel for vei, eiendomsgrenser og sonefarger.
- To klikkbare tomteomriss, felles grense og snarveien «Eiendommer».
- Asfaltveien Rabben følger flyfotoet og kan velges eller skjules.
- Bytt mellom «Tegning» og «Satellitt», med bryteren «Vis omriss av maskiner og rom» for konturer uten tekst eller fargefyll. Satellittvisningen begrenser zoom og panorering til fotoets dekning, også etter endring av vindusstørrelse.
- Se den opprinnelige hallvisualiseringen med «Vis simulering». Begge bilder følger med i HTML-filen for bruk uten internett.
- Veiledende avstandsmåling mellom to valgte punkter.
- Legendefelt og måleresultat utenfor kartflaten. Hallens mål og arealtekster er samlet i panelet «Mål og arealer» under tegningen.
- Del gjeldende visning med en lenke, eller last ned en HTML-fil.

Filen `index.html` inneholder hele appen og tegningsgeometrien. Den kan åpnes i en nettleser uten installasjon eller server. Panorering endrer bare visningen, ikke maskinenes plassering.

GitHub Pages publiserer fra rotmappen i grenen `main`. Filen `.nojekyll` gjør at appen vises uten behandling i Jekyll.

## Tegningsdata

Kildedata inneholder 46 508 CAD-elementer. 17 utvendige mål- og tekstelementer for hallen vises som informasjon i panelet under tegningen i stedet for over eiendommen. Bygnings- og maskingeometri er uendret. Ny hall: produksjon 210,3 m², kjølerom 287,2 m² og rom ved lastedokken 52,5 m². Arealene er oppgitt før fradrag for veggtykkelse. Kapasitet ved stabling og skjermmålinger er veiledende.

Repositoriet inneholder den publiserte visningen, uten originale DWG-filer eller innloggingsopplysninger.

## Eiendomsgrenser

Tomt 1 og Tomt 2 følger de synlige hvite grenselinjene i referansefotoet. Det bredere fotoet er tilpasset samme plan, mens grensene beholdes. Knekker langs Rabben og hjørnene er sporet i bildet. Foto, veier og tomter bruker samme koordinattilpasning; felles grense har identiske endepunkter i begge omriss. Tilpasningen er orienterende, og CAD-geometrien er uendret. Omrissene er ikke innmålte matrikkelgrenser; navnene er visningsnavn, ikke gårds- og bruksnummer. Eiendomsareal er derfor ikke oppgitt.

## Flyfoto og vei

Satellittvisningen bevarer den opprinnelige simuleringen med ny hall og kjøretøy innenfor anlegget. Det bredere bildet (1851 × 1055) brukes bare til omgivelsene rundt anlegget, ikke som erstatning for hallvisualiseringen. Dette er ingen løpende karttjeneste. Det er tilpasset referansefotoet ved åtte punkter på eksisterende tak. CAD og foto har lokale avvik; tilpasningen endrer ikke tegningsgeometrien. Opptaksdato er ikke oppgitt. Veiomriss og bredde er veiledende. Begge originale bildefiler er innebygd uten endringer; de kombineres i visningen med en myk overgang langs tomteomrisset og roteres sammen med planen. Delte lenker bevarer valg av bakgrunn og tegningsvisning.
