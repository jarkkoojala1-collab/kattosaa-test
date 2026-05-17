# Kattosää Pro testiversio - työmaajärjestyksen pisteytys korjattu

Korjattu:
- Kaikki työmaat eivät enää näytä "Tee ensin".
- Vain järjestyksen ensimmäinen sopiva työmaa saa tekstin "Tee ensin".
- Muut sopivat työmaat saavat tekstin "Seuraavana".
- Osittain sopivat työmaat saavat tekstin "Seuraa".
- Huonot työmaat saavat tekstin "Odota".
- Järjestys huomioi:
  1. löytyykö riittävä pinnoitusikkuna
  2. kuinka aikaisin ikkuna alkaa
  3. sopivien päivätuntien määrä
  4. työmaan nimi tasatilanteessa

Render-asetukset:

Build Command:
npm run render-build

Start Command:
npm start
