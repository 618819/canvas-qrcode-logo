> Generate QRcode with logo, only support Canvas.

# Usage
```js
new QRCode(dom, options)
```

## NPM
```js
const QRCode = require('canvas-qrcode-logo');
new QRCode(document.getElementById("qrcode"), {
        logo: './logo.png',
        text: "https://www.xiaoboy.com",
        width: 128,
        height: 128
    });
```

## Direct <script> Include
```html
<script src="../qrcode.min.js"></script>
<div id="qrcode"></div>
<script type="text/javascript">
    new QRCode.default(document.getElementById("qrcode"), {
        logo: './logo.png',
        text: "https://www.xiaoboy.com",
        width: 128,
        height: 128
    });
</script>
```

# Options
- `width` `{Number}` QRCode's width
- `height` `{Number}` QRCode's height
- `typeNumber` `{Number}`
- `colorDark` `{String}` default: `#000000`
- `colorLight``{String}` default: `#ffffff`,
- `correctLevel` `{String}` L | M | Q | H, default: `H`
- `logo` `String` logo's url,
- `size` `{Number}` logo's width and height, default: 30