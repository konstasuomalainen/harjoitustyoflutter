# PokeApp

## Tekijät
Tämän sovelluksen ovat kehittäneet [lisää tekijöiden nimet].

## Sovelluksen kuvaus
PokeApp on Flutter-sovellus, joka hyödyntää PokeAPI:ta ja Firebasen autentikaatiota. Käyttäjät voivat hakea Pokémoneja, tarkastella niiden tietoja ja lisätä suosikkinsa omalle lempipokémonien listalleen.

## Ominaisuudet
- Käyttäjän kirjautuminen ja rekisteröinti Firebase Authenticationin avulla
- Pokémonien haku ja tietojen näyttäminen PokeAPI:sta
- Lempipokémonien valinta ja tallennus käyttäjäkohtaisesti
- Responsiivinen käyttöliittymä

## Käytetyt paketit
Sovelluksessa on hyödynnetty seuraavia Flutter-paketteja:
- `firebase_auth` – Käyttäjän tunnistautumiseen
- `cloud_firestore` – Käyttäjäkohtaisten tietojen tallentamiseen
- `http` – PokeAPI:sta tietojen hakemiseen
- `provider` – Tilanhallintaan

## Ulkoiset palvelut
- **Firebase Authentication**: Käyttäjän kirjautumiseen
- **Cloud Firestore**: Käyttäjän lempipokémonien tallentamiseen
- **PokeAPI**: Pokémon-tietojen hakemiseen

## Puhelimen ominaisuudet
Sovellus ei vaadi erityisiä laitteistoominaisuuksia, vaan toimii internet-yhteyden varassa.

## Näkymät
1. **Kirjautumisnäyttö** – Käyttäjä voi kirjautua sisään tai rekisteröityä.
2. **Päänäkymä** – Käyttäjä voi hakea Pokémoneja ja tarkastella niitä.
3. **Lempipokémonit** – Lista käyttäjän tallentamista suosikkipokémoneista.

## Perustuuko esimerkkikoodiin?
Sovellus on toteutettu omana projektina, mutta sen kehittämisessä on voitu hyödyntää seuraavia esimerkkejä:
- [Linkki mahdolliseen esimerkkiprojektiin]

## Tekoälyn hyödyntäminen
Sovellus ei suoraan hyödynnä tekoälyä, mutta mahdollista laajennusta voisi olla esimerkiksi suosittelualgoritmi, joka ehdottaa Pokémoneja käyttäjän suosikkien perusteella.

Tekoälyä on käytetty readme.md-tiedoston rakenteen ja kieliasun parantamiseen.
