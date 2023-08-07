# Suureiden esitystarkkuus

Usein laskun tulos on päättymätön tai ainakin hyvin pitkä desimaaliluku. Luvun voi katkaista sopivasta kohdasta. Jos ensimmäinen pois jäävä numero on 5 tai suurempi, niin viimeistä lukuun jäävää numeroa pitää kasvattaa yhdellä.

**Esim.** $9.34573142 \approx 9.346$ tai $9.3457$

Luvun tarkkuuden voi ilmoittaa merkitsevien numeroiden määrällä (näitä ovat kaikki paitsi kokonaisluvun lopussa ja desimaaliluvun alussa olevat nollat), desimaalien määrällä tai viimeisen numeron yksiköllä, jos luvulla on yksikkö.

Sopiva esitystarkkuus määräytyy fysiikassa siitä periaatteesta, että "huonoin" käytettävissä oleva mittaväline määrää koko lopputuloksen tarkkuuden. Esimerkiksi metrimitalla ja mikrometriruuvilla otettuja mittoja ei ole mielekästä laskea yhteen.

**Esim.** Esitä luvut annetulla tarkkuudella:

a) 10 801 kolmen merkitsevän numeron tarkkuudella: **108**00

b) 0.050120 kolmen merkitsevän numeron tarkkuudella: 0.0**501**

c) 55.555 kahden desimaalin tarkkuudella: 55.**56**

d) 10.2017 kahden desimaalin tarkkuudella: 10.**20**

e) 1762.35 grammaa kilogramman tarkkuudella: suureen arvo on 1.76235 kg eli **2** kg

f) 114.875 metriä senttimetrin tarkkuudella: suureen arvo 11487.5 cm eli 1148**8** cm

Laskutoimituksien tulokset esitetään yleensä seuraavien sääntöjen mukaan
- yhteen- ja vähennyslaskut: niin monta desimaalia kuin epätarkimmassa luvussa on
- kerto- ja jakolaskut: niin monta merkitsevää numeroa kuin epätarkimmassa luvussa on
- välituloksissa käytetään yhtä merkitsevää lukua enemmän kuin pitäisi
- säännöt koskevat samoissa yksiköissä esitettyjä lukuja

::::{admonition} Esimerkki

Esitä järkevällä tarkkuudella:

a) $125~\text{nm} + 0.16~\mu\text{m}$

b) $22.3~\text{mg}+0.1~\text{ml}\cdot 12~\text{g/ml}$

c) Vanerilevyn pituus on 160 cm, leveys 70 cm ja paksuus $h=18~\text{mm}$. Materiaalin tiheys $\rho$ on valmistajan mukaan noin $680~\frac{\text{kg}}{\text{m}^3}$. Kuinka suuri on levyn massa? Massa lasketaan $m=\rho V$, missä $V=Ah$ ja $A$ on levyn pinta-ala eli pituuden ja leveyden tulo.

:::{admonition} Ratkaisu
:class: tip, dropdown

a) $125~\text{nm} + 0.16~\mu\text{m} = 125~\text{nm} + 160~\text{nm} = 285~\text{nm} \approx 290 ~\text{nm}$ 

b) $22.3~\text{mg}+0.1~\text{ml}\cdot 12~\text{g/ml}=$

$ 22.3~\text{mg}+1.20~\text{g}= 22.3~\text{mg}+1200~\text{mg} = 1222~\text{mg}$

c) Tilavuuden laskemiseksi mitat on muutettava samaan yksikköön. Helpoiten laskusta selviää, kun muuttaa mitat metreiksi: pituus 1.60 m, leveys 0.70 m ja paksuus 0.018 m. Tilavuus on $V=1.60~\text{m}\cdot0.70~\text{m} \cdot 0.018~\text{m}=0.02016~\text{m}^3$.

Massa on $680~\frac{\text{kg}}{\text{m}^3}\cdot 0.02016~\text{m}^3=13.7088~\text{kg}$. Kuitenkin tiheys tunnetaan vain kahden merkitsevän numeron tarkkuudella ja levyn pituus ja leveyskin ovat luultavasti pyöristettyjä arvoja. Niinpä järkevä tarkkuus voisi olla 14 kg.

:::

::::