# Kattosää testiversio - Pro-parametrit

Tämä on erillinen testiversio, jossa on mukana Pro-tyyppiset ominaisuudet ilman oikeaa maksujärjestelmää.

Mukana:
- kirjautuminen
- logo ja PWA-kuvakkeet
- kirjautumissivun kattotaustakuva
- Uusimaa / Pirkanmaa -aluevalinta
- iPhone-karttakorjaus
- yrityksen nimi
- käyttöoikeustason simulointi: Demo / Basic / Pro
- ominaisuuksien lukitus käyttöoikeuden mukaan
- yrityskohtaiset muokattavat sääparametrit:
  - maksimikosteus %
  - minimilämpötila °C
  - maksimituuli m/s
  - maksimisade mm/h
  - vaadittu hyvä pinnoitusaika tunneissa
- kartan värit ja tuntitaulukko muuttuvat valittujen parametrien mukaan
- seuraava hyvä pinnoitusikkuna
- työmaiden tallennus Pro-tasolla
- asetukset tallentuvat selaimen localStorageen testikäyttöä varten

Huomio:
Tämä on testimalli. Oikeassa maksullisessa versiossa nämä tiedot siirrettäisiin tietokantaan ja suojattaisiin yrityskohtaisesti.

Render-asetukset:

Name:
kattosaa-test-pro

Build Command:
npm run render-build

Start Command:
npm start
