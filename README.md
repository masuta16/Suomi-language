# Suomi-language
A suomi programming language

# Suomi-ohjelmointi - Dokumentaatio

Tervetuloa Suomi-ohjelmointiin! Tämä dokumentaatio sisältää esimerkkejä ja ohjeita Suomi-ohjelmoinnin käyttöön.

## Alkeet

### Tulostus

`tulosta`: Tulostaa viestin konsoliin.

```perl
tulosta "Hei, maailma!";
```
Käyttäjän syöte

kysy: Kysyy käyttäjältä syötettä.
```perl
tulosta "Mikä on nimesi?";
$nimi = kysy;
tulosta "Hei, " . $nimi . "!";
```
Toistot
while-toisto

kun: Toistaa lohkon niin kauan kuin ehto täyttyy.
```
$luku = 1;
kun ($luku <= 5) {
    tulosta $luku;
    $luku = $luku + 1;
}

```
for-toisto

kaikille: Toistaa lohkon annetun alueen läpi.
```
kaikille $i (1..5) {
    tulosta $i;
}
```
Ehdot
if-ehto

jos: Suorittaa lohkon, jos ehto täyttyy.

```
$luku = 10;
jos ($luku > 0) {
    tulosta "Luku on positiivinen.";
} muuten {
    tulosta "Luku on nolla tai negatiivinen.";
}
```
if-elsif-else-ehto

jos, muutoin_jos, muutoin: Käyttää useita ehtoja.
```
$luku = 7;
jos ($luku > 10) {
    tulosta "Luku on suurempi kuin 10.";
} muutoin_jos ($luku > 5) {
    tulosta "Luku on suurempi kuin 5, mutta pienempi tai yhtä suuri kuin 10.";
} muutoin {
    tulosta "Luku on 5 tai pienempi.";
}
```
Funktiot
Alifunktio

alifunktio: Määrittelee oman alifunktion.
```
alifunktio tervehdi {
    my ($nimi) = @_;
    tulosta "Hei, " . $nimi . "!";
}

tervehdi("Maija");
```
Kommentit

Kommentit alkavat #-merkillä ja ovat ohjelman suorituksen aikana ohitettavia.
```
# Tämä on kommentti
tulosta "Tämä on tulostus.";
```
Toivottavasti tämä dokumentaatio auttaa sinua oppimaan Suomi-ohjelmoinnin perusteet!

Kiitos ja onnea matkaan!
```

Huomaa, että tämä on kuvitteellinen dokumentaatio ja Suomi-ohjelmointia ei ole todellisuudessa olemassa. Kuitenkin tässä esimerkissä olemme kuvitelleet, miltä Suomi-ohjelmointi voisi näyttää, jos sitä käytettäisiin samankaltaisella syntaksilla kuin Perlissä, mutta suomen kielellä.
```
