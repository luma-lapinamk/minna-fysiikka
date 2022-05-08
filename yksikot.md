# Suureet ja yksiköt

Fysiikassa ei juuri koskaan lasketa pelkillä luvuilla, vaan laskuissa olevat luvut kuvaavat esim. pituutta, aikaa, sähköjännitettä ym. Mitattavien asioiden suuruutta kutsutaan nimellä suure. Suure sisältää mittaluvun ja yksikön. Esim. 170 cm on pituus-niminen suure, joka sisältää mittaluvun 170 ja yksikön cm. Tässä luvussa perehdytään suureiden ja niiden yksiköiden esitysmuotoihin.

## Perussuureet ja -yksiköt

Melkein kaikilla suureilla on yksikkö. Niin sanotussa SI-järjestelmässä perussuureita on olemassa vain 7 kappaletta. Suureilla on omat vakiintuneet tunnuksensa, jotka on esitetty taulukossa. Laskuissa suureita voi merkitä millä kirjaimella haluaa, kunhan vain itse tietää, mitä omat merkinnät tarkoittavat.

Jokaisella perussuureella on myös oma yksikkönsä. Lähtökohtaisesti luvut pitää laittaa fysiikan kaavoihin näissä yksiköissä ilmaistuna. Esimerkiksi matka pitää laittaa metreinä, vaikka kyse olisi Maan ja Auringon välisestä 150 miljoonasta kilometristä tai jonkin modernin nanoteknologian rakenteen muutamasta mikrometristä. 

|Suure|Tunnus|Yksikkö|Lyhenne|
---------|----|------|--------|
|pituus|$l$ (tai $s$, $x$)|metri|m|
|aika|$t$|sekunti|s|
|massa|$m$|kilogramma|kg|
|lämpötila|$T$|kelvin|K|
|sähkövirta|$I$|ampeeri| A|
|ainemäärä|$n$|mooli|mol|
|valovoima|$l$|kandela|cd|

Suureiden tunnukset on tapana kirjoittaa kursiivilla ja yksiköiden lyhenteet tavallisilla kirjaimilla. Käsin kirjoitettaessa tällä ei ole merkitystä. Suureita ja niiden yksiköitä yhdistää seuraava merkintätapa: ”pituuden yksikkö on metri” kirjoitetaan $[l]=\text{m}$. 

## Johdannaissuureet ja -yksiköt

Kaikki muut kuin perussuureet ja -yksiköt saadaan perussuureista ja -yksiköistä kerto- ja jakolaskuilla. Esimerkiksi nopeuden yksikkö on matkan yksikkö jaettuna ajan yksiköllä; tiheyden yksikkö on massan yksikkö jaettuna tilavuuden yksiköllä jne. Näiden ns. johdannaissuureiden ja johdannaisyksiköiden määrittely vaatii tietoa siitä fysiikan ilmiöstä, jota kyseinen suure kuvaa, eikä ole aina helppoa. Joskus se on toki suoraviivaista.

Useimmilla johdannaisyksiköillä on erityisnimi, esimerkiksi voiman yksikkö newton tai paineen yksikkö pascal. Kaikki johdannaisyksiköt voidaan kuitenkin esittää myös perusyksiköiden avulla.

**Esim.** Pinta-alan $A$ yksikkö on neliömetri, koska pinta-ala esimerkiksi suorakulmiolle lasketaan sivujen pituuksien tulona, ja sivujen pituuksien yksikkö on metri.

Siis $[A]=\text{m}^2$, sillä $[A]=[l]⋅[l]=\text{m}\cdot\text{m}=\text{m}^2$.

**Esim.** Sähköjohtimen resistanssi $R$ kuvaa johtimen kykyä vastustaa sähkövirran kulkua. Se riippuu johtimen materiaalista, pituudesta ja läpimitasta sekä jännitteestä ja sähkövirrasta siten, että 

$[R]=\frac{\text{m}^2 \cdot \text{kg}}{\text{s}^3 \text{A}^2}$.

Yksikkö on aika monimutkainen. Sillä onkin onneksi erityisnimitys ohmi ($\Omega$).

Yksiköiden pitäminen mukana laskuissa auttaa tarkistamaan, onko lasku oikein. Tämä on käyttökelpoinen tieto opintojakson tenttiä ajatellen! Lisäksi jos esimerkiksi raportoidaan mittausten tuloksia asiakkaille tai yhteistyökumppaneille, pitää tuloksissa aina olla yksiköt mukana. 

**Esim.** Ajetaan autolla matka $s=115~\text{km}$ ajassa $t=1.5~\text{h}$. Millä seuraavista kaavoista saadaan auton keskinopeus $v$? Päättele oikea laskukaava saadun vastauksen yksikön perusteella. Vaihtoehdot: $v=st$, $v=\frac{t}{s}$ ja $v=\frac{s}{t}$.


:::{admonition} Ratkaisu
:class: tip, dropdown

$v=st$: tulokseksi tulee $115~\text{km}\cdot 1.5~\text{h} = 172.5~\text{km}\cdot \text{h}$ - ei vaikuta oikealta

$v=\frac{t}{s}$: tulokseksi tulee $\frac{1.5~\text{h}}{115~\text{km}} = 0.01~\frac{\text{h}}{\text{km}}$ - tämäkään ei vaikuta oikealta

$v=\frac{s}{t}$: tulokseksi tulee $\frac{115~\text{km}}{1.5~\text{h}} = 76.7~\frac{\text{km}}{\text{h}}$ - oikein!

:::


## Suureyhtälöt

Suureyhtälö tarkoittaa fysiikan "laskutoimitusta" ilman suureiden lukuarvoja. Suureyhtälön avulla saa yleiskäsityksen jonkin fysiikan ilmiön luonteesta: miten jonkin suureen kasvaminen tai pieneneminen vaikuttaa johonkin toiseen suureeseen? Suureyhtälössä esiintyvien yksiköiden avulla voi myös tarkistaa, onko yhtälö oikein, ja jopa rakentaa sen itse.

**Esim.** Päätellään suureyhtälön avulla, miten ilmanvastus muuttuu eri tilanteissa. 

Etsitään ilmanvastusta kuvaava suureyhtälö:

$F=\frac{1}{2} c \rho A v^2$

Yhtälössä $c$ on ns. aerodynaaminen muotovakio, $\rho$ on ilman tiheys, $A$ on ilmavirtaa vasten kohtisuora pinta-ala ja $v$ on nopeus. Miten ilmanvastus muuttuu, jos 

a) nopeus kasvaa 10 %, b) pinta-ala kasvaa 10 %, c) molemmat kasvavat 10% ?

:::{admonition} Ratkaisu
:class: tip, dropdown

Merkitään alkuperäistä, vaikkakin tuntematonta, ilmanvastusta alaindeksillä 1, siis $F_1=\frac{1}{2} c \rho A v^2$.

a) Jos nopeus kasvaa 10 %, niin kaavaan on sijoitettava nopeuden $v$ paikalle uusi nopeus $1.1v$. Tällöin uusi ilmanvastus on

$F_2=\frac{1}{2} c \rho A (1.1v)^2 =\frac{1}{2} c \rho A \cdot 1.21 v^2 = 1.21 F_1$ 

eli 21 % alkuperäistä suurempi.

b) Jos pinta-ala kasvaa 10 %, niin kaavaan on sijoitettava alan $A$ paikalle uusi arvo $1.1A$. Tällöin uusi ilmanvastus on

$F_2=\frac{1}{2} c \rho \cdot 1.1 A v^2 = 1.1 F_1$ eli 10 % alkuperäistä suurempi.

c) Jos molemmat arvot kasvavat yhtä aikaa 10 %, niin ilmanvastukseksi tulee

$F_2=\frac{1}{2} c \rho \cdot 1.1 A \cdot (1.1v)^2 = 1.33 F_1$ eli 33 % alkuperäistä suurempi.

:::

**Esim.** Voiko olla mahdollista, että vesisäiliössä olevan veden virtausnopeutta (metreinä sekunnissa) säiliössä olevasta aukosta kuvaa yhtälö $v=2gh$, missä $g=9.81~\frac{\text{m}}{\text{s}^2}$ ja $h$ on vedenpinnan ja aukon välinen korkeusero metreinä?

:::{admonition} Ratkaisu
:class: tip, dropdown

Yhtälön mukaan nopeuden yksikkö on $[v]=[g][h]=\frac{\text{m}}{\text{s}^2}\cdot\text{m}=\frac{\text{m}^2}{\text{s}^2}$.

Annettu yhtälö ei voi olla oikein, koska yksiköksi ei tullut $\frac{\text{m}}{\text{s}}$.

Neliöjuuren ottaminen antaa oikean yksikön: $\sqrt{\frac{\text{m}^2}{\text{s}^2}}=\frac{\text{m}}{\text{s}}$.

Niinpä annettu yhtälö ei ole oikein. Toimiva yhtälö voisi olla $v=\sqrt{2gh}$.

Yksiköistä ei tosin voi päätellä, kuuluuko myös kerroin 2 neliöjuuren sisälle, tai onko se ylipäätään oikea luku. Tässä tapauksessa luku on oikea. Kyseinen yhtälö on Torricellin laki, johon palataan virtausfysiikassa. 

:::