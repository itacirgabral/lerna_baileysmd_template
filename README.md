# Lerna for baileys

```
git clone https://github.com/itacirgabral/lerna_baileysmd_template lbai
git clone --branch multi-device https://github.com/adiwajshing/Baileys packages/baileysmd
cd lbai
npx lerna init
```

```
cd packages/baileysmd
yarn
npx tsc
npx typedoc
```

obs: typedocs needs typescript `~4.2.0`

[verdaccio](https://verdaccio.org/) is nice too