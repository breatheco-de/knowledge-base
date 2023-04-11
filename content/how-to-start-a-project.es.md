# Cómo comenzar un proyecto de codificación

En 4Geeks entendemos que comenzar un proyecto es una de las cosas más difíciles de hacer. Hay muchas formas de comenzar a codificar un nuevo proyecto, tantas que es difícil saber cuál es la mejor o la "forma recomendada".

Después de mucho trabajo duro, llegamos a las siguientes alternativas; lee cuidadosamente y elige la mejor que se adapte a tus necesidades:

## 1) ¿Qué repositorio de Github estás tratando de abrir?

El paso más crítico es reconocer qué repositorio desea abrir; hay dos opciones:
- Algunos proyectos requieren comenzar desde cero pero usando una de las plantillas de 4Geek.
- Otros proyectos vienen con código prescrito; necesitas hacerle fork y clonar el repositorio principal del proyecto antes de abrirlo.

Asegúrate de entender la URL del repositorio que necesitas abrir.

## 2) Abrir el repositorio (solo para plantillas)

Una vez que sepas exactamente el repositorio que necesitas abrir, navega a ese repositorio y ten en cuenta que el proceso será un poco diferente si el repositorio es una plantilla. Si tu repositorio no es una plantilla, ve a `paso 3`.

Algunos repositorios están destinados a ser reutilizados cada vez que comiences un nuevo proyecto, en 4Geeks hemos creado varias plantillas para HTML/CSS, React, Python, etc. [Aquí está la lista completa.](https://github.com/4GeeksAcademy/Templates-Boilerplates).

Puedes saber si el repositorio es una plantilla porque contiene un botón para `Use this template`.

![](https://raw.githubusercontent.com/breatheco-de/knowledge-base/main/images/template.png)

Si el repositorio es una plantilla, comenzarás creando un nuevo repositorio basado en la plantilla. Haz clic en el botón que dice `Use this template`; se mostrará un menú desplegable. Debes hacer clic en la opción que dice `Create a new repository`:

![image](https://user-images.githubusercontent.com/109599459/230989999-aeba16c4-c1c1-460a-b1bb-94631de6ccc4.png)

Serás redirigido a una nueva vista donde crearás tu nuevo repositorio. Haz clic en el botón `Select an owner`; se mostrará un menú desplegable.

> ⚠️ Importante: Si actualmente eres parte del bootcamp de codificación de 4Geeks Academy, asegúrate de seleccionarlo en este menú desplegable, de lo contrario no obtendrás horas gratuitas de Github Codespaces.

Debes darle a tu repositorio un nombre: recomendamos encarecidamente que prependas tu nombre de usuario de github seguido del nombre del proyecto en el que estarás trabajando. Por ejemplo `githubusername-my-project-name`:

![image](https://user-images.githubusercontent.com/109599459/230991453-38566874-f844-4027-9e7d-3662c7548c66.png)

Asegúrate de seleccionar la opción `public` y luego haz clic en el botón que dice `Create repository from template`:

![image](https://user-images.githubusercontent.com/109599459/230991967-9c08afca-1355-41a5-8a12-0464b98d7bbd.png)

Serás redirigido a la URL del repositorio. Lo primero que necesitas hacer es marcar el repositorio como favorito para poder encontrarlo más fácilmente. Para ello, haz clic en el botón `Star`:

![image](https://user-images.githubusercontent.com/109599459/230993816-8f404028-b109-40d5-a47c-e149ae6c17ae.png)

> Nota: Puedes ver tus repositorios marcados haciendo clic en el botón de tu perfil (donde está tu foto o avatar): se desplegará un menú desplegable y tendrás que hacer clic en la opción `Your stars`.

![image](https://user-images.githubusercontent.com/109599459/230994342-567b1526-c1fb-4d05-b108-f6f3ec4d4208.png)

## 3) Abrir el repositorio

Hay 3 formas de abrir un repositorio, por favor elige solo una:

- Usando una computadora en la nube en Codespaces (recomendado).
- Usando una computadora en la nube en Gitpod.
- Trabajando en tu máquina local.

### Si estás usando Codespaces (toma 10 segundos)

Actualmente, esta es la forma recomendada de abrir el repositorio.

Luego, haz clic en el botón verde `<> Code` y luego en el botón que dice `Create codespace on main`:
![image](https://user-images.githubusercontent.com/109599459/230995122-1c00d010-b6d4-4810-852e-1e1524797a34.png)

¡Se abrirá una nueva pestaña con tu espacio de código listo para trabajar! ¡Comienza a codificar!

> 💻 Nota: aquí hay más detalles sobre [cómo abrir repositorios con Codespaces](https://4geeks.com/lesson/how-to-use-github-codespaces).

### Si estás usando Gitpod (para usuarios antiguos)

Por favor descarga la extensión de Gitpod [para Chrome](https://chrome.google.com/webstore/detail/gitpod-always-ready-to-co/dodmmooeoklaejobgleioelladacbeki) o [para Firefox](https://addons.mozilla.org/en-US/firefox/addon/gitpod/).

Una vez que navegues a la página del repositorio, encontrarás un botón verde que dice `Gitpod`, aquí hay [una captura de pantalla que muestra cómo debe mostrarse el botón en el repositorio](https://storage.googleapis.com/breathecode-asset-images/15d7c805161244a5a38d7bbf82fb8d355073ad7ac195088a453fba5777c3ef99.png). Presiona el botón y el proyecto se abrirá inmediatamente.

> 🍊 Nota: aquí hay más detalles sobre [cómo abrir repositorios con Gitpod](https://4geeks.com/lesson/how-to-use-gitpod).

### Si está trabajando localmente en su computadora

No recomendamos trabajar en su computadora local, pero aquí están las instrucciones si insistes.

Puedes encontrar explicaciones muy detalladas [en este artículo](https://4geeks.com/how-to/github-clone-repository), pero aquí hay un resumen:

- Asegúrate de tener git instalado.
- Encuentra tu terminal o power shell (para windows).
- Navega hasta la carpeta donde quieres descargar los archivos usando el comando `cd`.
- Ejecuta el siguiente comando que descargará el código:
sh

```sh
$ git clone https://github.com/4GeeksAcademy/html-hello
```

- Una vez que el proyecto haya terminado de descargarse, puedes abrir el editor de VSCode en esa carpeta, generalmente escribiendo `$ code .` en tu terminal (nota el punto `.` al final). Si ese comando no funciona, todavía puedes abrir VSCode, hacer clic en "abrir carpeta" y encontrar tu carpeta de proyecto.



















