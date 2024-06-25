---
title: "Configuración y Mejores Prácticas para Desarrollo Web Local"
description: "Cómo iniciar y configurar tu entorno de desarrollo web local en Windows, Mac y Linux. Optimiza tu flujo de trabajo de codificación: organización de proyectos, control de versiones, configuración de IDE, etc."
tags: ["javascript", "node", "python", "nvm", "pyenv", "git"]
authors: ["alesanchezr"]

---

Como desarrollador, trabajarás en varios proyectos de codificación simultáneamente; puede convertirse rápidamente en un desorden si no te organizas. **No seas la persona que tiene que esperar hasta perder el código del proyecto para aprender la lección.** Un flujo de trabajo y configuración bien estructurados te ayudarán a:

- Nunca perder tu código de proyecto (sucede mucho).
- Reducir el tiempo dedicado a la configuración.
- Cambiar fácilmente entre proyectos.
- Asegurar que tus proyectos sean portátiles y fáciles de compartir o mover.
- Ayudar a evitar conflictos y errores, especialmente al trabajar con múltiples dependencias.

Esta lección discutirá las mejores prácticas para configurar tu entorno de desarrollo local y flujo de trabajo en cualquier sistema operativo (computadoras Windows, Mac y Linux).

## 1) Crea un directorio local como raíz de todos tus proyectos

Utiliza una **estructura de directorios consistente** para organizar tus proyectos. Esto facilita cambiar entre proyectos, navegar y administrar tu código. A continuación se presentan los directorios recomendados para guardar tus proyectos y código:

 - **Windows**: `C:\Users\<YourUsername>\MyDocuments\Code`
 - **Mac**: `/Users/<YourUsername>/Documents/Code`
 - **Linux**: `/home/<YourUsername>/Documents/Code`

Los siguientes pasos te guiarán sobre cómo crear este directorio raíz según tu sistema operativo:

```windows runable=true
Dirígete a `C:\Users\<YourUsername>\MyDocuments` y crea una carpeta llamada `Code`.

Puedes crear esta carpeta mediante el Explorador de Archivos o usando el siguiente comando: `mkdir C:\Users\<YourUsername>\MyDocuments\Code`
```
```mac runable=true
Abre Terminal y crea el directorio `Code` con el siguiente comando: `$ mkdir -p ~/Documents/Code`
```
```linux runable=true
Abre tu terminal y crea el directorio `Code` sando el siguiente comando: `$ mkdir -p ~/Documents/Code`
```

## 2) Cada proyecto debe ser una nueva carpeta y repositorio de Git

No puedes trabajar y/o colaborar en múltiples proyectos sin usar un sistema de control de versiones como [Git](https://4geeks.com/lesson/how-to-use-git-version-control-system) y [Github](https://4geeks.com/lesson/welcome-to-github).

Cada vez que comiences a trabajar en un proyecto, realizarás cambios en los archivos y esos cambios serán registrados y rastreados por git:

- Nunca volverás a perder un solo archivo o cambio de archivo.
- Podrás retroceder en el tiempo cuando lo desees.
- Otros desarrolladores podrán ver y entender tus cambios más recientes en cuestión de segundos.

### Pasos para comenzar a rastrear las versiones de archivos

- Abre una cuenta en Github.com y aprende lo básico sobre [how to use GitHub](/lesson/welcome-to-github).
- Asegúrate de [instalar git en tu computadora Windows, MacOS o Linux](/how-to/install-git-on-windows-macos-and-linux).
- Inicializa un repositorio Git separado para cada directorio de proyecto: Este paso se realizará más adelante a medida que comiences a trabajar en proyectos mediante [clonación de un repositorio existente](https://4geeks.com/how-to/github-clone-repository) o creando uno nuevo.
- Realiza regularmente commits de tus cambios con mensajes de commit significativos.

## 3) Cada proyecto debe tener un entorno diferente

Un "entorno" se refiere a la configuración bajo la cual se ejecuta un proyecto. Idealmente, debes tener un entorno para cada proyecto, lo que significa que tendrás tantos entornos como proyectos.

### ¿Por qué tener diferentes entornos?

Existen varias razones; centrémonos en una: **versiones de lenguajes de programación.**
La tecnología evoluciona muy rápido: Si comienzas un proyecto en `Node v12`, este podría volverse obsoleto en unos meses.
Para evitar errores, debes `congelar en el tiempo` todas las dependencias del proyecto (bibliotecas, versión del lenguaje de programación, etc.).

> 📝 Aprende más sobre [crear entornos en programación](/lesson/what-is-an-environment-in-programming#what-are-environment-variables)

Otra razón es **privacidad y seguridad** al integrarse con otras APIs.
Por ejemplo, necesitas usar credenciales de API (API Keys) para hacer una llamada API a la API de TikTok.
Si estas credenciales están escritas directamente en tu código, quedan expuestas al público y cualquiera puede usar la API de TikTok en tu nombre.
Para evitar incidentes de seguridad, debes usar variables de entorno.

> 📝 Aprende más sobre [variables de entorno en programación](/lesson/what-is-an-environment-in-programming#what-are-environment-variables)

### Uso de un archivo .env para variables de entorno

Una vez que tengas tu entorno listo, es estándar crear un archivo llamado `.env` que no se cargará en GitHub porque será ignorado por Git (el sistema de control de versiones).

## 4) Usa VSCode como tu IDE predeterminado (editor de código):

- [Descarga VSCode](https://code.visualstudio.com/download) e instala su última versión desde el sitio web oficial.
- VSCode supports almost any programming language and offers features like linting and autocomplete that will prevent hundreds of bugs per day and make you code super fast (eventually 🤣).
- VSCode es popular y probablemente se utiliza en las empresas donde podrías trabajar.
- Personaliza la configuración del editor para que coincida con tu flujo de trabajo y las convenciones de tu equipo.

## 5) Instala tus lenguajes de programación

Estas instrucciones varían según el lenguaje de programación que elijas instalar; recomendamos tener al menos `Node` y `Python`, así que aquí tienes las instrucciones para ambos lenguajes.

Recomendamos encarecidamente instalar `Node` y `Python` utilizando gestores de versiones en lugar de instalar el lenguaje de programación de forma aislada.

### Instala Python usando Pyenv

Pyenv es una herramienta para gestionar diferentes versiones de Python en nuestra computadora. Facilita cambiar entre versiones según sea necesario para nuestro entorno de desarrollo. Haz clic aquí para aprender [como instalar PyEnv en tu computadora local](https://4geeks.com/how-to/what-is-pyenv-and-how-to-install-pyenv).

### Instala Node usando NVM

NVM (Node Version Manager) te permite gestionar múltiples proyectos de JavaScript y entornos de Node.js, y cambiar entre ellos según las necesidades del proyecto. Haz clic aquí para aprender [cómo instalar NVM en todos los sistemas operativos](https://4geeks.com/how-to/install-nvm-on-every-operating-system).

## Consejos adicionales para el Desarrollo Web Local

- **Respaldo**: Realiza copias de seguridad regulares de tu código en un disco externo o un servicio en la nube como GitHub, GitLab o Bitbucket.
- **Documentación**: Mantén una buena documentación dentro de tus proyectos para ayudar a otros (y a tu yo futuro) a entender el código.
- **Colaboración**: Utiliza herramientas como GitHub o GitLab para el desarrollo colaborativo, incluidas las solicitudes de extracción y revisiones de código.

Siguiendo estas mejores prácticas, podrás crear un entorno de desarrollo local robusto y organizado que soporte una codificación eficiente y efectiva.
