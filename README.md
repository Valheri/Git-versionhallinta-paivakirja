# git-oppimispaivakirja

Tämä on kurssin oppimispäiväkirja.

Kurssin nimi ja toteutuksen koodi: Git-versionhallinta - SOF013AS2A-3002

Tekijän nimi: Valtteri Vuokila

Lyhyt selvitys, mitä repositoriossa on: kurssin päiväkirja

---

<details>
  <summary><b>Lue Päiväkirja 1 (Klikkaa tästä)</b></summary>
  
  ### Osio 1
  # Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Mikään ei oikeastaan ollut vaikeaa. Kaikki entuudestaan tuttua, kun hieman myöhäisessä vaiheessa tulee tämä kurssi käytyä.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git tag <nimi> | Listaa kaikki projektissa olevat tunnisteet. |
| git revert HEAD --no-edit | Luo uuden tallennuksen, joka kumoaa edellisen muutokset automaattisella viestillä. |
</details>

<details>
  <summary><b>Lue Päiväkirja 2 (Klikkaa tästä)</b></summary>
  
  ### Osio 2
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
</details>

<details>
  <summary><b>Lue Päiväkirja 3 (Klikkaa tästä)</b></summary>
  
  ### Osio 3
  # Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Voin palata aiempiin versioihin helposti jos on tarvetta tai tulee virheitä

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Sama kuin ylempi ja projekti ei heti tuhoudu jos joku "mokaa"

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Käyttäkää Feature Branch -mallia: luokaa jokaiselle uudelle ominaisuudelle oma haara (git checkout -b ominaisuus), jotta koodi pysyy erillään muiden kokeiluista. Kun ominaisuus on valmis, tehkää GitHubissa Pull Request ja pyytäkää yksi tiimiläinen tarkistamaan koodi ennen sen yhdistämistä main-haaraan.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Ihan ok kurssi. Workflow säätö(e.g. joku lint tarkistus) olisi ollut kiva lisä.
</details>

## Sisällysluettelo
* [Päiväkirja 1](./paivakirja1.md)
* [Päiväkirja 2](./paivakirja2.md)
* [Päiväkirja 3](./paivakirja3.md)
