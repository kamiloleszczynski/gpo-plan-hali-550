# GPØ — interaktiv hallplan, 550 m²

Løsning 1, med maskinlinjen plassert i den nye hallen. Appen er på norsk bokmål.

## Åpne planen

[Åpne hallplanen på GitHub Pages](https://kamiloleszczynski.github.io/gpo-plan-hali-550/)

- Zoom og panorering, også på berøringsskjermer.
- Valg av tegningselementer og snarveier til soner. Søk og listen «Soner / Objekter» er midlertidig skjult.
- Én truck starter ute. Velg «Vaskelinje U», «Vaskelinje 2» eller «Kjølerom» for å starte riktig rute. Portene åpnes automatisk. I kjølerommet svinger trucken inn, rygger og manøvrerer mot kassene. Ingen manuelle portknapper.
- «Venstre semitrailer» viser utkjøring fra venstre lastedokk og passering av høyre semitrailer, som står parkert. Semitraileren følger trekkvognen i svingen. Kjøretøy og piler beholder tynn CAD-stil.
- Pause, fremdriftslinje og «Til start» gjør det mulig å undersøke hver manøver. Valgt rute følger den delte lenken. Animasjonen illustrerer et forslag, ikke en verifisert sporingsanalyse for et bestemt kjøretøy.
- Kompakt toppanel med anleggsinformasjon, areal og brytere for vei, eiendomsgrenser og sonefarger. Tegningen bruker hele sidebredden, også på små skjermer.
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

Kildedata inneholder 46 508 CAD-elementer. 17 utvendige mål- og tekstelementer for hallen vises som informasjon i panelet under tegningen i stedet for over eiendommen. Maskingeometrien er uendret. Visningen har en foreslått 3 m åpning i nordveggen ved lastedokken; originaldataene er bevart. Ny hall: produksjon 210,3 m², kjølerom 287,2 m² og rom ved lastedokken 52,5 m². Arealene er oppgitt før fradrag for veggtykkelse. Kapasitet ved stabling og skjermmålinger er veiledende.

Repositoriet inneholder den publiserte visningen, uten originale DWG-filer eller innloggingsopplysninger.

## Eiendomsgrenser

Tomt 1 og Tomt 2 følger de synlige hvite grenselinjene i referansefotoet. Det bredere fotoet er tilpasset samme plan, mens grensene beholdes. Knekker langs Rabben og hjørnene er sporet i bildet. Foto, veier og tomter bruker samme koordinattilpasning; felles grense har identiske endepunkter i begge omriss. Tilpasningen er orienterende, og CAD-geometrien er uendret. Omrissene er ikke innmålte matrikkelgrenser. Tomt 1 er 3112 – 82/110 (3 561,4 m²), og Tomt 2 er 3112 – 82/3, Rabben 16 (6 224,6 m²), fra eiendomsopplysningene vedlagt av brukeren. Klikk på en tomt for eiendomsareal, anslått bebygd areal i CAD-planen med ny hall og andelen i prosent. Fotavtrykk fordeles etter tomtegrensene uten dobbelttelling. Småbygg som bare finnes i flyfotoet er ikke inkludert. Dette er et anslag for bygningene i planen, ikke regulert %-BYA.

## Flyfoto og vei

Satellittvisningen viser eksisterende bygninger fra originalfotoet vedlagt 7. oktober 2026 (1816 × 1149). Fotoet er uendret og plasseres samlet; ingen lokale deformeringer av takene. Det er registrert mot det bredere flyfotoet med én rotasjon, lik skalering i begge retninger og forskyvning. 1 445 bildepunkter gir et gjennomsnittlig avvik på 0,33 piksler i det brede fotoet.

Konseptbildet bidrar bare med utsnitt av den planlagte hallen og lastebilene. Det dekker ikke lenger eksisterende tak på hele eiendommen. Det brede bildet brukes utenfor det nyere bildets dekning. «Originalfoto» åpner brukerens uendrede foto, mens «Vis simulering» viser det tidligere konseptbildet. Alle tre originale bildefiler følger med i HTML-filen. CAD, tomtegrenser, arealberegninger og kjøresimuleringer er uendret. Dette er en konseptvisualisering, ikke et levende kart eller en innmåling.
