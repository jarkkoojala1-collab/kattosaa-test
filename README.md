# Kattosää Pro testiversio - De before initialization korjattu

Korjattu:
- Virhe "Cannot access 'De' before initialization" poistettu.
- Syynä oli työmaajärjestyksen useEffect, joka käytti effectiveRules-arvoa ennen kuin se oli alustettu.
- Kyseinen logiikka siirrettiin oikeaan kohtaan effectiveRules-muuttujan jälkeen.
- Backendin syntaksi tarkistettu.
- Frontend build testattu onnistuneesti, jos riippuvuuksien asennus onnistui ympäristössä.

Render-asetukset:

Build Command:
npm run render-build

Start Command:
npm start
