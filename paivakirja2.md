# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__


Hieman epäselvää miten paikallinen repositori ja githubin repositori toimivat keskenään. Komennot fetch, merge ja pull ehkä vielä hieman epäselviä vaikka selitykset niiden toimintoihin ovat melko yksinkertaisia. Etäreposition lisääminen oli melko helppoa ja ensimmäinen push githubiin oli aika suoraviivaista.

## Osiossa käyttämäni Git-komennot

| Komento                     | Kuvaus                                                               |
| ----------------------------| -------------------------------------------------------------------- |
| git remote add origin <url> | Lisää GitHub-repositorion etärepositorioksi nimellä origin           |
| git remote -v               | Näyttää etärepositorioiden osoitteet                                 |
| git push -u origin master   | Puskee paikallisen master-haaran GitHubiin ja asettaa oletusetärepon |
| git fetch                   | Hakee muutokset etärepositoriosta ilman yhdistämistä                 |
| git checkout origin/master  | Siirtyy tarkastelemaan etähaaraa (detached HEAD)                     |
| git checkout master         | Palaa paikalliseen master-haaraan                                    |
| git merge origin/master     | Yhdistää etähaaran muutokset paikalliseen haaraan                    |
| git branch                  | Näyttää paikalliset haarat                                           |
| git branch -r               | Näyttää etähaarat                                                    |
| git tag harjoitus5          | Lisää tunnisteen viimeisimpään commitiin                             |
| git status                  | Näyttää työtilan ja staged muutosten tilan