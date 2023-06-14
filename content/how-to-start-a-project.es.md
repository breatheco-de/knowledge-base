# Cómo empezar un proyecto de programación  

En 4Geeks entendemos que empezar un proyecto es una de las cosas más difíciles de hacer. Hay muchas maneras diferentes de empezar, tantas que es difícil saber cuál es la mejor o la "forma recomendada".

Después de arduo trabajo, llegamos las siguientes alternativas; por favor, lee cuidadosamente y elige la primera que se adecue a tus necesidades:

## 1) Qué repositorio de Github estás intentando abrir?

El paso más crítico es reconocer cuál repositorio quieres abrir; hay dos opciones:

- Algunos proyectos requieren empezar de cero utilizando una de las plantillas de 4Geeks.
- Otros proyectos vienen con código ya pre-escrito; necesitarás hacerle fork y clonar el repositorio principal del proyecto antes de abrirlo.

Asegúrate de entender la URL del repositorio que necesitas abrir.

## 2) ¿El repositorio es una plantilla? (solo para plantillas)

Una vez que sepas exactamente cuál es el repositorio que necesitas abrir, navega al repositorio, y mantén en cuenta que el proceso será un poco diferente si el repositorio es una plantilla. Si el repositorio no es una plantilla, sigue al paso  `step 3`.

Algunos repositorios están hechos para ser reutilizados cada vez que empiezas un nuevo proyecto. En 4Geeks hemos creado múltiples plantillas para HTML/CSS, React, Python, etc. [Aquí está la lista completa](https://github.com/4GeeksAcademy/Templates-Boilerplates).

Puedes saber si el repositorio es una plantilla porque contiene un botón que dice `Use this template`.

![Usar esta plantilla](https://raw.githubusercontent.com/breatheco-de/knowledge-base/main/images/template.png)

Si el repositorio es una plantilla, vas a empezar creando un nuevo repositorio basado en la plantilla. Haz clic al botón que dice `Use this template` (usar esta plantilla); se mostrará un menú desplegable. Debes que hacer clic en la opción que dice `Create a new repository` (crear un nuevo repositorio):

![Usar esta plantilla](https://user-images.githubusercontent.com/109599459/230989999-aeba16c4-c1c1-460a-b1bb-94631de6ccc4.png)

Serás redirigido a una nueva vista donde vas a crear tu nuevo repositorio. Haz clic en el botón que dice `Select an owner`; se mostrará un menú desplegable.

> ⚠️ Importante: Si eres actualmente parte de coding bootcamp de 4Geeks Academy, asegúrate de seleccionarlo en este menú desplegable, de lo contrario no obtendrás horas gratuitas de Github Codespaces.

Le tienes que dar a tu repositorio un nombre: Nosotros recomendamos anteponer tu nombre de usuario de Github seguido por el nombre del proyecto en el que vas a estar trabajando. Por ejemplo, `githubusername-my-project-name`:

![Nombre del repositorio](https://user-images.githubusercontent.com/109599459/230991453-38566874-f844-4027-9e7d-3662c7548c66.png)


Asegúrate de seleccionar la opción `public`, y luego de eso haz clic en el botón `Create repository from template` (crear repositorio de la plantilla)

![Crear repositorio de la plantilla](https://user-images.githubusercontent.com/109599459/230991967-9c08afca-1355-41a5-8a12-0464b98d7bbd.png)

Serás redirigido a la URL del repositorio. La primera cosa que necesitas hacer es destacar el repositorio, de esta marera lo podrás encontrar más fácil. Tienes que darle clic al botón que dice `star` (destacar):

![Destacar](https://user-images.githubusercontent.com/109599459/230993816-8f404028-b109-40d5-a47c-e149ae6c17ae.png)

> 👉 Nota: Puedes ver tus repositorios destacados haciendo clic en el botón de tu perfil (donde está tu foto o tu avatar); se mostrará un menú desplegable, y tienes que darle clic la opción `Your stars`

![Tus destacados](https://user-images.githubusercontent.com/109599459/230994342-567b1526-c1fb-4d05-b108-f6f3ec4d4208.png)

## 3) Abre el repositorio

Hay 3 maneras de las que puedes abrir un repositorio, por favor elige una:

- Usando una computadora en la nube en Codespaces (recomendado).
- Usando una computadora en la nube en Gitpod.
- Trabajando en tu computador local.

### Si estás usando Codespaces (toma 10 segundos)

Actualmente, esta es la manera recomendada para abrir el repo.

Vas a darle clic al botón verde que dice `<> Code`, y luego de ese, al botón que dice `Create codespace on main` (Crear codespace en Main):

![Crear codespace en Main](https://user-images.githubusercontent.com/109599459/230995122-1c00d010-b6d4-4810-852e-1e1524797a34.png)

¡Una nueva ventana será abierta con tu Codespace listo para trabajar!¡Empieza a programar!

> 💻 Nota: aquí hay mas detalles sobre [cómo abrir repositorios con codespaces](https://4geeks.com/es/lesson/como-usar-los-codespaces-de-github).

### Si estás usando Gitpod (Para usuarios heredados)

Por favor, descarga la extensión de Github [para Chrome](https://chrome.google.com/webstore/detail/gitpod-always-ready-to-co/dodmmooeoklaejobgleioelladacbeki) o [para Firefox](https://addons.mozilla.org/en-US/firefox/addon/gitpod/).

Una vez que navegues a la página del repositorio, vas a encontrar un botón verde que dice `Gitpod`. Aquí hay una captura de pantalla que enseña [cómo debe mostrarse el botón en el repositorio](https://storage.googleapis.com/breathecode-asset-images/15d7c805161244a5a38d7bbf82fb8d355073ad7ac195088a453fba5777c3ef99.png). Presiona el botón y el proyecto empezará a abrirse inmediatamente.

> 🍊 Nota: aquí hay mas detalles sobre [abrir repositorios con Gitpod](https://4geeks.com/lesson/how-to-use-gitpod).

### Si estás trabajando localmente en tu computadora

No recomendamos trabajar localmente en tu computadora, pero aquí están las instrucciones por si insistes.

Puedes encontrar explicaciones detalladas [en este artículo](https://4geeks.com/es/how-to/como-clonar-un-repositorio-de-github), pero aquí está el resumen:

- Asegúrate de que tienes git instalado.
- Encuentra tu terminal de computadora o PowerShell (para Windows).
- Navega a la carpeta en la que quieres descargar los archivos usando el comando `cd`.
- Corre el siguiente comando que va a descargar el código.

```sh
$ git clone https://github.com/4GeeksAcademy/html-hello
```

- Una vez que el proyecto haya terminado de descargarse, puedes abrir el editor VScode en esa carpeta, usualmente escribiendo `$ code .` en tú terminal (nota el punto al final `.`). Si ese comando no funciona, todavía puedes abrir VSCode, haz clic en "open folder" y busca la carpeta de tu proyecto.
