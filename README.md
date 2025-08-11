# MaiVoice

Mai Voice on oikean puheäänialueen harjoitteluun tarkoitettu lauta-seurapeli kahdesta kuuteen pelaajalle.

Pelisuunnittelu: Mai ja Google Gemini 2.5 Pro

Tästä repositorystä löytyvien materiaalien lisäksi tarvitset äänitaajuusmittari-sovelluksen. 

Yksi hyvä vaihtoehto on Tadao Yamaokan kehittämä *Vocal Pitch Monitor*, joka on saatavissa Android- ja Apple-puhelimelle/laitteille. Toinen hyvä vaihtoehto on selaimessa toimiva [Pitchreader](https://pitchreader.com/).

Voidaan ajatella, että ihmisen puheäänen sävelalat ovat seuraavan taulukon (Talukko 1. Äänialat) mukaiset:

| Pelin väri | Kuvaus                                 | Sävelala | Taajuusalue  |
| ---------- | -------------------------------------- | -------- | ------------ |
| Punainen   | Korkea feminiininen                    | Yli A3   | > 220 Hz     |
| Oranssi    | Keskitason feminiininen                | G3 - A3  | 190 - 220 Hz |
| Keltainen  | Matala feminiininen, ylempi androgyyni | F3 - G3  | 170 - 190 Hz |
| Vihreä     | Selkäesti androgyyni alue              | D3 - E3  | 150 - 170 Hz |
| Sininen    | Keskitason maskuliininen               | B2 - D3  | 120 - 150 Hz |
| Violetti   | Matala maskuliininen                   | Alle B2  | < 120 Hz     |
Taulukko 1. Äänialat

Pelin tarkoitus on toimia hauskana pelillisenä tapana kokeilla ja omaksua uusi ääniala. Peliä voi myös pelata *voittaakseen*, jos haluaa, säännöt mahdollistavat voittamisen sekä häviämisen. 

Repository on jaettu seuraaviin alihakemistoihin:
- src - pelin sääntöjen ja komponenttien lähdekieliset versiot
- print - pelin tulostettavat komponentit pdf- ja stl-muotoisina

[Sisällysluetteloon ->](/src/Sisällysluettelo.md)
