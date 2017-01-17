# React + Mobx

## Introducción
Boilerplate para utilizar React y Mobx, contiene las siguientes herramientas de desarrollo:

* Webpack
* Babel
* Chai
* Cross-env
* CSS Loader
* Karma
* Less

Para el desarrollo incluye las siguientes librerías:

* React (15.1.0)
* Mobx (3.0.0)
* Mobx React (4.1.0)


## Instalacion

**1. Clonar el repositorio:**

```sh
git clone --depth 1 https://github.com/daver182/react-mobx-boilerplate.git my-app
cd my-app
```


**2. Eliminar git anterior:**

```sh
rm -rf .git && git init && npm init
```

> :information_source: Esto reinicializa el repo e inicia un proyecto con npm


**3. Instalar las dependencias:**

```sh
npm install
```

> Una vez instaladas las dependecias queda todo listo para comenzar


## Flujo de trabajo


**4. Iniciar el servidor con livereload:**

```sh
npm run dev
```

>  Este es un servidor web completo. Cada vez que se hace un cambio a la carpeta `src` se recompila y se reinicia el navegador.

**5. Testing con `mocha`, `karma`, `chai`, `sinon` a través de `phantomjs`:**

```sh
npm test
```


**6. Generar un archivo build para producción en `./build`:**

```sh
npm run build
```


**5. Iniciar un servidor local en producción [serve](https://github.com/zeit/serve):**

```sh
npm start
```

> Esto simula un servidor CDN con gzip. Solo sirve el contenido de `./build`.
