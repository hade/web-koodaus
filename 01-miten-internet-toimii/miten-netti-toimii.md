title: Miten netti toimii
author:
  name: Hannu Korhonen
  github: hade
output: esitys.html
controls: true
style: ../asset/cleaver-style.css
--

# Miten Internet toimii

--

### Yhteenliitettyjä koneita
- Hurja määrä erilaisia laitteita, jotka keskustelevat keskenään.
- Läppäreitä, puhelimia, autoja, valtavia konesaleja

--

### Kaksi konetta
Venla ja Lilja haluavat järjestää lanit. Ensin he liittävät koneet toisiinsa. 

 ![kaksi konetta](img/kaksi-konetta.svg)

 https://www.youtube.com/watch?v=lcb8uafr0cw

--

### Kolme konetta
Jani-Petteri tulee kylään ja hänet liitetään verkkoon.  

 ![kolme konetta](img/kolme-konetta.svg)

--

### Neljä konetta  
Myös Pertti saapuu paikalla. Vähän myöhässä, kuten tavallista. Pertti liitetään verkkoon. 

 ![nelja konetta](img/nelja-konetta.svg)  

--

### Viisi konetta  
Pertti lähettää ystävälleen Titalle savumerkkejä ja pyytää hänet mukaan laneihin. Lilja hakee varastosta lisää kaapelia.

 ![viisi konetta](img/viisi-konetta.svg)  

--

### Kuusi konetta  
Miia saapuu paikalle viimeisenä. Aika hämähäkinseitti!

 ![kuusi konetta](img/kuusi-konetta.svg)  

--

### Miten Internet voi toimia?
Miten Internet on rakennettu, jos jo kuudella lanittajalla tulee monimutkainen verkko!

--

### Reititin to the rescue!
Reititin välittää viestit muille lanittajille.

 ![reititin](img/reititin.svg) 

--

### Reititin välittää 💕
Jos vaikkapa Miia haluaa jutella Pertin kanssa. 

 ![reitti](img/reitti.svg) 

--

### Naapurin lanit
Naapurissa on samanlaiset lanit. What?!?

 ![naapuri](img/naapuri.svg)

-- 

### Naapurin lanit
Reititin taas apuun

 ![naapuri-reititin](img/naapuri-reititin.svg)

-- 

### Internet on verkkojen verkko
Verkkoja verkkojen sisällä.

 ![internet](img/internet.svg)

-- 

### Miltä Internet näyttää?

Internetin "selfie" vuodelta 2005. Tässä näkyy vain pieni osa. 

https://ha.wikipedia.org/wiki/Yanar_gizo#/media/File:Internet_map_1024_-_transparent,_inverted.png

--

### Internetin palvelut
Internetissä on paljon palveluita, muitakin kuin Webbi. Esimerkiksi sähköposti.

--

### World Wide Web
- Rakkaalla lapsella monta nimeä
- WWW, Web, Webbi
- Internetissä toimiva palvelu, jossa selaimella luetaan verkkosivuja. 
- Monesti WWW ja Internet sekoitetaan keskenään, vaikka WWW on vain yksi Internetin palveluista. 
- WWW:llä jaetaan erilaista tietoa (tekstiä, kuvaa, ääntä, videoita) selaimen ja verkkosivujen avulla. 

--

### Muistettavat asiat
- Internet on verkkojen verkko
- Internetissä on paljon eri palveluita, joista WWW on suosituin
- WWW = World Wide Web = Web = Webbi
- Palvelu, jossa verkkoselaimella (esim. Chrome) luetaan verkkosivuja (esim. www.yle.fi)

--

### Miten Web toimii?

- Internetissä on satoja miljoonia palvelimia (Server). 
- Palvelin on tietokone, joka **palvelee** sen asiakkaita. Web-pavelin palvelee Web-asiakkaita (Client), eli selaimia (Browser).
- Etsi kuvahaulla "konesali".

--

### Venla hakee Netflixistä Winx-aiheisia sarjoja
1. Venla avaa selaimen,
1. kirjoittaa selaimeen www.netflix.com,
1. kirjautuu,
1. kirjoittaa hakukenttään haun ja
1. hakutulokset näkyvät selaimessa.

--

### Netflix-haku
 ![winx-haku](img/winx-haku.svg)

--

### Webin pelisäännöt
- Protokolla tarkoittaa yhteisesti sovittuja **sääntöjä**. 
- HTTP (Hyper Text Transfer Protocol) on Webin yhteisesti sovitut säännöt. 
- Ohjeet, miten selain saa kyseltyä verkkosivuja palvelimelta. 

--

### Leikki: Client & Server
- Tarvikkeet:
  - värikynät
  - kolmen värisiä post-it -lappuja
  - laatikko
  - kirjoituskynä posti-it -lapuille
  - pahvinpalasia

--

### Leikki: Client & Server
- Valitaan käyttäjä, selain (Client) ja palvelin (Server)
- Kurssin vetäjän kannattaa olla käyttäjä
- Pahvinpalasille kirjoitetaan "GET", "401 Not found", "500 Internal Server Error" ja "200 OK"
- Leikkiin saa pukeutua
- Alussa käydään läpi lappujen tarkoitus. Sininen on HTML (sisältö), punainen tarkoittaa tyyliä (CSS) ja keltainen Javascriptiä (JS). 

--

### Leikki: Client & Server
Käyttäjä kirjoittaa paperille osoitteen, johon haluaa mennä. Käyttäjä antaa osoitelapun selaimelle. Selain ottaa lapun vastaan ja laittaa sen pieneen koriin yhdessä "GET"-pahvinpalan kanssa. 

Kun palvelin saa laatikon, niin se tutkii, että löytyykö sivu. Jos ei löydy, niin voi palauttaa suoraan "401":en tai jos jokin menee pieleen, niin "500":en. Jos sivu löytyy ja se osataan palauttaa, niin palvelin kirjoittaa laatikkoon kolme lappua. 

--

### Leikki: Client & Server
Siniseen lappuun tulee sisältö omin sanoin, vaikkapa ranskalaisin viivoin. Punaiseen lappuun voi kirjoittaa tyylin, esimerkiksi taustan värin, tekstin värin, välit, otsikoiden värit jne. Keltaiseen lappuun kirjoitetaan Javascript omin sanoin, eli käytännössä mitä sivulla tapahtuu, kun käyttäjä liikkuu siinä. 

Kun palvelin palauttaa laatikon selaimelle, niin selain lukee ensin html- ja tyylilaput ja piirtää sivun näiden perusteella. Tämän jälkeen selain näyttää sivun käyttäjälle ja käyttäjä kertoo, että mitä tekee sivulla. Esimerkiksi sormella liikkuu paperilla ja sanoo asioita, joita tekee. "Laitan hiiren tämän tekstin päälle, mutta en vielä klikkaa". Tai "klikkaan nyt tätä painiketta". 