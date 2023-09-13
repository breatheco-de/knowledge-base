El portal de la academia [4Geeks.com](http://4Geeks.com/es) ahora puede sincronizar automáticamente y opcionalmente a los estudiantes como usuarios de su organización de Github.

> 🐞 Esta es una función beta que será probada en las próximas semanas.

## ¿Cómo funciona la Sincronización de la Organización de Github?

### Activación o desactivación de la Sincronización de Github

Hemos tomado medidas para activar la sincronización de Github en las ubicaciones actuales de 4Geeks Academy en el sistema. Esto se puede desactivar en cualquier momento en la [configuración de Github del administrador](https://admin.4geeks.com/admin/github).

### Agregar usuarios

Los estudiantes son automáticamente `agregados` a la organización de GitHub en las siguientes situaciones:

1. Cuando se agrega un estudiante a una cohorte.
2. Cada vez que el estado de educación se vuelve `activo`.

También puedes invitar manualmente a estudiantes a la organización desde [Github.com](http://Github.com) y [4Geeks.com](http://4Geeks.com los reconocerá cuando se sincronicen con Github; intentará obtener información sobre sus cohortes y conectarlos con su academia.

![Comunidad de Desarrolladores](https://github.com/breatheco-de/knowledge-base/blob/main/images/4Geeks-Developers-Community-Admin_(5).png?raw=true)

> ⚠️ Si se encuentra a un usuario en una organización de Github pero no se refleja como usuario de [4geeks.com](http://4geeks.com/es) y no pertenece a ninguna cohorte, el sistema marcará al usuario como ignorado.

### Eliminar usuarios

Los estudiantes que fueron `eliminados` de la organización de GitHub en la siguiente situación:

1. Cuando un estudiante pierde el estado `activo` en una cohorte.

También puedes eliminar manualmente usuarios en Github, pero es probable que el sistema los vuelva a agregar. Se recomienda marcarlos como eliminados en la página de administración de GitHub y esperar a que el sistema los elimine de la Organización de GitHub

> ⚠️ Las cohortes que `nunca terminan` también se consideran; siempre que el estudiante esté activo, se le permitirá ingresar a la organización de la academia.

![sincronizar usuarios de github](https://storage.googleapis.com/breathecode-asset-images/bcfa2f990e94bb6d13f293926956d37f86b2778248bcb9e804d43a97c1272d6b.gif?raw=true)

## Acciones necesarias por parte de la academia

### Asegurarse de que los estudiantes acepten las invitaciones

Los estudiantes recibirán invitaciones para unirse a nuestra organización de Github, si no aceptan la invitación, nunca serán parte de su organización y no tendrán acceso a funciones como: Acceso a repositorios privados, uso gratuito de Github Codespaces en los repositorios de la academia, etc.

### Mantener un seguimiento de los usuarios

4Geeks.com agregará/eliminará automáticamente usuarios según la actividad de la cohorte, pero siempre debe estar al tanto de los cambios que se realizan y asegurarse de que sus estudiantes sean agregados y eliminados correctamente.

## Sincronización asincrónica

Por razones logísticas y porque un estudiante puede pertenecer a varias academias, hemos decidido evitar la sincronización en tiempo real; la sincronización ocurrirá en un proceso por lotes cada pocos minutos. El intervalo exacto está por determinarse.

## Preguntas frecuentes

- **¿Qué sucede si los estudiantes en cohortes que nunca terminan no se gradúan y permanecen `activos` para siempre?**

    El sistema seguirá asumiendo que el estudiante pertenece a tu academia. Permanecerá dentro de su organización de Github para siempre. Siempre puedes eliminar manualmente al estudiante desde el [panel de administración]((https://admin.4geeks.com/admin/github).
    
- **¿Qué sucede si el usuario está en varias cohortes, pero es eliminado de una?**
    
    El sistema se asegurará de que solo se elimine de la organización de GitHub si pierde el estado `activo` en todas las cohortes.
    
- **¿Qué sucede si el usuario está en varias academias?**
    
    Si el usuario está en varias cohortes en varias academias, solo consideraremos aquellas cohortes en las que el estudiante siga activo.
