# Õpetajate Sild – GitHub Pages prototüüp

Interaktiivne õpikeskkonna näidis alustavale lasteaiaõpetajale ja mentorile.

## Sisu
- `index.html` – veebilehe põhistruktuur
- `style.css` – kujundus
- `script.js` – õpimoodulid, test, tegevuskava, tagasiside ja refleksioon

## Avaldamine GitHub Pagesis
1. Loo GitHubis uus **Public** repositoorium nimega `opetajate-sild`.
2. Laadi selle kausta **kolm faili** (`index.html`, `style.css`, `script.js`) repositooriumi juurkausta.
3. Ava **Settings → Pages → Build and deployment**.
4. Vali **Source: Deploy from a branch** ning **Branch: main / (root)** ja vajuta **Save**.
5. Avalik aadress on kujul `https://KASUTAJANIMI.github.io/opetajate-sild/`.

## Demopiirangud
- Rollivahetus Arina/Katrin toimub **samas brauseris**.
- Kirjed salvestatakse brauseri **localStorage**-isse, mitte GitHubi ega serverisse.
- Videode ja teadusartiklite juures on näidiskohad, mitte väljamõeldud lingid.
- Reaalset mitme kasutaja koostööd, autentimist ja andmebaasi selles versioonis ei ole.
- Ära kasuta prototüübis päris laste ega õpetajate isikuandmeid.

## Arendamine
Muuda tekste ja mooduleid `script.js` faili `MODULES` massiivis. Kasutajaliidese värvid asuvad `style.css` alguses `:root` plokis.
