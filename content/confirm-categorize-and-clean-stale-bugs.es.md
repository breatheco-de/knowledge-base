### Mira estos vídeos
- Entendiendo [Stale Issues en GitHub](https://www.loom.com/share/775c119625ee411ba2b2207c2693f192?sid=c1d1d53f-0de6-4e29-8168-35f5462913ea)
- Tarea recurrente: [Revisando Issues sin persona asignada](https://www.loom.com/share/f666d418b10e4ea49948fd24ef7b9ca6?sid=dbba6ff1-ef0b-4165-995c-349f9e622dc1)

### Procedimiento:
1. **Ingresar a GitHub:**
- Navega hasta el repositorio de GitHub y busca informes de errores obsoletos o problemas no asignados.
- Puedes encontrarlos usando este [enlace](https://github.com/breatheco-de/breatheco-de/issues?q=is%3Aissue+label%3Astale+is%3Aopen+no%3Aasignee) o aplicando los filtros: `is:issue label:stale no:assignee is:open`.
2. **Leer y entender:**
- Lee los informes de errores para comprender el tipo de error y dónde ocurre.
3. **Replicar o Confirmar:**
- Intenta replicar el error mencionado en el informe.
- Visita el sitio web mencionado en el informe para confirmar si el error aún está presente.
4. **Acción basada en la confirmación:**
- Si el error aún está presente:
  - Retira la etiqueta `stale`.
- Agrega una o más de las siguientes etiquetas:
  - `Confirm`: si se confirmó que el error aún ocurre.
  - `BUG`: Si efectivamente es un error.
  - `Front-end`: si el error es un error de front-end.
  - `Back-end`: si el error es un error de backend.
- Si no puedes confirmar el error:
  - Agrega la etiqueta `✋ waiting-for-feedback`.
  - Revísalo en la reunión de pie.
- Si el error no ocurre:
  - Cierra el problema agregando un comentario.


Seguir este procedimiento ayudará a agilizar el proceso de gestión e informe de errores, garantizando que los problemas se identifiquen, confirmen y aborden adecuadamente de manera oportuna.
