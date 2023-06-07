# Pystysuuntainen kiihtyvä liike

Kun kappale putoaa, tai kun se heitetään suoraan alaspäin, tai kun se heitetään ylöspäin ja se lähtee sitten itsekseen putoamaan, niin kiihtyvyys on aina sama. Tällöin kiihtyvyyttä merkitään kirjaimella $g$ ja sen lukuarvona käytetään $g=9.81~\frac{\text{m}}{\text{s}^2}$. Kiihtyvyys johtuu painovoimasta Maan ja muiden kappaleiden välillä. Sen tarkka suuruus vaihtelee hieman eri puolilla Maapalloa ja riippuu mm. paikallisen kallioperän koostumuksesta sekä etäisyydestä Maan keskipisteeseen.

Pystysuuntaisen kiihtyvän liikkeen yhtälöt ovat melkein samanlaisia kuin vaakasuoran kiihtyvän liikkeen yhtälöt. Sijaintia merkitään nyt kirjaimen $x$ sijasta kirjaimella $y$. Vaakasuuntaisessa kiihtyvässä liikkeessä ei läheskään aina tarvittu alkuhetken sijaintia $x_0$, mutta pystysuuntaisessa kiihtyvässä liikkeessä alkukorkeus $y_0$ on tärkeä.

Vaakasuuntaisessa liikkeessä tavallinen tapa valita suunnalle merkki on se, että vasemmalta oikealle liikkuminen on positiivista ja oikealta vasemmalle negatiivista. Putoamislaskuissa suunta ylöspäin on positiivinen ja suunta alaspäin negatiivinen. Myös kiihtyvyyden eteen tulee miinusmerkki, koska kuten jokainen on varmasti huomannut, painovoiman takia esineiden suunta on alaspäin. Pystysuuntaisen kiihtyvän liikkeen yhtälöt ovat seuraavat:

- nopeusyhtälö $v=v_0-gt$

- paikkayhtälö $y=y_0 + v_0 t - \frac{1}{2} gt^2$

Tehtävissä loppukorkeus $y$ saatetaan ilmaista esimerkiksi muodossa "maassa" eikä suoraan lukuarvona $0~\text{m}$ kirjoitettuna. Lisäksi tehtävissä voidaan ilmaista esimerkiksi sanalla "putoaa" se, että kappaleen alkunopeus on 0 m/s. 

::::{admonition} Esimerkki

Kuumailmapallo on nousemassa ylöspäin nopeudella 5.0 m/s, kun siitä pudotetaan 25 m korkeudessa hiekkasäkki. Kuinka pitkän ajan päästä ja millä nopeudella hiekkasäkki osuu maahan?

:::{admonition} Ratkaisu
:class: tip, dropdown

Nopeus- ja paikkayhtälössä olevissa suureista tiedossa ovat seuraavat: 

$v_0=5.0~\frac{\text{m}}{\text{s}}, g=9.81~\frac{\text{m}}{\text{s}^2}, y_0=25~\text{m}, y=0~\text{m}$

Jätetään tuntemattomaksi jäävät $t$ ja $v$ yhtälöihin ja syötetään yhtälöt WolframAlphaan:

solve v=5-9.81\*t, 0=25+5\*t-0.5\*9.81\*t^2

Ensimmäinen ratkaisuvaihtoehto on $t\approx -1.80475, v \approx 22.7046$ ja toinen vaihtoehto on $t \approx 2.82412, v \approx -22.7046$. Näistä oikea valinta on jälkimmäinen, sillä siinä aika on positiivista. Negatiivinen nopeus tarkoittaa sitä, että säkki on menossa alaspäin, mikä on myös järkevää.

Halutessaan ongelman voisi ratkaista myös selvittämällä ensin paikkayhtälöstä putoamiseen kuluvan ajan $t$, ja sijoittamalla sen sitten nopeusyhtälöön.

:::

::::

::::{admonition} Esimerkki

Tornista pudotettiin pikkukivi. Kivi osui maahan 1.7 sekunnin kuluttua putoamisesta. Kuinka korkea torni on?

:::{admonition} Ratkaisu
:class: tip, dropdown

Vaikka tehtävänannossa on annettu vain yksi suureen arvo, $t=1.7~\text{s}$, voidaan päätellä monta muutakin arvoa:

- pudottaminen tarkoittaa, että $v_0=0~\frac{\text{m}}{\text{s}}$

- kiihtyvyys on aina sama, $g=9.81~\frac{\text{m}}{\text{s}^2}$,

- loppusijainti on maassa, $y=0~\text{m}$

Nopeus- ja paikkayhtälö voidaan siis kirjoittaa WolframAlphaan muodossa:

solve 0=y-0.5\*9.81\*1.7^2, v=-9.81\*1.7

Näistä toki riittäisi ensimmäinenkin yhtälö, sillä loppunopeutta $v$ ei edes kysytty. Ensimmäisestä yhtälöstä saadaan kynällä ja paperillakin laskemalla

$y=0.5\cdot 9.81~\frac{\text{m}}{\text{s}^2} \cdot (1.7~\text{s})^2 \approx 14.2~\text{m}$.

Tätä voit kokeilla käytännössä vaikka näköalatornissa, kunhan tornin alla ei ole ketään!

:::

::::

Jos kappale on heitetty ylös, sen nopeus on hetkellisesti 0 m/s juuri silloin, kun se lähtee putoamaan alaspäin. Tällä periaatteella voidaan laskea lakikorkeus, eli se korkeus, jolla kappale enimmillään käy. Jos tehtävän haluaa ratkaista käsin, niin  ensin pitäisi laskea aika $t$, jolloin nopeus on nolla, ja sen jälkeen tämä aika pitäisi sijoittaa paikkayhtälöön. Ajan saa ratkaistua seuraavasti:

$0=v_0-gt \Leftrightarrow gt=v_0 \Leftrightarrow t=\frac{v_0}{g}$

::::{admonition} Esimerkki

Pallo heitetään ylöspäin nopeudella 3 m/s. 

a) Kuinka korkealla pallo käy heittokorkeudesta mitattuna?

b) Kuinka korkealla pallo käy maasta mitattuna, jos heitto tapahtuu 1.5 m korkeudelta?

:::{admonition} Ratkaisu
:class: tip, dropdown

Kummassakin tapauksessa huippukorkeus saavutetaan hetkellä $t=\frac{3~\frac{\text{m}}{\text{s}}}{9.81~\frac{\text{m}}{\text{s}^2}} = 0.306~\text{s}$.

a) Asetetaan heittokorkeudeksi $0~\text{m}$. Tällöin huippukorkeus on $y=3~\frac{\text{m}}{\text{s}} \cdot 0.306~\text{s} -\frac{1}{2} \cdot 9.81~\frac{\text{m}}{\text{s}^2}\cdot (0.306~\text{s})^2 = 0.46~\text{m}$.

b) Alkuhetken sijainti on nyt $y_0=1.5~\text{m}$. Lakipisteessä korkeus on $y=1.5~\text{m}+3~\frac{\text{m}}{\text{s}} \cdot 0.306~\text{s} -\frac{1}{2} \cdot 9.81~\frac{\text{m}}{\text{s}^2}\cdot (0.306~\text{s})^2 = 1.96~\text{m}$

WolframAlphalla ratkaisu onnistuisi seuraavasti:

a) solve 0=3-9.81\*t, y=3\*t-0.5*9.81\*t^2

a) solve 0=3-9.81\*t, y=1.5+3\*t-0.5*9.81\*t^2

:::

::::