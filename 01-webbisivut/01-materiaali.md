title: Mitä webbisivut ovat
author:
  name: Hannu Korhonen
  github: hade
output: 01-esitys.html
controls: true
style: ../asset/cleaver-style.css
--

# 01 - Mitä webbisivut ovat

--

### Sivustot

- Internetissä on valtava määrä sivustoja (site). 
- Jokaisella on oma osoitteensa. 
- Mitä sivustoja tiedät Internetistä?

--

### Selaimet
- Internet-sivuja katsotaan selain-ohjelman (browser) avulla. 
- Osaatko nimetä yhtään selainohjelmaa koneeltasi?

--

###  Selain ja sivusto
- Kun selaimeen syötetään sivuston osoite, niin selain osaa lukea sivun sisällön.
- Testataan 

--

### Sivuston koodin katselu
- Mene koulusi sivulle ja tarkastele sivun lähdekoodia. 
- Paina valkoisella alueella hiiren kakkospainiketta:  
  **Näytä sivun lähdekoodi**

--

### Muuta sivun sisältöä
- Chromessa:  
View > Developer > Developer tools

-- 

### Tiedostot ja hakemistot
- Internet-sivut ovat tiedostoja, esimerkiksi `index.html`
- Osaatko nimetä tiedostoja omalta koneeltasi?

--

### Tiedostot ja hakemistot
- Mitä seuraavat tiedostot voisivat olla?
  - prime.jpg
  - päiväkirja.docx
  - historia-uusin.pptx
  - raportti.pdf

--

### Koodieditori
- Webbisivuja kannattaa kirjoittaa koodieditorin avulla (IDE). 
- Tällä kurssilla käytetään Visual Studio Code -editoria. 
- Se on hyvä ja ilmainen.

-- 

### Koodieditori
- Luo Finderissa uusi kansio koodeille
- Luo toinen kansio koodit-kansion sisälle
- Avaa tämä kansio Visual Studio Codessa (VSCode)

--

### Webbisivujen tekemisestä
- Luo tiedosto `index.html`
- Luodaan ensimmäinen otsikko.
- Ykköstason otsikko saadaan kirjoittamalla otsikon teksti h1-tägien sisään:
```html 
<h1>Ensimmäinen otsikko</h1>
<h2>Toinen otsikko</h2>
```