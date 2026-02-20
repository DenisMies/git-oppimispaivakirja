# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Mielestäni vaikeaa on ymmärtää hahmottamaan eroja tiedoston eri tilojen välillä (staged,modified,unmodified). Tämän lisäksi hankalaa on perua tekemiä toimintoja. Haarojen ymmärtäminen myös ehkä hieman hankalaa, ymmärrän kuitenkin paremmin kuin edelliset. Samalla iso määrä uusia komentoja saa pään pyörälle. Helpommiksi tehtäviksi voisin sanoa perus tiedostojen lisäämisen ja committaamisen, sekä git statuksen runsas käyttö.

## Osiossa käyttämäni Git-komennot


| kirjoita tähän komento | tähän lyhyt kuvaus, mitä komento tekee |

| Komento                     | Kuvaus                                                         |
| --------------------------- | -------------------------------------------------------------- |
| git init     | Luo uuden Git-repositorion hakemistoon                         |
| git add .  | Lisää kaikki muutokset stageen seuraavaa commitia varten |
| git commit -m "viesti"    | Tallettaa stageen lisätyt muutokset versionhallintaan          |
| git status     | Näyttää työtilan ja staged-muutosten tilan                     |
| git log  | Näyttää commit-historian    |
| git rm <tiedosto> | Poistaa tiedoston Git-hallinnasta   |
| git mv <vanha> <uusi> | Nimeää tai siirtää tiedoston Gitissä     |
| git restore <tiedosto>   | Peruuttavat työtilassa tehdyt muutokset                        |
| git revert <commit>       | Luo uuden commitin, joka peruuttaa aiemman commitin muutokset  |
| git branch <haara>       | Luo uuden haaran   |
| git checkout <haara>| Vaihtaa aktiiviseksi haaraksi                                  |
| git checkout -b <haara> | Luo uuden haaran ja siirtyy sille   |
| git merge --no-ff <haara> | Yhdistää toisen haaran nykyiseen säilyttäen historian näkyvänä |
| git tag <tunniste>| Lisää tunnisteen tiettyyn commit:iin |
| git switch <haara> | Vaihtaa haaraa
