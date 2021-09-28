# html5-qrcode
A cross-platform HTML5 QR code &amp; barcode reader.

This repository is only a part of the original library done by [mebjas](https://github.com/mebjas) which is located [here](https://github.com/mebjas/html5-qrcode)

The purpose was to be able to create a rectangle area to scan 1d barcode and add an idle delay to allow the user to move to the next barcode.

The object can now be initialized with this map.

```
const config = {
  fps: 10,
  **qrboxWidth: 240,**
  **qrboxHeight: 160,**
  aspectRatio: 0.75,
  **idleTimeout: 1500,**
};
```
