# QR Code Renderer

A minimal static web page that generates QR codes client‑side using a query parameter. Perfect for free, zero‑build hosting on GitHub Pages or any static server.

---

## Overview

This project provides a simple, cost‑effective way to render QR codes entirely in the browser. It leverages the [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) library via CDN to produce SVG‑based QR images—no build tools or back‑end required.

## Features

* **Dynamic encoding**: Generates a QR for any string passed via the `value` query parameter.
* **Lightweight**: Single HTML file plus a \~3 KB CDN script.
* **Zero build step**: Just HTML/CSS/JS—deploy as static files.
* **Free hosting‑friendly**: Works out‑of‑the‑box on GitHub Pages, Netlify, S3, etc.

## Live Demo

Try it now:
[https://innoaya.github.io/QR-Renderer/?value=https://github.com/innoaya](https://innoaya.github.io/QR-Renderer/?value=https://github.com/innoaya)

## Usage

1. **Clone or fork** this repo:

   ```bash
   git clone https://github.com/<YOUR_ORG_OR_USERNAME>/QR-Renderer.git
   ```
2. **Enable** GitHub Pages in your repository settings (source: `main` branch, folder `/`).
3. **Open** in your browser with a `value` parameter:

   ```
   https://<YOUR_ORG_OR_USERNAME>.github.io/QR-Renderer/?value=Hello%20World
   ```

## Customization

* **Adjust size**: Modify the `cellSize` and `margin` options in the script config.
* **Styling**: Tweak the CSS in the `<style>` block for fonts, layout, or theming.
* **Self‑host library**: Replace the CDN URL with a local copy of `qrcode.min.js` if desired.

## License

This project is open‑source under the [MIT License](LICENSE). Feel free to use and adapt it for your own needs.
