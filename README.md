# Masakiro Mono

Masakiro's custom build of [Iosevka](https://github.com/be5invis/Iosevka).

---

## Installation

Download the latest release from the [Releases page](https://github.com/masakirocorp/masakiro-mono/releases).

**Available packages:**

- `MasakiroMono.zip` - Recommended desktop package: Light, Regular, and Bold
- `MasakiroMono-Hinted.zip` - Same six faces for standard-resolution displays
- `MasakiroMono-Full.zip` - All six weights
- `MasakiroMono-Web.zip` - WOFF2 web fonts

Extract and install the fonts on your system.

---

## Features

- Default desktop package has Light, Regular, and Bold with matching italics
- Upright and Italic styles
- Broad Latin plus common coding, math, and terminal symbols; other scripts use system fallback

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
