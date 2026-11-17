# NDD Stock Count: uji scan barcode

Halaman uji pembaca barcode untuk NDD Stock Count v2. Halaman ini hanya membaca barcode lewat kamera HP atau scanner handheld dan tidak menyimpan data ke server.

- Halaman: `scan-test/index.html`
- Pembaca barcode: [zxing-wasm](https://github.com/Sec-ant/zxing-wasm) 2.2.4 (`zxing.js` + `zxing_reader.wasm`, disimpan di repo supaya tidak bergantung pada CDN)
- Format yang dibaca: EAN-13, EAN-8, UPC-A, UPC-E, ITF (ITF-14 karton), Code 128

## Cara uji
1. Buka link GitHub Pages repo ini di HP (Chrome di Android, Safari di iPhone), lalu sekali lagi dari WhatsApp.
2. Tekan **Buka kamera**, izinkan kamera, scan 20 SKU (bungkus dan karton).
3. Tekan **Salin hasil** dan kirim hasilnya. Info HP ikut tersalin.

Target lulus: minimal 19 dari 20 barcode terbaca dalam 3 detik.
