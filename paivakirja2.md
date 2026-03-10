# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Edelleen tuttua hommaa. Ei tullut esteitä.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| :--- | :--- |
| `git remote add origin <url>` | Yhdistää paikallisen repositorion etäpalvelimeen (esim. GitHub) nimellä "origin". |
| `git remote -v` | Listaa kaikki määritetyt etärepositoriot ja niiden osoitteet. |
| `git push -u origin master` | Lähettää paikallisen haaran GitHubiin ja asettaa sen seuraamaan etähaaraa. |
| `git fetch` | Hakee päivitykset etäpalvelimelta, mutta ei muuta paikallisia tiedostoja vielä. |
| `git checkout origin/master` | Siirtyy tarkastelemaan etärepositorion tilannetta (detached HEAD -tila). |
| `git merge origin/master` | Yhdistää etäpalvelimelta haetut muutokset paikalliseen master-haaraan. |
| `git status` | Näyttää työtilan tilan ja kertoo, onko paikallinen haara perässä etähaaraa. |
| `git tag harjoitus5` | Lisää tunnisteen viimeisimpään tallennukseen harjoituksen merkiksi. |