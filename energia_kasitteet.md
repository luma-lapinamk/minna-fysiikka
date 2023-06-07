# Käsitteitä

Energia on eräs tärkeimmistä fysiikan käsitteistä. Erityisen merkittävää on energian säilyminen: energiaa voi esiintyy erilaisissa muodoissa, mutta energian määrä ei muutu mihinkään. Energiaa esiintyy monissa muodoissa, esimerkiksi sähkönä, lämpönä, kappaleiden liikkeenä tai ruoan sisältämänä kemiallisena energiana. Esimerkiksi kun poltetaan puuta, niin polttopuun molekyylien sidoksissa esiintyvä kemiallinen energia muuttuu lämpöenergiaksi. Jos polttaminen tapahtuu sisällä talossa takassa, tarvitaan vielä tietoa energian siirtymisestä, jotta lämpö saadaan pysymään sisällä talossa. Sitä käsitellään esimerkiksi [lämpöopin](https://luma-lapinamk.github.io/minna-lampooppi/intro.html) opintojaksolla.

## Energia, työ ja teho

Tällä opintojaksolla keskitytään tarkastelemaan mekaanista energiaa. Mekaaninen energia voidaan määritellä kykynä tehdä mekaanista työtä. Fysiikassa mekaaninen työ $W$ tarkoittaa kappaleen siirtämistä. Siirtämiseen tarvitaan voimaa. Työn yksikkö onkin voiman yksikkö kerrottuna siirtomatkan yksiköllä: siis Nm, mistä käytetään yleisesti nimitystä joule (J). 

- Kun voima $F$ siirtää kappaletta matkan $s$ voiman suunnassa, niin voiman $F$ tekemä työ on $W=Fs$.

- Kun voima $F$ siirtää kappaletta matkan $s$, ja voiman ja siirtymän välinen kulma on $\alpha$, niin voiman $F$ tekemä työ on
$W=Fs \cos{\alpha}$.

- Kun esinettä nostetaan, niin tarvittavan voiman suuruus on sama kuin esineeseen kohdistuvan painovoiman suuruus. Työ on siis painovoiman $mg$ ja nostokorkeuden $h$ tulo, $W=mgh$.

Muussa kuin nostamisen tapauksessa voimalle ei ole mitään yleispätevää laskukaavaa. Voimia voidaan laskea samaan tapaan kuin Newtonin lakien tai ympyräliikkeen yhteydessä. Esimerkiksi kun satelliitit kiertävät Maata, niin satelliitin radallaan pitävä voima on maapallon ja satelliitin välinen gravitaatiovoima, jolle on oma laskukaavansa. Voiman ja satelliitin siirtymän (eli kiertoradan tangentin) välinen kulma on 90 astetta, joten tehty työ on 0 J.

::::{admonition} Esimerkki

Paljonko tehdään työtä, kun vedetään laatikkoa 160 N voimalla 2.5 metriä

a) suoraan eteenpäin, 

b) 30 asteen kulmassa?

:::{admonition} Ratkaisu
:class: tip, dropdown

a) $W=160~\text{N}\cdot 2.5~\text{m}=400~\text{Nm}=400~\text{J}$

b) $W=160~\text{N}\cdot 2.5~\text{m} \cdot \cos{30^{\circ}} = 346~\text{J}$

:::

::::

::::{admonition} Esimerkki

Laske tehty työ, kun nostetaan

a) 100 g painava kirja 100 cm korkealle hyllylle,

b) 5000 kg painava kontti laiturilta 8 m korkealle laivan kannelle 

c) 80 kg painava ihminen Saana-tunturille 500 m korkeuteen

:::{admonition} Ratkaisu
:class: tip, dropdown

a) $W=mgh=0.1~\text{kg}\cdot 9.81~\frac{\text{m}}{\text{s}^2}\cdot 1.00~\text{m}=0.98~\text{J}$

b) $W=5000~\text{kg}\cdot 9.81~\frac{\text{m}}{\text{s}^2}\cdot 8~\text{m}=392400~\text{J} \approx 400~\text{kJ}$

c) $W=80~\text{kg}\cdot 9.81~\frac{\text{m}}{\text{s}^2}\cdot 500~\text{m}=392400~\text{J} \approx 400~\text{kJ}$

:::

::::

Myös energian yksikkö on joule. Yksi joule riittää nostamaan omenan metrin korkeuteen. Syömällä sama omena saadaan energiaa 135 000 joulea. Suuri osa energiasta muuttuu lämmöksi, kuten omenan energia elimistössä. Tällöin energia ei häviä, mutta se karkaa ulottuviltamme, eikä sitä voida enää hyödyntää muun työn tekemiseen. Esimerkiksi tehtaissa liukuhihnoilla esiintyvä kitka voi aiheuttaa merkittävää energiahäviötä.

Teho $P$ tarkoittaa tehdyn työn määrää jaettuna työhön kuluneella ajalla, siis $P=\frac{W}{t}$. Kyseessä on keskimääräinen teho. Todellinen teho suorituksen aikana voi vaihdella paljonkin, ihan samalla tavalla kuin nopeuskin voi matkan aikana poiketa paljonkin koko matkan keskinopeudesta.

Tehon yksiköstä on J/s käytetään erityisnimeä watti, ja sen lyhenne on W. Siis tehon yksikkö on sama kirjain kuin työn tunnus! Jos tarkkoja ollaan, niin fysiikassa suureiden tunnuksia merkitään kursiivilla ja yksiköitä tavallisilla kirjaimilla: siis $[W]=\text{J}$ ja $[P]=\text{W}$. 

Teholle käytetään joskus myös yksikköä hevosvoima. Nimestään huolimatta se on siis tehon yksikkö. Yksi hevosvoima vastaa 75 kg kuorman nostamista nopeudella 1 m/s. Laskemalla saadaan yhtä hevosvoimaa vastaavaksi tehoksi noin 736 W.

Tehon laskukaavaan työn paikalle tuleva lauseke riippuu siirtotyöstä. Nostotyössä sen paikalle tulee painovoiman ja nostokorkeuden tulo. Tasaisessa liikkeessä voidaan ilmaista siirtomatka $s$ nopeuden $v$ ja ajan $t$ avulla, siis $s=vt$. Tällöin $P=\frac{Fs}{t}=\frac{Fvt}{t}=Fv$.

::::{admonition} Esimerkki

Painonnostaja nostaa 130 kg rautaa 1.5 metrin korkeuteen 1.2 sekunnissa. Laske teho noston aikana.

:::{admonition} Ratkaisu
:class: tip, dropdown

$P=\frac{W}{t}=\frac{mgh}{t}=\frac{130~\text{kg} \cdot 9.81~\frac{\text{m}}{\text{s}^2} \cdot 1.5~\text{m}}{1.2~\text{s}}=1594~\text{W }= 1.6~\text{kW}$

:::

::::

::::{admonition} Esimerkki

Autolla ajetaan nopeudella 100 km/h. Ilman vastusvoima on 280 N. Kuinka suurella teholla auto toimii ilmanvastusta vastaan? 

:::{admonition} Ratkaisu
:class: tip, dropdown

$P=Fv=280~\text{N}\cdot \frac{100}{3.6}~\frac{\text{m}}{\text{s}} = 7777.78~\frac{\text{Nm}}{\text{s}} = 7.8~\text{kW}$

:::

::::

Sähkölaskusta tuttu yksikkö kilowattitunti kWh tarkoittaa 1000 watin teholla työskentelyä yhden tunnin ajan. Jouleina 1 kWh on siis  $1000~\text{W}\cdot 1~\text{h}=1000~\frac{\text{J}}{\text{s}}\cdot 3600~\text{s}=3.6~\text{MJ}$. Sähköön liittyviä energiamääriä voidaan ilmaista myös wattitunteina (Wh), esim. auton akussa on noin 600-700 Wh ja AA-paristossa 2-3 Wh. 


## Hyötysuhde

Energiantuotantolaitosten tehot, joilla ne tuottavat sähköenergiaa, ovat esim. vesivoimaloissa muutamia kymmeniä tai satoja megawatteja, ydinvoimaloissa 1600-2000 MW. Saunan kiukaan teho on noin 6000 W ja hehkulampun teho 40 W. Laitteiden tehoilla tarkoitetaan sitä energiamäärää, jonka laite käyttää omaan toimintaansa tietyssä ajassa. Varsinainen laitteen tekemä työ samassa ajassa voi olla pienempi. 

Hyötysuhde $\eta$ (”eeta”) määritellään koneen käyttöön tuottaman tehon ja vastaanottaman tehon suhteena: 

$\eta=\frac{P_{\text{anto}}}{P_{\text{otto}}}$

Tehon määritelmä huomioiden hyötysuhde voidaan myös esittää tietyssä ajassa tehdyn työn ja kulutetun energian suhteena.

Kaikista koneista menee energiaa hukkaan mm. kitkan aiheuttaman lämmön muodossa. Auton moottorin hyötysuhde on vain noin 20 %, eli 80 % bensiinin sisältämästä kemiallisesta energiasta muuttuu lämmöksi. Sähkömoottoreissa hyötysuhde voi olla jopa 97 %.

::::{admonition} Esimerkki

Liukuportaat nostavat matkustajia metroasemalta 30 m matkan ylöspäin katutasolle. Ruuhka-aikana määrä voi olla 120 ihmistä minuutissa. Laske portaiden kuluttama sähköteho, jos matkustajan keskimääräinen paino on 75 kg ja koneen hyötysuhde on 70 %.

:::{admonition} Ratkaisu
:class: tip, dropdown

Ratkaistaan hyötysuhteen määritelmästä ottoteho: $P_{\text{otto}}=\frac{P_{\text{anto}}}{\eta}=\frac{mgh}{t\cdot \eta}$

Sijoitetaan luvut:

$P_{\text{otto}}=\frac{75~\text{kg}\cdot 9.81~\frac{\text{m}}{\text{s}^2} \cdot 30~\text{m}}{60~\text{s} \cdot 0.70}=63064~\text{W} = 63~\text{kW}$

:::

::::

::::{admonition} Esimerkki

Auton moottorin tehosta suuri osa tarvitaan ilmanvastuksen voittamiseen. Henkilöauton aerodynaaminen muotovakio on $c=0.33$ ja etenemissuuntaa vastaan kohtisuora pinta-ala $A$ on 2.4 neliömetriä. Ilman vastusvoima lasketaan kaavalla $F=\frac{1}{2}c \rho A v^2$, missä $\rho=1.25~\frac{\text{kg}}{\text{m}^3}$ on ilman tiheys ja $v$ on liikkuvan kappaleen nopeus. Laske polttoaineen kulutus 100 km matkalla, kun ajetaan nopeudella 100 km/h. Auton hyötysuhde on 24 % ja bensiinin lämpöarvo on 24 MJ/l. Laske myös auton teoreettinen maksiminopeus, jos auton moottorin maksimiteho on 55 kW.

:::{admonition} Ratkaisu
:class: tip, dropdown

Lasketaan aluksi ilmanvastus nopeudessa 100 km/h:

$F=\frac{1}{2} \cdot 0.33 \cdot 1.25~\frac{\text{kg}}{\text{m}^3} \cdot 2.4~\text{m}^2 \cdot \left(\frac{100}{3.6} ~\frac{\text{m}}{\text{s}}\right) ^2 = 382~\text{N}$

Moottorin tekemä työ, eli autoa todella eteenpäin liikuttava "antotyö", ilmanvastusta vastaan 100 km matkalla on siis: 

$W_{\text{anto}}=Fs=382~\text{N} \cdot 100 000~\text{m}=38.2~\text{MJ}$

Moottorin käyttämä energia saadaan hyötysuhteen perusteella:

$W_{\text{otto}}=\frac{W_{\text{anto}}}{\eta}= \frac{38.2~\text{MJ}}{0.24} = 159.2~\text{MJ}$.

Polttoainetta tarvitaan $\frac{159.2~\text{MJ}}{24~\frac{\text{MJ}}{\text{l}}}=6.63~\text{l}$.

Maksiminopeus saadaan yhtälöstä $P=Fv$, kun asetetaan tehon paikalle moottorin maksimiteho 55 kW ja ilmanvastuksen paikalle sen laskukaava:

$P=Fv$

$P=\frac{1}{2}c \rho A v^2\cdot v$

$P=\frac{1}{2}c \rho A v^3$

$v=\sqrt[3]{\frac{2P}{c \rho A}}$

$v = \sqrt[3]{\frac{2\cdot 55\cdot 10^3~\frac{\text{kgm}^2}{\text{s}^3}}{0.33\cdot 1.25~\frac{\text{kg}}{\text{m}^3} \cdot 2.4~\text{m}^2}} = 48.1~\frac{\text{m}}{\text{s}} = 173~\frac{\text{km}}{\text{h}}$

:::
 
::::