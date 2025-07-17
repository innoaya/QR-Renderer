# QR Code Renderer

This tiny project renders a QR code based on the `value` query parameter provided in the URL. For rendering QR, https://cdn.jsdelivr.net/npm/qrcode-generator@1.4.4/qrcode.min.js is used. I figured out doing this is the most cost effective way to render QR image using github static hosting.

## Usage

1. Start the application.
2. Access the app in your browser with a URL like:

  ```
  http://localhost:PORT/?value=your-string-here
  ```

3. The page will display a QR code representing the string passed in the `value` query parameter.

## Features

- Renders a QR code for any string provided via the `value` query parameter.
- Simple and minimal interface.

## Example

If you visit:
