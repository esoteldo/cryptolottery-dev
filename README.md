# cryptolottery-dev

Hosting del frontend **DEV (testnet)** de CryptoLottery via GitHub Pages
(servido desde `docs/` en master): <https://esoteldo.github.io/cryptolottery-dev/>

**No editar a mano.** El contenido de `docs/` se genera desde el repo
[cryptolottery](https://github.com/esoteldo/cryptolottery) con:

```
npm run deploy:dev
```

que hace el build con `.env.development`, espeja `docs-dev/` acá, commitea y pushea.

El sitio prod es <https://esoteldo.github.io/cryptolottery/> (repo cryptolottery, `docs/`).
