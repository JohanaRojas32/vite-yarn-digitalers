## REPASO:

## Incorporamos yarn a nuestro proyecto:
1. En consola, instalamos yarn

```sh
yarn create vite .
```

2. Instalamos las dependencias:

```sh
yarn
```

3. Levantamos el servidor:

```sh
yarn dev
```


### INSTALAMOS BOOTSTRAP A NUESTRO PROYECTO:

1. Instalamos bootstrap junto con popperjs/core:

```sh
yarn add bootstrap @popperjs/core
```

2. Incorporamos el bootstrap en el main (los script y estilos)

```main.js
import * as bootstrap from 'bootstrap'
```

3. Incorporamos bootstrap en el CSS:

```style.css
@import 'bootstrap';
```
