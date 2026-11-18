# 🍅 OpiskeluPomodoro

Suomenkielinen, mobiiliystävällinen Pomodoro-opiskelusovellus. Ei vaadi asennuksia, palvelinta tai käyttäjätunnuksia.

## Käyttö

Avaa `index.html` selaimessa tai julkaise GitHub Pagesissa.

- Valitse päivä ja lisää Pomodoroja.
- Valitse tehtävä, käynnistä 25 minuutin ajastin ja merkitse tehtävä tehdyksi.
- Vaihda 5 minuutin taukoon tarvittaessa.
- Lisää uusia päiviä ja poista tarpeettomia tehtäviä.
- Vie JSON-varmuuskopio, jos haluat siirtää tietoja laitteelta toiselle.

## Julkaisu GitHub Pagesiin

1. Luo GitHubissa uusi julkinen repository, esimerkiksi `pomodoro-app`.
2. Lataa repositoryyn `index.html` (ja halutessasi tämä `README.md`) juurihakemistoon.
3. Avaa **Settings → Pages**.
4. Valitse **Build and deployment → Deploy from a branch**, branch **main** ja kansio **/(root)**. Tallenna.
5. Sovelluksen osoite on yleensä `https://KAYTTAJANIMI.github.io/pomodoro-app/`.

## Tietojen säilyminen

Edistyminen tallentuu selaimen `localStorage`-muistiin. Se ei synkronoidu automaattisesti eri selaimien tai laitteiden välillä. Selainhistorian/sivustotietojen tyhjentäminen voi poistaa tiedot. Käytä **Vie varmuuskopio** -toimintoa.

Ajastin toimii sivun ollessa avoinna. Sivu ei lähetä tietoja ulkoiselle palvelimelle.
