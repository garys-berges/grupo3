# Grupo 3 – MediCitas

## Descripción del proyecto

MediCitas es la propuesta de una plataforma web pensada para acercar a los pacientes a los profesionales de la salud. La idea es que una persona pueda conocer las especialidades disponibles y solicitar una cita médica desde un formulario sencillo, indicando sus datos, la especialidad que necesita y la fecha y el horario que prefiere. Luego, el personal administrativo revisa la solicitud y confirma la cita.

## Fase 1: Maquetación

En esta primera etapa nos enfocamos en darle forma visual al sitio. Partimos de los wireframes que diseñamos como equipo y, a partir de ellos, construimos las páginas con HTML y CSS. Todavía no hay lógica de servidor ni base de datos; el objetivo de esta fase es definir cómo se ve MediCitas, cómo se organiza la información y cómo navega el usuario entre una página y otra.

Por ahora el sitio cuenta con una página de inicio (`index.html`), donde el paciente conoce la plataforma y las especialidades, y con la página para solicitar una cita (`solicitar-cita.html`), que contiene el formulario. Los bocetos están en la carpeta `Wireframes`, los estilos en `css` y los recursos gráficos en `imagenes`.

**Tecnologías:** HTML5 y CSS3.

## Fase 2: Interactividad con JavaScript

En esta segunda etapa el sitio cobra vida. Sobre la maquetación que construimos en la fase anterior, incorporamos JavaScript para que MediCitas responda a las acciones del usuario, y todo se ejecuta directamente en el navegador, sin servidor ni base de datos.

El código se organiza en un archivo JavaScript externo, enlazado a nuestras páginas, que reúne funciones propias encargadas de las distintas tareas. Con él, el formulario de `solicitar-cita.html` revisa que los campos obligatorios estén completos y que el correo tenga un formato válido, y muestra los mensajes de error en la misma página para que el paciente sepa qué corregir. Además, añadimos un componente dinámico que hace la navegación más útil e interactiva.

**Tecnologías:** HTML5, CSS3 y JavaScript.

## Integrantes

| # | Integrante | Rol |
|---|------------|-----|
| ★ | **David Adames Castillo** | Líder |
| 2 | Roberto Arnaud Medina | Integrante |
| 3 | Garys Bergés Heyliger | Integrante |
| 4 | Yorbis Blanco Mora | Integrante |
| 5 | Fernando Estrella Domínguez | Integrante |
| 6 | Alber Montero Ramírez | Integrante |
| 7 | Josué Ramírez Álvarez | Integrante |
| 8 | Génesis Adriana Soto | Integrante |

## Organización del repositorio

El trabajo de la primera etapa se encuentra en la rama `fase-1-maquetacion` y el de la segunda en `fase-2-javascript`. Al terminar cada fase, su rama se une a `main`. Cada integrante sube sus cambios desde su propia cuenta, de modo que el historial de commits refleja lo que aportó cada uno.

## Cómo ver el proyecto

Basta con clonar el repositorio y abrir `index.html` en el navegador:

    git clone https://github.com/garys-berges/grupo3.git
