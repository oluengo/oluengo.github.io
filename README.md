# oluengo.github.io

Web personal de oluengo: apps libres y sencillas, y un blog sobre Nostr.
*Personal website of oluengo: free, simple apps and a Nostr-powered blog.*

**<https://oluengo.github.io>** · Nostr: `_@oluengo.github.io`

## Apps

| App | Qué es · What it is | Nostr |
|---|---|---|
| [Mado](https://oluengo.github.io/mado/) | Tus publicaciones de Nostr en tu propia web · Your Nostr posts on your own website | Hecha sobre Nostr · Built on Nostr |
| [Tansu](https://oluengo.github.io/tansu/) | Explorador de los datos de tus apps en Nostr · Explorer for your apps' data on Nostr | Hecha sobre Nostr · Built on Nostr |
| [Wavestr](https://oluengo.github.io/wavestr/) | Radio online y streams de Nostr · Online radio and Nostr live streams | Opcional · Optional |
| [Usus](https://oluengo.github.io/usus/) | Registro de entrenos y hábitos · Workout and habit tracker | Opcional · Optional |

Cada app tiene su propio repositorio y su página en `/<app>/`. *Each app has its own repository and page at `/<app>/`.*

## Estructura · Structure

```
index.html              portada en inglés · English home page
cat/, esp/              portada en catalán y castellano · Catalan and Spanish home
blog/index.html         blog: instancia ligera de Mado · lightweight Mado instance
blog/admin/             configuración del blog (entra con extensión, Amber o bunker)
.well-known/nostr.json  NIP-05: _@oluengo.github.io
fonts/, img/            tipografía Geist Mono (OFL) e iconos · typeface and icons
```

## Blog

El blog usa [Mado](https://github.com/oluengo/mado): el código se carga desde `/mado/`, el npub está en `blog/index.html` y la configuración vive en Nostr (NIP-78, `d` = `mado:oluengo.github.io/blog/`). Para cambiarla: [`/blog/admin/`](https://oluengo.github.io/blog/admin/) → entrar → **Guardar**. No hay `config.json`.

*The blog runs on Mado: code from `/mado/`, npub in `blog/index.html`, settings stored on Nostr. Edit them at `/blog/admin/` (sign in, then **Save**). There is no `config.json`.*

## Créditos · Credits

- Icono de Nostr · Nostr icon: **Purple Nostrich Icon** by SovrynMatt — <https://github.com/SovrynMatt/Nostr-Website-Button-Design>
- Geist Mono (Vercel), SIL Open Font License — `fonts/OFL.txt`

[MIT License](LICENSE)
