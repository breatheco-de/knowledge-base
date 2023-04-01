# Cómo comenzar un proyecto de codificación

En 4Geeks entendemos que comenzar un proyecto es una de las cosas más difíciles de hacer. Hay muchas formas de comenzar a codificar un nuevo proyecto, tantas que es difícil saber cuál es la mejor o la "forma recomendada".

Después de mucho trabajo duro, llegamos a las siguientes alternativas; lee cuidadosamente y elije la mejor que se adapte a tus necesidades:

## 1) ¿Qué repositorio de Github estás tratando de abrir?

El paso más crítico es reconocer qué repositorio desea abrir; hay dos opciones:
- Algunos proyectos requieren comenzar desde cero pero usando una de las plantillas de 4Geek.
- Otros proyectos vienen con código preescrito; necesitas forkear y clonar el repositorio principal del proyecto antes de abrirlo.

Asegúrate de entender la URL del repositorio que necesitas abrir.

## 2) Abrir el repositorio

Una vez que sepas exactamente el repositorio que necesitas abrir, navega hasta ese repositorio y ábrelo usando **solo una** de las siguientes formas:

- Usando una computadora en la nube en Codespaces (recomendado).
- Usando una computadora en la nube en Gitpod.
- Trabajando en su máquina local.

### Si estás usando Codespaces (toma 10 segundos)

Actualmente, esta es la forma recomendada de abrir el repositorio.

Una vez que navegues a la página del repositorio, encontrarás un botón verde que dice `Code`, aquí hay [una captura de pantalla que muestra cómo el botón debe mostrarse en la parte superior del repositorio](https://github.com/breatheco-de/content/raw/master/src/assets/images/open-codespace.png) y aquí hay un [gif animado con los pasos para abrirlo](https://github.com/breatheco-de/content/raw/master/src/assets/images/create-codespace.gif?raw=true)


> 💻 Nota: aquí hay más detalles sobre [cómo abrir repositorios con Codespaces](https://4geeks.com/lesson/how-to-use-github-codespaces).

### Si estás usando Gitpod (para usuarios antiguos)

Descarga la extensión de Gitpod [para Chrome](https://chrome.google.com/webstore/detail/gitpod-always-ready-to-co/dodmmooeoklaejobgleioelladacbeki) o [para Firefox](https://addons.mozilla.org/en-US/firefox/addon/gitpod/).

Una vez que navegues a la página del repositorio, encontrarás un botón verde que dice `Gitpod`, aquí hay [una captura de pantalla que muestra cómo el botón debe mostrarse en el repositorio](https://storage.googleapis.com/breathecode-asset-images/15d7c805161244a5a38d7bbf82fb8d355073ad7ac195088a453fba5777c3ef99.png). Presiona el botón y el proyecto comenzará a abrirse inmediatamente.

> 🍊 Nota: aquí hay más detalles sobre [cómo abrir repositorios con Gitpod](https://4geeks.com/es/lesson/como-utilizar-gitpod).

### Si estás trabajando localmente en tu computadora

No recomendamos trabajar en tu computadora local, pero aquí están las instrucciones por si insistes.

Puedes encontrar explicaciones muy detalladas [en este artículo](https://4geeks.com/es/how-to/Como-clonar-un-repositorio-de-github), pero aquí hay un resumen:

- Asegúrate de tener git instalado.
- Encuentra tu terminal de computadora o power shell (para windows).
- Navega hasta la carpeta en la que deseas descargar los archivos usando el comando `cd`.
- Ejecuta el siguiente comando que descargará el código:

```sh
$ git clone https://github.com/4GeeksAcademy/html-hello
```

- Una vez que el proyecto haya terminado de descargarse, puedes abrir el editor de VSCode en esa carpeta, generalmente escribiendo `$ code .` en tu terminal (fíjate en el punto `.` al final). Si ese comando no funciona, todavía puedes abrir VSCode, hacer clic en "abrir carpeta" y encontrar la carpeta del proyecto.