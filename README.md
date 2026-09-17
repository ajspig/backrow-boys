# The Backrow Boys

A one-page site for the three desks in row 3 — Matt, Aakash and Marc — with a
scannable QR for the office guest wifi.

Static HTML, no build step. `index.html` is the whole site. The QR is generated
in the browser by [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator)
from the `WIFI` constant at the bottom of the file; change the network there and
the code redraws itself.

Served by GitHub Pages from `main`.
