# Kattosää Pro testiversio - Invalid LatLng korjattu

Korjattu:
- Sovellus ei enää kaadu, jos tallennetulta työmaalta puuttuu lat/lon.
- Kartalle ei piirretä valittua paikkaa, jos koordinaatit puuttuvat.
- Kartan pisteet suodatetaan niin, että vain validit koordinaatit piirretään.
- Vanhoista localStorage-työmaista hyväksytään vain rivit, joilla on nimi.
- Työmaan avaaminen ei enää yritä keskittää karttaa undefined-koordinaatteihin.
- Työmaan tallennus estetään, jos koordinaatit puuttuvat.

Jos vanha selainmuisti on rikki:
Asetukset / selaimen sivustodata voi tyhjentää testisivulta, mutta tämän version pitäisi kestää myös vanhat puutteelliset työmaat.

Render-asetukset:

Build Command:
npm run render-build

Start Command:
npm start
