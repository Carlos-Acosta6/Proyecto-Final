1. Descripción del sitio
   Fundación Caminos del Saber es una web informativa y de captación de apoyos para una ONG educativa ficticia. El sitio está pensado como proyecto escolar
   y contiene las secciones principales necesarias para una ONG real: Inicio, Nosotros, Proyectos, Blog, Transparencia, Equipo, Contacto, Donar.
   
   Su objetivo: presentar la misión, mostrar proyectos e impacto, ofrecer transparencia y facilitar la colaboración (donaciones y voluntariado).

   Características principales:
  
      Diseño accesible y semántico (uso correcto de header, nav, main, section, article, footer).
  
      Formulario de donación (simulado) con tipos de donación: Donación única, Donación mensual, Apadrinamiento estudiantil, etc.
  
      Páginas de transparencia con tablas y enlaces a informes PDF.
  
      Blog (artículos), galería multimedia (img/video) y página de equipo con fichas.
  
      Footer con contacto, enlaces rápidos, redes y legal.

3. Mapa de navegación (sitemap)
      
      INICIO
      │
      ├── SOBRE NOSOTROS
      │
      ├── PROYECTOS
      │
      ├── BLOG / NOTICIAS
      │
      ├── TRANSPARENCIA
      │
      ├── EQUIPO
      │
      ├── DONAR
      │
      └── CONTACTO

 
4. Decisiones semánticas y de accesibilidad

    Estructura semántica

      "header" contiene logo, título y <nav> principal con enlaces.

      "main" agrupa el contenido principal en <section "id="inicio">, "<section "id="proyectos">", etc.

      Cada artículo del blog usa <section> con <h2> para el título.

      Formularios usan "form", "fieldset", "legend" para agrupar campos y "label for="..."" asociado a cada 'input""/select".

      Tablas en transparencia usan <table>, <thead>, <tbody>, <caption>

    Accesibilidad (WCAG)

     Uso de alt descriptivo en todas las imágenes (<img "alt="">), ejemplo: alt="Niños leyendo en aula de la comunidad Los Pinos".

   Etiquetas y atributos

     link para los iconos(<link "rel="icon" href="mi_icono">).
     meta de viewport y lang="es" en <html "lang="es">.
     <img "src="" alt="">, <video 'controls>

5. Validación W3C
     (archivo de word)

7. Créditos y fuentes

     Textos y contenido: creado para el proyecto por Carlos Acosta - Poyecto Final.
     UNESCO – Educación para el Desarrollo Sostenible (https://www.unesco.org)
     UNICEF – Programas de apoyo educativo en América Latina (https://www.unicef.org)
     Fundación Ayuda en Acción – Transparencia y gestión de proyectos sociales (https://ayudaenaccion.org)
     Save the Children – Iniciativas de apadrinamiento educativo (https://savethechildren.es)
     Banco Mundial – Educación y desarrollo humano (https://www.bancomundial.org)
     Datos financieros y números: simulados para fines del proyecto.

Glosario de términos técnicos

  <link> — Conecta el documento HTML con archivos externos, como hojas de estilo CSS o íconos.

  <div> — Contenedor genérico usado para estructurar y agrupar contenido dentro de una página.

  <section> — Define una sección o bloque temático dentro del documento.

  id — Identificador único para un elemento, útil para estilos CSS o scripts.

  class — Agrupa elementos con el mismo nombre de clase para aplicarles el mismo estilo o comportamiento.

  <h1> — Encabezado principal de una página o sección; debe existir solo uno por documento.

  <h2> — Subtítulo de segundo nivel, ideal para dividir secciones.

  <h3> — Subtítulo de tercer nivel dentro de un bloque o tema.

  <p> — Etiqueta usada para crear párrafos de texto.

  <video> — Inserta videos en la página con controles integrados (reproducir, pausar, volumen).

  <img> — Muestra imágenes con la ruta definida en el atributo src.

  <a> — Crea hipervínculos a otras páginas o archivos mediante href.

  <form> — Define un formulario para recopilar información del usuario.

  <fieldset> — Agrupa varios campos relacionados dentro de un formulario.

  <legend> — Asigna un título al grupo de campos definidos dentro de <fieldset>.

  <input> — Campo de entrada que recibe datos del usuario (texto, correo, número, etc.).

  <header> — Encabezado de una página o sección; contiene el logo, menú o título principal.
  
  <footer> — Pie de página; incluye contactos, derechos de autor y enlaces útiles.

  <small> — Muestra texto en tamaño reducido, generalmente para notas o aclaraciones.
  
  <strong> — Destaca texto importante con mayor énfasis (normalmente en negrita).
  
  Mapa gráfico — Representación visual de la estructura del sitio web (mapa de navegación).
  
  Tamaño de archivo — Espacio que ocupa un documento o imagen digital (medido en KB, MB o GB).
  
  Páginas web dinámicas — Sitios cuyo contenido se actualiza o genera automáticamente con lenguajes como JavaScript o PHP.
  
  Base de datos — Conjunto organizado de información que puede ser consultada o modificada digitalmente.
  
  HTML (HyperText Markup Language) — Lenguaje base para crear y estructurar páginas web.
  
  CSS (Cascading Style Sheets) — Lenguaje que define el diseño, colores y estilos visuales de un sitio web.
  
  Responsive Design — Técnica que adapta el contenido de una página a distintos tamaños de pantalla (computadora, tablet, móvil).
  
  Formulario de contacto — Sección en una página donde los usuarios pueden enviar mensajes, preguntas o donaciones.
  
  Metaetiquetas (<meta>) — Proporcionan información adicional sobre la página, como descripción, autor o codificación de caracteres.
  
  Etiqueta semántica — Elemento HTML que describe su contenido de forma clara (por ejemplo, <header>, <footer>, <article>).

7. Resumen técnico de validación y estructura

    Resumen técnico de la estructura.
    
      index.html — página de inicio.
      
      nosotros.html — historia, misión, valores y CTA a Transparencia.
      
      proyectos.html — fichas de proyectos y CTA a Donar.
      
      blog.html — listado de artículos.
      
      transparencia.html — tablas de presupuesto, links a informes PDF y gráficas (imágenes).
      
      equipo.html — tarjetas de miembros (foto, nombre, cargo, breve bio).
      
      contacto.html — formulario de contacto (name, email, mensaje).
      
      donar.html — formulario de donaciones con tipos: Donación única, Donación mensual, Apadrinamiento estudiantil.
  
    Validación

     Añadir <!doctype html> y lang="es".
     Usar etiquetas semánticas (header, nav, main, footer).
     Incluir label en cada input y fieldset para grupos lógicos.
     Proveer alt en todas las imágenes

    Resumen técnico de accesibilidad

      Etiquetas semánticas aplicadas para encabezados, secciones y artículos.
      
      Jerarquía de texto coherente para facilitar la lectura con lectores de pantalla.
      
      Imágenes con descripciones alt claras y significativas.
      
      Elementos interactivos (botones y enlaces) con nombres accesibles y roles definidos.
