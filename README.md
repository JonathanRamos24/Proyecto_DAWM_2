# ESCUELA SUPERIOR POLITÉCNICA DEL LITORAL
## FACULTAD DE INGENIERÍA EN ELECTRICIDAD Y COMPUTACIÓN

**Fecha:** 16 de octubre de 2026  
**Nombre de la materia:** Desarrollo de Aplicaciones Web y Móviles  
**Código de la materia:** SOFG1006  
**Proyecto:** PROYECTO 02: EXPLORANDO LA CULTURA CON LA WEB (Fase 3: Desarrollo - Sprint 1)  
**Integrantes (Grupo 16):** Naranjo Muñoz Pablo David - Ramos Macías Jonathan David  

---

## Contenido
1. [Análisis](#1-análisis)
2. [Planificación](#2-planificación)
3. [Diseño](#3-diseño)
4. [Implementación](#4-implementación)
5. [Despliegue](#5-despliegue)
6. [Bibliografía](#6-bibliografía)

---

## 1. Análisis

En la fase previa de levantamiento de información se realizó un estudio de campo y entrevistas comunitarias sobre la actividad **"Apropiación cultural y artística del espacio público en Plaza Guayarte"**, desarrollada durante los fines de semana en la Plaza Guayarte (ubicada en la Av. Carlos Julio Arosemena, Guayaquil).

Esta actividad consiste en la asistencia ciudadana para el uso recreativo del espacio público al aire libre, integrando el consumo de alimentos y bebidas en emprendimientos gastronómicos locales con expresiones artísticas, muralismo, música en vivo y ferias independientes. El levantamiento de información involucró a perfiles clave de la comunidad:
* **Visitantes y comensales.**
* **Emprendedores gastronómicos** de los contenedores y locales comerciales.

A partir de los datos recopilados (caracterización del espacio, encuestas cerradas sobre frecuencia de visita, motivación, accesibilidad de precios y nivel de satisfacción, así como testimonios abiertos sobre el impacto urbano, problemáticas como parqueo o clima, y registro multimedia), se identificó la necesidad de desarrollar una *landing page* informativa y documental. Su propósito es visibilizar la dinámica cultural y comercial de Plaza Guayarte, presentar los resultados y testimonios obtenidos en las entrevistas comunitarias, mostrar la galería multimedia del entorno y canalizar sugerencias ciudadanas para la mejora continua del espacio público.

---

## 2. Planificación

Considerando los datos recopilados durante las entrevistas y la observación en campo en Plaza Guayarte, se determinaron seis secciones estructuradas para conformar la *landing page*. A continuación, en la **Tabla 1**, se detalla la organización del contenido indicando el nombre de cada sección, su propósito comunicacional y los datos específicos que se presentarán:

### Tabla 1: Organización del contenido de la Landing Page

| Nombre de la sección | Propósito | Datos que se presentarán |
| :--- | :--- | :--- |
| **1. Portada Principal (Header)** | Captar la atención del visitante desde el primer instante e introducir la temática central de la actividad comunitaria en Guayaquil. | - **Título oficial:** "Apropiación cultural y artística del espacio público en Plaza Guayarte".<br>- **Subtítulo:** Punto de encuentro entre cultura, arte urbano, gastronomía y comunidad en Guayaquil.<br>- **Ubicación y jornada:** Av. Carlos Julio Arosemena (Jornadas de fin de semana). |
| **2. Contextualización: Acerca de la Actividad (Body)** | Explicar en qué consiste la actividad comunitaria, su relevancia urbana para Guayaquil y los actores sociales que convergen en la plaza. | - Descripción del uso recreativo del espacio público al aire libre.<br>- **Perfiles involucrados:** Estudiantes universitarios del sector, familias, artistas urbanos/músicos y emprendedores gastronómicos.<br>- **Relevancia comunitaria:** Armonía entre el emprendimiento local, el arte y el esparcimiento diario.<br>- Fotografía panorámica principal de Plaza Guayarte. |
| **3. Pilares de la Experiencia y Galería Multimedia (Body)** | Exhibir visualmente las actividades que motivan la asistencia ciudadana junto con la evidencia fotográfica y audiovisual levantada en campo. | - **Bloque 1: Oferta Gastronómica y Emprendimientos:** Locales de comida y bebida, ambiente accesible y puntos de encuentro.<br>- **Bloque 2: Expresiones Artísticas y Cultura:** Música en vivo, murales de arte urbano, ferias libres y presentaciones de fin de semana.<br>- **Evidencia multimedia:** Fotografías y videos del entorno capturados con consentimiento durante la jornada. |
| **4. Percepción Ciudadana y Resultados de Entrevistas (Body)** | Presentar los hallazgos cuantitativos y cualitativos obtenidos de las preguntas cerradas y abiertas aplicadas a los visitantes, artistas y emprendedores. | - **Estadísticas de preguntas cerradas:** Frecuencia de visita en fines de semana, motivación principal (comida, música, paseo), percepción de precios/accesibilidad y calificación general de la experiencia.<br>- **Voces de la comunidad (Preguntas abiertas):** Lo que más disfrutan los ciudadanos, el impacto positivo para Guayaquil y las dificultades identificadas (parqueo, seguridad, clima). |
| **5. Propuestas de Mejora y Buzón Ciudadano (Body)** | Recopilar nuevas opiniones, propuestas de eventos o sugerencias de mejora por parte de visitantes, artistas o emprendedores interesados en Plaza Guayarte. | - Resumen de propuestas ciudadanas recolectadas (nuevos tipos de locales y eventos culturales deseados).<br>- **Formulario interactivo:** Nombre o seudónimo, perfil (visitante, emprendedor, artista), y mensaje para la plaza. |
| **6. Información Logística, Ética y Créditos (Footer)** | Proveer la ubicación geográfica del espacio estudiado, la nota de consideración ética del proyecto académico y los datos del equipo investigador. | - **Dirección:** Plaza Guayarte, Av. Carlos Julio Arosemena, Guayaquil, Ecuador.<br>- **Nota de Consideración Ética:** Declaración de uso exclusivamente académico y protección de datos personales/consentimiento informado.<br>- **Equipo investigador:** Pablo Naranjo y Jonathan Ramos (Grupo 16 - ESPOL).<br>- Enlaces al repositorio de GitHub y redes. |

---

## 3. Diseño

Para el desarrollo de la primera versión funcional de la *landing page*, se exploró el catálogo de plantillas gratuitas HTML5 y CSS3 del repositorio **HTML5 UP** [1]. Considerando que nuestro proyecto combina un carácter documental, fotográfico y de reportaje comunitario sobre Plaza Guayarte, se preseleccionaron tres plantillas candidatas: **Massively** [2], **Telephasic** [3] y **Photon** [4].

### Análisis comparativo de plantillas

En la **Tabla 2** se comparan las tres plantillas candidatas evaluando los cinco criterios técnicos y de experiencia de usuario solicitados:

#### Tabla 2: Cuadro comparativo de plantillas de HTML5 UP

| Criterio | Plantilla 1: Massively | Plantilla 2: Telephasic | Plantilla 3: Photon |
| :--- | :--- | :--- | :--- |
| **Estructura** | Estructura tipo revista por una portada a pantalla completa (*full-screen hero*), barra de navegación integrada, una sección principal ancha para el artículo destacado (*featured post*), una cuadrícula (*grid*) modular de 2 columnas para múltiples bloques temáticos y un *footer* dividido en formulario y datos logísticos. | Estructura corporativa tradicional multipágina con un encabezado simétrico, dos bloques promocionales superiores, un banner intermedio y una sección inferior de 3 columnas pensada para vender servicios o productos empresariales. | Estructura *one-page* minimalista dividida en bandas horizontales simples: un encabezado con ícono central, secciones alternadas de texto breve con imagen lateral, una grilla pequeña de 3 columnas y botones básicos. |
| **Navegación** | Transición suave (*smooth scroll*) desde la portada hacia el contenido mediante el botón circular de bajada, barra de navegación superior con pestañas claras y enlaces rápidos, e integración directa con el pie de página. | Utiliza un menú superior horizontal con soporte para submenús desplegables complejos (mediante jQuery Dropotron). Está diseñada para navegar entre múltiples páginas separadas más que para una lectura continua de *landing page*. | Navegación sumamente limitada: carece por completo de una barra de navegación (*navbar*) superior o lateral. El usuario depende únicamente del desplazamiento manual (*scroll*), dificultando ir directo a las entrevistas o al formulario. |
| **Diseño** | Moderno, editorial y de alto impacto visual. Emplea un fondo fijo con efecto *parallax* que resalta el contenedor central blanco, ofreciendo una jerarquía tipográfica y fotográfica ideal para crónicas urbanas, galerías de arte de Guayarte y reportajes comunitarios. | Diseño de corte empresarial clásico con degradados suaves y distribución rígida. Resulta visualmente plano y corporativo, restándole fuerza al colorido cultural, artístico y gastronómico de Plaza Guayarte. | Diseño limpio con cabeceras de fondo degradado e íconos vectoriales, pero demasiado austero. No cuenta con el dinamismo visual necesario para destacar fotografías grandes del entorno ni testimonios extensos. |
| **Adaptabilidad (*Responsive Design*)** | Altamente adaptable a dispositivos móviles, *tablets* y escritorio. Las tarjetas de la cuadrícula pasan automáticamente de 2 columnas a 1 columna vertical en teléfonos móviles, y el menú se convierte en un panel lateral deslizable (*off-canvas menu*). | Es *responsive* gracias a su sistema de grillas CSS, pero sus menús desplegables multinivel y sus bloques simétricos pierden legibilidad e impacto visual en pantallas verticales de teléfonos móviles. | Se adapta correctamente a pantallas móviles apilando los bloques en formato vertical; sin embargo, al carecer de menú móvil (*hamburger menu*), recorrer todas las secciones de la entrevista en un celular resulta poco ergonómico. |
| **Facilidad de personalización** | Muy alta. El código HTML5 es semántico y cada bloque (portada, caracterización destacada, tarjetas de actividades/entrevistas y *footer* con formulario) está encapsulado en etiquetas `<article>` y `<section>`, facilitando insertar las fotos y datos de Guayarte sin alterar el CSS. | Media. Al estar orientada a un sitio corporativo multipágina y depender de *scripts* para menús desplegables, requiere eliminar varias estructuras innecesarias para adaptarla a una *landing page* comunitaria. | Alta por la simplicidad de su código base, pero limitada funcionalmente: obligaría a programar desde cero una barra de navegación y a maquetar manualmente el formulario de sugerencias ciudadanas en el cierre. |

---

### Selección y justificación de la plantilla

* **Plantilla seleccionada:** **Massively** [2].

* **Justificación de la elección:**  
  Se seleccionó la plantilla **Massively** porque su enfoque de publicación narrativa y fotográfica responde de manera exacta a las necesidades del levantamiento de información realizado en **Plaza Guayarte**:
  1. **Enfoque de reportaje comunitario y visual:** A diferencia de *Telephasic* y *Photon*, **Massively** tiene un diseño editorial pensado para contar historias con gran respaldo fotográfico. Su portada a pantalla completa permite mostrar de fondo el ambiente artístico y colorido de los contenedores y murales de Plaza Guayarte desde el primer segundo.
  2. **Correspondencia exacta con la Tabla de Organización del Contenido:** 
     * El bloque principal **Featured Post** se adapta perfectamente para presentar la *Caracterización de la Actividad* (qué es, dónde queda y qué perfiles de la comunidad guayaquileña participan).
     * La cuadrícula modular de artículos (**Posts Grid**) permite dividir de forma ordenada los pilares de la plaza (*Oferta Gastronómica*, *Arte y Música en vivo*) y los resultados del trabajo de campo (*Estadísticas de preguntas cerradas*, *Testimonios de preguntas abiertas sobre beneficios y problemas como parqueo o clima*, y la *Evidencia Multimedia*).
  3. **Formulario y datos logísticos listos para usar:** El *Footer* de **Massively** incluye por defecto un diseño dividido que integra un formulario completo junto con los bloques de dirección física, información de los entrevistadores (Grupo 16) y la nota de consideración ética.

---

## 4. Implementación

Para construir la primera versión funcional de la *landing page*, se descargó el paquete oficial de la plantilla **Massively** desde HTML5 UP y se integró su estructura completa de directorios y archivos dentro del repositorio del proyecto (`index.html`, `generic.html`, `elements.html`, `assets/css/`, `assets/js/`, `assets/sass/`, `assets/webfonts/` e `images/`), verificando que todas las dependencias locales funcionen sin errores.

---

## 5. Despliegue

El control de versiones, la organización de los archivos fuente de la plantilla y la documentación del proyecto se gestionaron a través de un repositorio público en **GitHub** [5].

* **URL del Repositorio en GitHub:** [https://github.com/JonathanRamos24/Proyecto_DAWM_2.git](https://github.com/JonathanRamos24/Proyecto_DAWM_2.git)
* **Documento de Reporte (PDF):** Incluido en el repositorio como `Reporte Proyecto 02 G16.pdf`.
* **Verificación de la primera versión funcional:** Los archivos HTML, CSS, JavaScript y recursos gráficos mantienen la integridad de sus rutas relativas. Al abrir el proyecto en cualquier navegador web moderno, la página carga correctamente su diseño *responsive*, sus efectos visuales de transición y su navegación básica entre secciones. Asimismo, se incluyó el archivo `README.md` y el documento de reporte siguiendo la plantilla establecida.

---

## 6. Bibliografía

[1] AJ, "HTML5 UP! Responsive HTML5 and CSS3 Site Templates," *HTML5 UP*, 2026. [En línea]. Disponible en: https://html5up.net/.

[2] AJ, "Massively - HTML5 UP," *HTML5 UP*, 2026. [En línea]. Disponible en: https://html5up.net/massively.

[3] AJ, "Telephasic - HTML5 UP," *HTML5 UP*, 2026. [En línea]. Disponible en: https://html5up.net/telephasic.

[4] AJ, "Photon - HTML5 UP," *HTML5 UP*, 2026. [En línea]. Disponible en: https://html5up.net/photon.

[5] GitHub, Inc., "GitHub Documentation," *GitHub Docs*, 2026. [En línea]. Disponible en: https://docs.github.com/.