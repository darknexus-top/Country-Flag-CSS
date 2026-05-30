# Country Flag CSS

A lightweight, pure CSS library to display country flags using simple HTML classes. No images or external assets required — just vector-based flags rendered entirely with CSS.

## Features

- ✅ **Pure CSS** — No images, no SVGs, no external files
- ✅ **Lightweight** — Minimal footprint for faster page loads
- ✅ **Easy to use** — Just add a CSS class to any element
- ✅ **Vector quality** — Flags scale without losing quality
- ✅ **CDN available** — Ready to use via jsDelivr

## Flags
<p>
  <img src="/dist/flags/BD.svg" width="50">
  <img src="/dist/flags/IR.svg" width="50">
  <img src="/dist/flags/BR.svg" width="50">
  <img src="/dist/flags/CA.svg" width="50">
  <img src="/dist/flags/CI.svg" width="50">
  <img src="/dist/flags/CU.svg" width="50">
  <img src="/dist/flags/BF.svg" width="50">
  <img src="/dist/flags/BL.svg" width="50">
  <img src="/dist/flags/Bn.svg" width="50">
  <img src="/dist/flags/US.svg" width="50">
  <img src="/dist/flags/PK.svg" width="50">
  <img src="/dist/flags/SA.svg" width="50">
</p>
## Installation

### Via CDN (Recommended)

Add the following line to your HTML `head`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/darknexus-top/Country-Flag-CSS@main/dist/css/flags.main.css">
```

#### Html Example
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/darknexus-top/Country-Flag-CSS@main/dist/css/flags.main.css">
</head>
<body>

<i class="flag flag-us"></i>
<i class="flag flag-in"></i>

</body>
</html>
```

Via GitHub

Clone the repository:

```bash
git clone https://github.com/darknexus-top/Country-Flag-CSS.git
```

Then include the CSS file in your project:

```html
<link rel="stylesheet" href="path/to/dist/css/flags.main.css">
```

Usage

Display a flag by creating an element with the flag class followed by the country code:

```html
<!-- United States -->
<i class="flag flag-us"></i>

<!-- Ascension Island -->
<i class="flag flag-ac"></i>

<!-- United Kingdom -->
<i class="flag flag-gb"></i>
```

Size Control

By default, flags are displayed at 1em × 0.75em. You can easily resize them using CSS:

```html
<!-- Small flags -->
<i class="flag flag-us" style="font-size: 1rem;"></i>

<!-- Medium flags -->
<i class="flag flag-gb" style="font-size: 2rem;"></i>

<!-- Large flags -->
<i class="flag flag-ac" style="font-size: 4rem;"></i>
```

With Other Elements

```html
<span>
  <i class="flag flag-fr"></i> France
</span>

<span>
  <i class="flag flag-de"></i> Germany
</span>

<span>
  <i class="flag flag-jp"></i> Japan
</span>
```

Available Flags

The library includes flags for all countries, dependencies, and special regions. Use the standard ISO 3166-1 alpha-2 country codes:

Country Code Example
United States us flag-us
United Kingdom gb flag-gb
France fr flag-fr
Germany de flag-de
Japan jp flag-jp
Brazil br flag-br
India in flag-in
Australia au flag-au
Canada ca flag-ca
Ascension Island ac flag-ac

<p align="center">
  <a href="https://darknexus-top.github.io/Country-Flag-CSS/">
    🔎 Open Flag Explorer
  </a>
</p>

For a complete list of all available country codes, please refer to the repository.

Browser Support

Supports all modern browsers:

· Chrome / Edge (latest)
· Firefox (latest)
· Safari (latest)
· Opera (latest)
· Mobile browsers (iOS Safari, Android Chrome)
Repository Structure

```
Country-Flag-CSS/
├── dist/
│   ├── css/
│   ├   └── flags.main.css    # Main CSS file
│   └── flags/
│       ├── AC.svg
├── src/                      # Source files
├── README.md                 # This file
└── LICENSE                   # License information
```

License

This project is open source and available under the MIT License.

Links

[GitHub Repository](https://github.com/darknexus-top/Country-Flag-CSS)

[CSS File](https://github.com/darknexus-top/Country-Flag-CSS/blob/main/dist/css/flags.main.css)

[CDN Link](https://cdn.jsdelivr.net/gh/darknexus-top/Country-Flag-CSS@main/dist/css/flags.main.css)

Contributing

Contributions are welcome! Feel free to submit issues, feature requests, or pull requests to improve the library.

---

Made with ❤️ by darknexus-top