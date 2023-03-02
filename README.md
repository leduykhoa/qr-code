## Installation

install via npm:
```bash
npm install qr-code --save
```
## Basic Usage
```javascript

    // example #1
    new QrCode(document.getElementById(`test`), `http://web-fast.com`);

    // example #2
    let oQrCode = new QrCode(`test`, {
        text : `http://web-fast.com`,
        width : 128,
        height : 128
    });

    oQrCode.clear(); // Clear the QrCode.
    oQrCode.makeCode(`http://web-fast.com`); // Re-create the QrCode.
```