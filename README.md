# Worlds-Newspapers
Språk/API: Java / Android, JSON, GSON Firebase, Google Play Services.

Beskrivning: Ett nyhetsprogram. Programmet använder sig av listor med över 12.000
nyhetssidor från alla länder i världen. Detta är det största programmet av sitt slag - världen över.
Listorna kommer användaren åt genom navigation drawer där länderna är uppdelade i regioner
och presenteras i en recyclerviewer. Varje kort innehåller namn på tidningen, land, url samt om
tidningen har bokmärkts. Det går att bokmärka en tidning genom long press. Tidningen hamnar i
favoritmenyn för snabb åtkomst. Klickar man på en tidning används i första hand en intern
webbhanterare med hjälp av webview. Det går att ändra detta till sin egna externa webbläsare i
optionsmenyn. I denna meny kan man även ändra tema på applikationen och rensa hela
favoritlistan om man inte vill ta bort enskilda genom long press i favoritmenyn. Då tidningar finns
i recyclerviewn kan man söka efter en tidning genom tidningens namn eller land, alternativt
både på samma gång. När en hemsida har laddats sparas den i cachen. Om användaren inte
har internet tillgängligt via mobildata eller WIFI kommer cachen användas. Alla storlekar på
skärmar stöds - mobiler och tablets - förutom ytterst små skärmar. I webbläsarna är Javascript,
zoom och caching påslagna.

Koden finns inte tillgänglig eftersom detta är produktionskod. Det går att se och köpa
applikationen via Google Play via urlen:
https://play.google.com/store/apps/details?id=blue.ansoa.worldsnewspapers&hl=en
