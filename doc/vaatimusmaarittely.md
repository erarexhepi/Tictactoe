# Harjoitustyön määrittelydokumentti

**Era Rexhepi**  
Kurssi: *Algoritmit ja tekoäly -harjoitustyö*
Opinto-ohjelma: *Tietojenkäsittelytiede*
Projektin dokumenaatiokieli: *suomi*

---

## Harjoitustyön aihe
**Tic Tac Toe -peli ja minimax-algoritmi**

---

## Harjoitustyö

Harjoitustyöni ydin on tekoälyn toteuttaminen Tic Tac Toe -peliin minimax-algoritmin avulla. Tavoitteena on toteuttaa algoritmi, joka kykenee pelaamaan täydellisesti tekemällä aina parhaan mahdollisen siirron annetussa pelitilanteessa. Pääpaino on algoritmin toimivuudessa ja päätöksenteon loogisuudessa.

---
## Toteutustapa

- **Ohjelmointikieli:** Python
- **Käyttöliittymä:** Tekstipohjainen, valikkotoiminnolla ja ASCII-laudalla
- **Versiohallinta** Git
- **Testaus:** Pythonin yksikkötestit 

## Käytettävät algoritmit ja tietorakenteet

- Minimax-algoritmi: rekursiivinen hakualgoritmi päätöksentekoon kahden pelaajan pelissä
- Pelipuun läpikäynti: arvioida kaikki mahdolliset pelitilanteet ja paras mahdollinen siirtovalinta


---

## Ratkaistava ongelma

Ohjelman tehtävänä on ratkaista optimaalinen siirto 3x3 Tic Tac Toe -pelissä annetussa tilanteessa. Tavoitteena on, että tekoäly ei häviä koskaan, ja että se tekee joko voittavan siirron tai estää vastustajan voiton.

---

## Syötteet ja niiden käyttö

- Käyttäjä voi vuorollaan syöttää ruudukon koordinaatit komentoriviltä
- Tekoäly käyttää minimax- algoritmia valitakseen seuraavan siirron

---
## Aika- ja tilavaativuus

- Minimax- algortimin pahimman tapauksen aikavaativuus on O(b^d): 
    - b = haarautumisaste (pelissä enintään 9)
    - d = puun syvyys (enintään 9)

- Pelin yksinkertaisuuden vuoksi algoritmi toimii hyvin ilman optimointia, mutta alpha-beta pruning voi nopeuttaa toimintaa huomattavasti.

---

## Odotetut tulokset
- Toimiva komentiriviltä pelattava Tic Tac Toe- peli
- Tekoäly, joka pelaa täydellisesti minimax- arlgoritmin avulla
- Testit funktioille, esim. voittajan tarkistus ja siirron valinta
- Selkeä dokumentointi, joka selittää algoritmin toimintaperiaatteen


---

## Lähteet

- [Wikipedia: Minimax algorithm](https://en.wikipedia.org/wiki/Minimax)
- GeeksforGeeks
- Visualgo.net

---

## Aikataulu (luonnos)

| Viikko | Tavoite |
|--------|---------|
| 1      | Suunnittelu|
| 2      | Pelitilan ja Minimax-algoritmin toteutus |
| 3      | Käyttöliittymän rakentaminen ja perustoiminnallisuus |
| 4      | Testaus, virheenkorjaukset ja viimeistely |
