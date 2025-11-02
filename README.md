# Masakiro Mono

Masakiro's custom build of [Iosevka](https://github.com/be5invis/Iosevka).

---

## Installation

Download the latest release from the [Releases page](https://github.com/masakirocorp/masakiro-mono/releases).

**Available packages:**

- `MasakiroMono.zip` - Modern fonts (recommended)
- `MasakiroMono-Hinted.zip` - For standard-resolution displays
- `MasakiroMono-Web.zip` - WOFF2 web fonts

Extract and install the fonts on your system.

---

## Features

- 7 weight variants: Light (300) to ExtraBold (800)
- Upright and Italic styles
- Multiple font formats

Full configuration available in [`config.toml`](./config.toml).

---

## License

Licensed under the **SIL Open Font License 1.1**.

Built using the Iosevka typeface engine by Belleve Invis and contributors.

---

## Building

```bash
git clone https://github.com/masakirocorp/masakiro-mono.git
cd masakiro-mono

git clone https://github.com/be5invis/Iosevka.git iosevka-src
cd iosevka-src

cp ../config.toml private-build-plans.toml
npm install
npm run build -- contents::MasakiroMono
```

Built fonts output to `iosevka-src/dist/MasakiroMono/`.
