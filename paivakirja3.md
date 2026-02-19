# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Lähinnä auttaa hallitsemaan projektia, varsinkin jos tulee virheitä tai toiminnallisuus rikkoutuu projektissa niin on hyvä, että projektin voi palauttaa aikaisempaan versioon. Lisäksi olettaisin versionhallinnan auttavan jäsentämään omaa työskentelyä.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Mahdollistaa usean käyttäjän samanaikaisen työskentelyn projektin parissa. Samalla käyttäjät voivat työskennellä eri ominaisuuksien parissa ilman, että toisten muutokset ylikirjoittavat omia muutoksia. Oletan, että versionhallinta antaa kontrollia projektinhallintaa ja parantaa koodinlaatua sekä sen myötä tiimityön hallintaa.

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

1. Päähaara pidettävä toimivana versiona.
2. Kehitystyö tehdään vaikka develop haarassa.
3. Jokainen uusi ominaisuus tehdään omassa haarassa
4. Ominaisuus haara yhdistetään dev-haaraan pull requestin kautta.
5. pull requestit tarkistetaan vähintään yhden tiimiläisen toimesta ennen hyväksymistä.
6. Ennen uutta työtä, päivitetään oma local repository komennolla git pull
7. Commit-viestien pitää olla selkeitä ja kuvaavia

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Uskon, että opintojakso auttoi minua ymmärtämään versionhallinan käytännön merkitystä. Useimmat git komennont ovat tulleet tutuiksi harjoituksissa. Ehkä toivonut enemmän porrastettua vaikeustasoa jokaiseen tehtäväkohtaan, esim ensin tee näin tehtäviä ja sitten soveltavia samassa kohdassa (esim.paikallinen git, yms).