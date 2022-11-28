## Tehtävä: Opiskelijaryhmän tiedot
* **Kaikkien ryhmään** kuuluvien opiskelijoiden nimet ja JAMK:n opiskelijatunnukset
    * TODO: Opiskelija 1 + opiskelijatunnus
    * TODO: Opiskelija 2 + opiskelijatunnus
    * TODO: Opiskelija 3 + opiskelijatunnus
    * TODO: Opiskelija 4 + opiskelijatunnus

Huom! Vain yksi vastaus tähän ryhmätehtävään per ryhmä. Kaikki vastaukset arvioidaan koko ryhmän jäsenille samalla tavalla.

#### Tehtävien pisteytys

* Opintojakson opettaja laskee pisteet palautuksen jälkeen
* Alla kootusti tehtävien maksimipistemäärät

| Teht. 3 | Teht. 4 | Yhteensä |
|---------|---------|----------|
| 5p      | 5p      | max. 10p |

--------------------

## Tehtävien 3-6 alustus 

Tehtävissä **3-6** on kuvitteellinen tilanne, jossa **ryhmänne on konsultoimassa vesiyhtiötä**.

* Datalähteenä on **Yorkshire Water** -yhtiön julkaisemat vedenkäyttötilastot vuosilta **2012-2015**
* Datalähteenä tehtävässä on: https://datamillnorth.org/dataset/yorkshire-water-daily-customer-meter-data--local-area-

Huom! Voitte myös käyttää tulosten analysoinnissa annettua [Yorkshire Water Jupyter Notebook -dokumenttia](jupyter_data/YorkshireWater_data_analysointi.ipynb). Sitä on myös mahdollista hieman muuttaa data- ja tulosanalyysia varten, mutta kovin paljon aikaa ei siihen kannata käyttää, koska aihetta opiskellaan paljon tulevilla kursseilla. 

Seuraavassa hieman lisätietoa datasta sen tarjoajan sivuilta:

* A dataset showing daily water consumption readings in cubic metres (m3) from internal and/or external meters in a discrete study in two distribution management areas (DMAs) in Yorkshire between 2013 and 2015.
* This data is taken from a live localised project investigating water use. 
* The data has been anonymised to remove personal data and make it Data Protection Act compliant. 
* The DMAs are also anonymised to prevent any open data activity affecting the results of the ongoing study the data has been taken from.

### Videomateriaali 
Katso videomateriaali aina ennen tehtävien tekemistä. Tämä on tärkeää, koska on hyvä pyrkiä ymmärtämään käsitteitä ennen vastausten kirjoittamista. 
* Tehtävien lopussa on lista hyödyllisistä videoista ja muista lähteistä
* Tehtävissä keskeisin asia on **CRISP-DM -prosessi**
* Ennen tehtäviä kannattaa katsoa videot **01-05**.

### Tehtävät 3-6 vs. CRISP-DM

![CRISP-DM Yleiskuva](img/crisp-dm.png)

![CRISP-DM ja opintojakson tehtävät](img/crispdm-vs-teht.png)

--------------------

# Tehtävä 3: Ongelman kuvaaminen 

* mistä vesilaitos saa tuottonsa (liiketoiminta)
* mitkä asiat ovat vesilaitokselle tärkeitä?
* Mitä vesilaitoksen asiakkaat hyötyvät datasta?
* Ketkä muut voivat datasta hyötyä?
* Vesilaitoksella on erilliset alueverkot
* asiakkaiden vesihuollon häiriöttömyys ja vedenlaatu on yhtiölle tärkeitä arvoja
* muista CSV-tiedostoista voi löytyä lisäinformaatiota kulutukseen liittye
* ketkä tätä dataa pystyvät teknisessä mielessä hyödyntämään?
* Löytyykö datasta poikkeavia havaintoja?



Haetaan vastaukset kysymyksiin: 
* Millainen data on kyseessä? 
vedenkäyttötilastot vuosilta 2012-2015 
* Missä yhteydessä tästä datasta voi olla hyötyä? 
kulutuksen seurannassa, kapsiteetin varmistus tiettyinä aikoina,säästöohjelma joskus tarpeen. jyvitys, yritys tietää kapasiteettitarpeesta ja kuluttja omista tottumuksista, onko syytä muuttaa niitä?
* Millainen liiketoiminta on datan taustalla? 
puhtaanveden jakelu 
* Mitä kaikkea datasta voidaan oppia? 
kulutustottumuksia tiettyinä kuukausina vuodessa vuodenaikoina (onko muutoksia tapahtunut eri vuosina, graafi jossa keskiarvo ja ) ja onko muutosta vuosien aikana tapahtunut, kapasiteetin varmistaminen poikkeustlanteissa rajoittaminen/lisääminen mahd. vuotokohdat....
elintapojen muutoksia tekniikan muutoksia jotka johtavat kulutuksen vähenemiseen/lisäämisen onko sääolosuhteilla vaikutusta yms.
teknologian sääolosuhteiden vaikutus kulutukseen
* Mitä datasta voidaan nähdä? 
graafeista nähdään kulutustottumuksia kiinteistökohtaisia vedenkulutustietoja aikaleimalla
* Mitä datasta voidaan tunnistaa? 
datasta tunnistetaan tunnuslukuja poikkeustilanteita, tähän vois laitta laskelmia keskiarvo yms. eri aikina vertailua
* Voidaanko datasta havaita jotain poikkeavaa? 
kyllä erityisesti kiinteistön 163 kulutus syyskuussa 2013 
* Tarvitaanko tämän lisäksi jotakin muuta lisätietoa? 
teknologian sääolosuhteiden vaikutus kulutukseen
Häiriöraportti, Selvitys poikkeustilanteista, silla huomattavia poikeukisia, Poikkeusraportti, mistä johtuu em. kuka on tämä kuluttaja syyskuu onko lomakuukausi jenkeissö, onko kysessä kylpylä sisävesipuisto tms. mutta vain vuonna, mutta seuravina vuosina ei ole kulutusta, olisiko silloin jokin rakennuskohde joka käyttää paljon vettä? 

Palautetaan vastaus repositoryyn annettuun palautuspäivämäärään mennessä:
* mielellään MarkDown-formaatissa (tarkenne .md), jolloin kuvat ja kaaviot linkitetään dokumenttiin. 
* Voi palauttaa tämän vastauksen myös PDF-formaatissa

**Lähteitä:**
* Video - **05 CRISP-DM Alku**
* Katso Myös **10: Tekoälyprojektin roolitus**

----------
## Tehtävä 3: Vastaus 

TODO: Jos kirjoitat vastauksen MarkDown-formaatissa, sen voi liittää suoraan tehtävädokumenttiin.
[MarkDown-tutorial](https://www.markdownguide.org/basic-syntax/).


----------
Moro,

 

Ehdotin silloin joskus, että voitaisiin Tomin kanssa olla vaikka yksi ryhmä kun hän ilmoitti olevansa vailla ryhmää.

Ei olla oltu yhteydessä ainakaan vielä puolin/toisin.  Tämän viikon jälkeen vapaudun "täysin"tähän kurssiin kun React-kurssin deadline umpeutuu.

Aloin kyllä  jo äskettäin tsekkaan matskua, videot kävin kaikki läpi, mutta jotenkin en saanut niistä vielä oikein mitään irti, 

oliskohan ollut väärässä moodissa ja/tai väsynyt... 

Vähän pyörittelin jo dataakin ja kävin läpi tehtäviä, niihin ei liene tarkoitus kovin syväanalyysia tehtävän, lienee seuraavan kurssikokonaisuuden aihepiiriä,  laskennalliset menetelmät/analyysit yms.

Erityisesti kiinteistön 163 syyskuu 2013 kulutus ollut ihan tolkuton, yritin googlata mutta eihän tietoa/syytä löytynyt , tuli aluksi mieleen esim. jokin vesihuvipuisto tms., mutta kulutus on hyvinkin tasaantunut muille ajoille silloin vedenjakelu kiinteisöötn on ollut käytössä, voisiko olla jokin rakennusprojekti tuona poikkeus ajanjaksona ? No on siellä muitakin kohteita, joissa keskiarvoon nähden poikkevaa kulutusta (mahd. suurempia yksiköitä/kiinteistöjä), niin nuo poikkeustapaukset vääristävät keskiarvoa yms. joten ne pitänee poistaa (joitakin yliesitä yhteenvedoista) ja laittaa omaan luokkansa. Myös tapauksesta riippuen poistetaanko täytearvot -1.0 kokonaan vai laitetaanko 0 tilalle.  

 

Voin toki olla omassa ryhmässäni yksinkin, mutta voisihan sitä vaihtaa ajatuksia jonkun/joidenkin kanssa, mutta tämän viikon jälkeen...

 

ps.

Mitä datasta voidaan nähdä?

Mitä datasta voidaan tunnistaa?

Nuohan on oikeastaan sama asia, tosin jos näkemisellä tarkoiteaan tapauskohtaisia graafisia diagrammeja niin kuvastahan tietty voidaan tulkita silmämääräisesti datan suunta ja suuruus. Datan tunnistamisella vissiin tarkoitetaan mahdollisesti tunnuslukujen hakemista datasta.

 

t. Timo


käyttöaste kun -1.0 arvot poistetaan
Tsekkaa google vesi data analytiikka tms. onko sitä ja milliasta
TSEKAAA HARJOITUSKSET 1-2 sekä sieltä muummoassa kumulatiiviset yms. mitä niistä sadaan irti?
Mikä on merkattu -1.0 siis mitä tarkoittaa
Käy läpi aikaisemmat harjoitukset kaikki, sieltä ideoita tähän tehtävään etämitä ahetaan ja miten ja analysoidaan
nyt: 
haetaan kunkin kiinteistön maksimit ja siitä joukosta maksimi käppyrä
myös hae minimit mikä on suurin minimi ja pienein minimi käppyrä
Mikö on maxismeista maxein ja mikö minein
Näyttäisi olevan ehjä data ei nan eikä puuttuvia arvoja vaan -1.0, päivämäärä yms noudattaa öogiikkaa ehjä kokonaisuus, data on oikeissa kentissä oikeassa formaatissa

-----------
Laske tunntulukuja keskiarvoja regressio, keskihajonta min max avg eri aikajaksoilla
Joissakin kiinteistäissä ei ole tietyltä väliltä arvoja olisko kysymys että ei ole vielä ollut olemassa tyhjillään

google esim. pandas test dataframe data quality
1.
Poikkeukset niin suuri että ne vaikuttavat ylieskuvaa kulutuksesta, toki voidaan huomioida mutta vääristää yleiskäsitystä,
tsekaa jostakin mitä tehdä riippuu siitä mitä haluitaan ja kenelle kertoa, fakta tietysti on että huomioitava tietyissa tilastoissa 
mutta ei yliestävässä esim. keskikulutusta esuteträessä ja eri kiinteistoja verrattaessa kkeskikulutukseen.
Data on csv formaatissa jossa sarkerottimena on "," (pilkku) 
haetaan max-arvo ja saadaan tieto päivämäärästä, tsekataan onko tämä poikkeus vertaamalla muihin arvoihin,
jos on poikkeus niin haetaan onko jokin syy googletetaan kyseisen päivämäärää liittyen vesilaitokseen tms.

# rivejä
print(df.index.size)
# tai
print(df.shape[0])

# sarakkeita 
print(df.shape[1])
#tai
print(len(df.columns))

# NaN kenttiä koko datassa
print(df.isna().sum().sum()


kapasiteetin mitoitus 
Kysessä kiinteistöön tuleva puhdas käyttövesi, poistuva/jätevesi oma juttunsa
budjetoinnissa voi olla hyötyä, sekä vedeb sääntelyssä, josku svoidaan joutua säätelemään kun lasketaan keskimääräinen tarve niin 
voidaan asettaa kulleekin taloudelle jokin prosentuaalinen säästä/rajoitus. Tiettyjen tunnuslukujen kuten xxx perustella voidaan havaita kuluttujan köäyttäytymistä veden käytön suhteen jos on lisöäsntynyt tai vähentynyt pitää selvittää mistä johtuu, yleisen trendin mukaisesti
Jos on pikkeumia lähinnä korkea kulutus on syytä selvittää mistä jihtuu ja jos on jatkuvaa... mahd. vuoto tai vahinko jöönyt hana päälle, kuiva kesä putket jäässä sii epäkunnossa onko kiinteistökoihtainen vai yleisempi ongelma.
Eli haetaan max arvo kulutus datasta, 
Vesi on ongelma monissa kaupungeissa/kohteissa , joten völillä on otettava pakkokeinojakin käyttöön ja turvata töerkeiden kohteiden vedensaanti,´eli priorisointia. 
Vedensööstöongelma-> sunnitelma talouskohtaisesti
https://datamillnorth.org/dataset/yorkshire-water-daily-customer-meter-data--local-area-
https://datamillnorth.org/download/yorkshire-water-daily-customer-meter-data--local-area-/fb01ce66-423a-4111-9065-d989bdf0b3ce/Daily%20m3%201315.csv


takaisinkytkentä mainitse jossakin eli ..
    scikit-learn
    https://datamillnorth.org/dataset/customer-meter-data

# Tehtävä 4: Datan kuvaaminen 

* Millaisia muuttujia on datassa? kulutus päivämäärän mukaan, rivit ovat päivämäära ja sarakkeet kiinteistöjä, lisäksi viimeiset sarakkeet päivämäärän lisäksi erotettu päiväysleimasta seuraavat tiedot joita ei tarvitse näin "laskea" erikseen 
Year, Month, Day, Week, Weekday

lasketaan tyypilliset tilastolliset tunnusluvut kuten
lukumäärä,summa,keskiarvo,keskihajonta sekäminimi ja maksimi
#Tilastolliset tunnusluvut valituille kiinteistöille
kiinteistot = ['1', '873', '55']
df2.groupby("Year")[kiinteistot].agg([np.sum, np.mean, np.std, np.min, np.max])

* Mitä arvoa on käytetty täytearvona? 
käyttökatkot 
EKÄ TEHTÄVÄ/PÄÄTÖS mitä tehdään täytetarvoille????
-1.0, mitä näille tehdään tähän kuvaaja joissa ero keskiarvoissa
* Millaisia korrelaatioita datasta löytyy? ei oikein mitään, kun ei ole kuin yksi varisnianen muuttuja arvo (päivämärä mysö) ja ne on sidoksisaa johinkin kiinteistöön. 
* Tarkistelee dataa tietyillä aikaväleillä **(esim. viikko, kuukausi tai vuosi). Millaisia havointoja teet?**
* Havaintojen tueksi voi liittää kuvia datasta
* Mieti mitä tällä datalla voidaan mahdollisesti tehdä?

Palautetaan vastaus repositoryyn annettuun palautuspäivämäärään mennessä:
* Mielellään MarkDown-formaatissa (tarkenne .md), jolloin kuvat linkitetään dokumenttiin
* Vielä edistyneempi vaihtoehto on käyttää Jupyter Notebook-formaattia/dokumenttia palautukseen, jolloin dokumentti tulee suorittaa repositoryyn ennen tehtävän palauttamista, että kaikki tulokset ja kuviot näkyvät output-kentissä ilman ylimääräistä ajamista
* Vastauksen voi palauttaa myös PDF-formaatissa

Datan käsittely:
* Katso julkaistu [Yorkshire Water Jupyter Notebook -dokumentti](jupyter_data/YorkshireWater_data_analysointi.ipynb) 
* Tätä voitte käyttää apuna datan ymmärtämisessä
* Sitä voi myös täydentää lisähavaintojen ja -analyysin tekemiseen

**Lähteitä:**
* Video - **05 CRISP-DM Loppuosa**

Kannattaa myös katsoa seuraavat videot:
* **18: Data ja sen laatu**
* **19: Huono Data**
* **20: Laadun arviointi ja formaatit**

----------
## Tehtävä 4: Vastaus 

TODO: Jos kirjoitat vastauksen MarkDown-formaatissa, sen voi liittää suoraan tehtävädokumenttiin.
[MarkDown-tutorial](https://www.markdownguide.org/basic-syntax/).

----------
Esiemrkki yoershire water oli -0-1 arvo mitä niille tehdään pitääkö muuttaa NaN ja tehdä interpolaatio. toimiiko?
omaa pohdistaa ooli poistaa tai täyttää 0:lla.
http://hantt.pages.labranet.jamk.fi/datan-esikasittely/materiaali/01-pandas/
KErro jos ei käy ja miksei