# Template de Web de Creación y Escaneo de Códigos QR

Este template proporciona una interfaz web básica para crear y escanear códigos QR. No utiliza ninguna dependencia de npm y utiliza la API de [QRServer](https://api.qrserver.com/) para generar y escanear los códigos QR.

## Características

- Creación de códigos QR con texto, URL, correo electrónico, teléfono, etc.
- Escaneo de códigos QR con la cámara del dispositivo.

## Requisitos

- Tener instalado [Visual Studio Code](https://code.visualstudio.com/) (VSC) o usar [Replit](https://replit.com/) u otra plataforma web similar.

## ¿Cómo visualizar la página web?

### Clonar el repositorio de GitHub

```bash
git clone https://github.com/ALEXXHUMILDE/QRPortal.git
```

### Inicia un server
- Inicia un server con [Visual Studio Code](https://code.visualstudio.com/), [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) o [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server).

## Uso
- La interfaz web del template se encuentra en la dirección http://127.0.0.1:5500/.

- Para crear un código QR, haz clic en el botón "Generar un Código QR" en la página principal. Se abrirá otra página y en ella habla un recuadro que dice "Texto o URL" y ahí ingresas tu Texto, URL, Correo Electrónico u otra cosa.

- Para escanear un código QR, haz clic en el botón "Escanear un código QR" en la página principal. Se abrirá otra página y en ella habla un recuadro que dice "Sube tu Código QR" y le das clic al recuadro, buscas tu Código QR, lo pones en la página, y solo esperas a que se escanee y ya tendrás el Texto o URL de ese Código QR.

- Lamentablemente, la API no escanea los Códigos QR en móvil, solo en PC. :(

## Tecnologías utilizadas

- HTML
- CSS
- JS

## Licencia 

- Este proyecto se distribuye bajo la licencia MIT. 

## Demostración

- Hay una demostración del proyecto disponible en la siguiente dirección:

https://qrportal.netlify.app/
