# Ympyräliike

![Liike ympyräradalla](ympyra.png "Liike ympyräradalla")

Olkoon ympyrän säde $r$ (m) ja ympyräradalla liikkuvan kappaleen nopeus $v$ (m/s). Koska ympyrän kehän pituus on $2\pi r$, niin yhteen kierrokseen kuluvalla ajalla eli kierrosajalla $T$ (s), säteellä $r$ ja nopeudella $v$ on yhteys

$v=\frac{2\pi r}{T}$

Lisäksi voidaan määritellä 

- kierrostaajuus $f=\frac{1}{T}$ (yksikkö $\frac{1}{s}$ eli hertsi, Hz), joka kertoo kuinka monta kierrosta sekunnissa edetään, 
- kulmataajuus $\omega=\frac{2\pi}{T}$, joka kertoo kuinka suuren kulman ympäri kappale kiertää sekunnissa.

Kulmaa mitataan radiaaneina. Kulmataajuus voidaan esittää myös sijoittamalla $f=\frac{1}{T}$, jolloin kulmataajuudeksi tulee $\omega=2\pi f$.
    
::::{admonition} Esimerkki

a) Polkupyörän takapyörän säde on $r=0.35~\text{m}$. Pyöräilijä ajaa nopeudella 20 km/h. Paljonko on renkaan pyörähdysaika, kierrostaajuus ja kulmataajuus?

b) Paljonko pitäisi olla kierrostaajuuden, jotta pyöräilijä liikkuisi kävelynopeudella 5 km/h? Entä paljonko pitäisi olla pyörän säteen, jotta tämä kierrostaajuus riittäisi nopeuteen 20 km/h?

:::{admonition} Ratkaisu
:class: tip, dropdown

a) Nopeuden määritelmästä saadaan ratkaistua pyörähdysaika

$T=\frac{2\pi r}{v}=\frac{2\pi \cdot 0.35~\text{m}}{20/3.6~\text{m/s}}\approx 0.396~\text{s}$

Kierrostaajuudeksi saadaan $f=\frac{1}{T}=\frac{1}{0.396~\text{s}}\approx 2.53~\frac{1}{\text{s}}$

ja kulmataajuudeksi $\omega=\frac{2\pi}{T}=\frac{2\pi}{0.396~\text{s}} = 15.9~\frac{1}{\text{s}}$ tai $2\pi f=2\pi\cdot 2.53~\frac{1}{\text{s}} = 15.9~\frac{1}{\text{s}}$.

b) Nopeuden määritelmään $v=\frac{2\pi r}{T}$ voidaan sijoittaa taajuuden määritelmä $f=\frac{1}{T}$. Tällöin nopeuden laskukaavaksi muodostuu $v=2 \pi r f$, josta voidaan ratkaista $f=\frac{v}{2\pi r}$, siis

$f=\frac{5/3.6~\text{m/s}}{2\pi \cdot 0.35~\text{m}}\approx 0.63~\frac{1}{\text{s}}$.

Jos poljettaisiin tällä taajuudella siten, että nopeus olisi 20 km/h, niin renkaan säteen tulisi olla

$r=\frac{20/3.6~\text{m/s}}{2\pi\cdot 0.63~\text{1/s}}\approx 1.4~\text{m}$.

:::

::::