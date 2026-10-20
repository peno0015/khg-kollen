KHG-KOLLEN v1 – lokal testversion

1. Packa upp ZIP-filen.
2. Ladda upp index.html, style.css, app.js, sw.js, icon.svg och manifest.webmanifest till ett NYTT GitHub-repository.
3. Aktivera GitHub Pages: Settings > Pages > Deploy from a branch > main / (root).
4. Öppna GitHub Pages-adressen i telefonen eller datorn. Lägg till på hemskärmen på iPhone om du vill.

OBS: Version 1 sparar i webbläsarens localStorage. Dator och mobil har OLIKA listor. Dela inte denna som gemensam personalapp ännu.
Exportera JSON för säkerhetskopia. Import ERSÄTTER lokal lista.

Datumlogik: KHG-dagar subtraheras som kalenderdagar; KHG-månader subtraheras som kalendermånader. Om månaden saknar samma dag används dess sista dag.
Exempel: Bäst före 18 december och KHG 1 månad => rabattera 18 november.
När bäst före-datumet nåtts visas datumkontroll oavsett om varan tidigare markerats rabatterad.

Notera: 'Bäst före' är inte alltid ett lagkrav på bortplockning. Följ butikens rutiner, särskilt för sista förbrukningsdag.

För gemensam databas krävs en genomtänkt behörighetslösning. Att bara dela länken skyddar inte mot obehöriga ändringar.
