https://github.com/aalvaroo7/INFORMATICAII.git


# EJERCICIOS EN PAREJA HTML 
Por Daniel Jose y Álvaro Martín 

## EJERCICIO 1(criterios)

1. Enunciado
   Crea una página web de "Reserva de Eventos" con las siguientes características:

1. Estructura Semántica
   El sistema debe organizar el contenido web utilizando los siguientes elementos HTML
   semánticos, asegurando una estructura clara y navegable.
   • <header>,<nav>,<main>,<section>,<article>,<footer>

2. Formulario de Reserva
   El formulario permitirá a los usuarios registrarse para un evento y debe ser accesible desde la
   sección <main>. Este formulario incluirá los siguientes campos y validaciones:
   • Campo de texto para nombre completo: Obligatorio (con atributo required).
   • Campo de email: Obligatorio, con validación de formato (HTML5).
   • Selector de fecha: Un campo input de tipo date para que los usuarios seleccionen la
   fecha del evento.
   • Selector de hora: Un campo input de tipo time para que los usuarios elijan la hora del
   evento.
   • Desplegable de eventos: Un menú desplegable que permitirá seleccionar entre opciones
   como "Concierto", "Conferencia" y "Taller".
   • Casilla de verificación de términos y condiciones: Obligatorio para aceptar las políticas
   del evento.
   • Radio buttons para tipo de entrada: Los usuarios podrán seleccionar entre "VIP" y
   "General".
   • Botón de envío: Un botón para procesar la reserva y enviar el formulario.
3. Accesibilidad
   El sistema debe cumplir con los estándares de accesibilidad mediante:
   • Atributo aria-label: Añadir este atributo en cada campo del formulario para describir el
   propósito de los elementos para lectores de pantalla.
   • Atributo tabindex: Establecer el orden de navegación lógico para los usuarios que
   navegan utilizando el teclado.
4. Enlaces y Multimedia
   En la sección <footer>, el sistema debe incluir:
   • Enlaces a redes sociales: Con texto descriptivo para mejorar la experiencia del usuario y
   facilitar la accesibilidad.
   • Video de introducción: Un video embebido dentro de la página utilizando el tag <video>,
   con controles habilitados. Opcionalmente, el video debe contar con subtítulos para
   usuarios con discapacidad auditiva.
5. Metadatos
   Para mejorar la optimización en motores de búsqueda (SEO) y proporcionar información
   adicional:
   • Meta descripción: Añadir una etiqueta <meta> con la descripción del contenido de la
   página.
   • Palabras clave y autor: Incluir etiquetas <meta> con las palabras clave relevantes para la
   página y el nombre del autor.


2. Enunciado
   Ejercicio 1: Estructura Semántica
   Crea la estructura básica de la página utilizando los elementos semánticos mencionados.
   Dentro del <header>, incluye un título y un menú de navegación (<nav>). El contenido principal
   irá dentro del <main>, mientras que en el <footer>, deberás colocar los enlaces a redes sociales.
   Ejercicio 2: Formulario de Reserva
   En el <main>, añade un formulario de reserva que incluya los campos solicitados (nombre,
   email, fecha, hora, selección de evento, tipo de entrada, aceptación de términos). Asegúrate de
   que el formulario tenga los atributos requeridos y las etiquetas aria-label para accesibilidad.
   Ejercicio 3: Accesibilidad
   Ajusta los campos del formulario para que tengan atributos de accesibilidad como aria-label y
   tabindex. Estos atributos deben estar correctamente configurados para asegurar que los
   usuarios puedan navegar fácilmente a través del formulario utilizando el teclado.
   Ejercicio 4: Enlaces y Multimedia
   Añade un gif de introducción. En el <footer>, crea una lista con enlaces a tus redes sociales
   usando un texto descriptivo para cada uno. Añadiendo los enlaces de:
   • https://media.giphy.com/media/XAxylRMCdpbEWUAvr8/giphy.gif
   • https://www.facebook.com
   • https://www.twitter.com
   • https://www.instagram.com
   Ejercicio 5: Metadatos
   En la sección <head>, añade etiquetas <meta> que contengan una descripción del sitio, palabras
   clave relevantes, y la información del autor.
   Página 6




Recomendaciones
• Asegúrate de que cada sección de la página esté claramente definida utilizando elementos
semánticos. Esto no solo mejora la accesibilidad y el SEO, sino que también facilita la
lectura y mantenimiento del código.
• Recuerda siempre pensar en la accesibilidad. Los usuarios que usan lectores de pantalla o
navegan por la web mediante el teclado deben poder interactuar sin problemas con el
formulario.
• Valida los campos necesarios (required) como el nombre y el email. Además, asegúrate de
que el campo de email tenga validación de formato por defecto.
• Asegúrate de que el video incluya controles (controls) para que los usuarios puedan
pausarlo, adelantarlo o cambiar el volumen. Los subtítulos son opcionales pero altamente
recomendados para mejorar la accesibilidad.
Tecnologías y Herramientas
• HTML5: Para la estructura semántica del documento y la creación del formulario.
• Usa atributos aria-label y tabindex para mejorar la accesibilidad.
• Incluye etiquetas <meta> para mejorar el SEO de la página.
• IDE: Webstorm, SublimeText o similares.
• Navegador: Mozilla Firefox o similares compatibles con HTML5.


