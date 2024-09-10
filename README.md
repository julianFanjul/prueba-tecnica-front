# Prueba técnica — React developer

## Objetivo

El objetivo de esta prueba técnica es que el candidato muestre sus habilidades usando react.js y su capacidad para resolver problemas.

Pondremos el foco en obtener un código simple, bien diseñado y organizado, eficaz, cumplimiendo de todos los requerimientos solicitados.

## Desarrollo del proyecto

- Se deberá clonar este repositorio para poder modificarlo y completarlo con la resolución del proyecto.
- Una vez que su código esté listo, suba el código a un repositorio público propio y envíenos el enlace a dicho repositorio para que lo revisaremos.


## Prueba técnica
Se debera crear una pagina que mediante la utilizacion de la api de cultura ARG para obtener datos.

Documentacion: https://www.cultura.gob.ar/api/v2.0/

Pagina 1: "Tabla de organismos", se deberan presentar los datos del siguiente endpoint: https://www.cultura.gob.ar/api/v2.0/organismos en una tabla y manejar las request mediante paginacion.

Pagina 2: "Detalle de organismo", se accedera mediante un click haciendo uso del atributo "url" EJ: https://www.cultura.gob.ar/api/v2.0/organismos/13/ del detalle de un organismo en tabla de la pagina "Tabla de organismos".

Seria un plus que la paginacion se gestione mediante rutas dinamicas con react router v6, es decir, que si yo ingresara a por ejemplo: http://localhost:5173/13 , ingrese a la pagina de "Detalle de organismo" y obtenga la informacion del organismo id 13.


Se deberá incluir también `README` con instrucciones de configuración/ejecución y cualquier prueba u otra documentación que haya creado como parte de su solución.

Además, agregue la siguiente información a su archivo `README`:

- ¿Cómo decidió las opciones técnicas y arquitectónicas utilizadas como parte de su solución?
- ¿Hay alguna mejora que pueda hacer en su envío?
- ¿Qué haría de manera diferente si se le asignara más tiempo?

## Requisitos de Stack

Para el desarrollo de la aplicación deberá utilizar:

- React / React Hooks
- React-Query https://tanstack.com/query/latest/docs/framework/react/examples/basic
- Material UI o React-bootstrap https://mui.com/material-ui/getting-started/ / https://react-bootstrap.netlify.app/
- React Router V6 https://reactrouter.com/en/main
- Mobile friendly
- Manejo de errores
- _(opcional)_ T
- _(opcional)_ Integration/E2E tests
- _(opcional)_ Deploy automático
- _(opcional)_ Testing

Importante saber:
- No es necesario crear un entorno de desarrollo/producción.
- Se pueden utilizar otras librerías que crea conveniente, aunque se recomienda proporcionar una solución básica ajustada a lo solicitado, ya que nuestro objetivo principal es evaluar sus habilidades con React y Javascript.
- Puedes aplicar los estilos que consideres "esteticos" a tu gusto!
- Creemos que la comunicación es la clave del éxito. Entonces, si algo no está claro, o si tiene dudas sobre la tarea, consultanos!

> Happy coding!
