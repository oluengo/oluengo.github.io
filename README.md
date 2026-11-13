# oluengo.github.io

Personal website of oluengo: free, simple apps and a Nostr-powered blog.

**<https://oluengo.github.io>** · Nostr: `_@oluengo.github.io`

## Apps

| App | What it is | Nostr |
|---|---|---|
| [Mado](https://oluengo.github.io/mado/) | Your Nostr posts on your own website | Built on Nostr |
| [Tansu](https://oluengo.github.io/tansu/) | Explorer for your apps' data on Nostr | Built on Nostr |
| [Wavestr](https://oluengo.github.io/wavestr/) | Online radio and Nostr live streams | Optional |
| [Usus](https://oluengo.github.io/usus/) | Calisthenics workout and habit tracker | Optional |

Each app has its own repository and its page at `/<app>/`. The apps themselves are translated; the website is in English.

## Structure

```
index.html              home page
cat/, esp/              old language URLs, redirect to /
blog/index.html         blog: a lightweight Mado instance
blog/admin/             blog settings (sign in with an extension, Amber or a bunker)
.well-known/nostr.json  NIP-05: _@oluengo.github.io
fonts/, img/            Geist Mono typeface (OFL) and icons
```

## Blog

The blog runs on [Mado](https://github.com/oluengo/mado): code is loaded from `/mado/`, the npub is in `blog/index.html` and the settings live on Nostr (NIP-78, `d` = `mado:oluengo.github.io/blog/`). To change them: [`/blog/admin/`](https://oluengo.github.io/blog/admin/) → sign in → **Save**. There is no `config.json`.

## Credits

- Nostr icon: **Purple Nostrich Icon** by SovrynMatt — <https://github.com/SovrynMatt/Nostr-Website-Button-Design>
- Geist Mono (Vercel), SIL Open Font License — `fonts/OFL.txt`

[MIT License](LICENSE)
