# Webfejlesztő platform

Bemutatkozó weboldal webfejlesztési, karbantartási és üzemeltetési szolgáltatásokhoz. A projekt **Astro** + **TypeScript** alapú, és fokozatosan épül.

## Mi van most?

- Egy magyar nyelvű kezdőlap.
- Nincs belépés, admin, adatbázis vagy fizetés.

## Hogyan indítsd el?

1. Nyisd meg a Cursor alján a **terminált** (parancssor: ide írsz szöveget, Enterrel futtatod).
2. Győződj meg róla, hogy ebben a mappában vagy: `C:\Users\gemes\Projects\webfejleszto-platform`
3. Írd be, majd Enter:

```sh
npm run dev
```

4. A terminál kiír egy címet, általában: `http://localhost:4321`
5. Ezt másold a böngésző címsorába. **localhost** = csak a te géped, nem a nyilvános internet.
6. Leállítás: a terminálban `q` majd Enter, vagy `Ctrl+C`.

| Parancs | Mit csinál |
| --- | --- |
| `npm run dev` | Fejlesztői nézet, mentés után frissül a böngésző |
| `npm run build` | Elkészíti a publikus fájlokat a `dist/` mappába |
| `npm run preview` | A lefordított oldalt nézed helyben |

## Mappa röviden

- `src/pages/` — oldalak. A fájlnév lesz a webcím (`index.astro` = kezdőlap).
- `src/layouts/` — közös keret (címsor, nyelv).
- `src/styles/` — kinézet (CSS).
- `public/` — képek, ikonok.
- `.env` — ide kerülhetnek később titkok; **ne** tedd GitHubra (a `.gitignore` már kizárja).

## Hivatalos dokumentáció

- [Astro telepítés](https://docs.astro.build/en/install-and-setup/)
- [Astro TypeScript](https://docs.astro.build/en/guides/typescript/)
# web
web
