# PROMPT 02 — GENERA LAS IMÁGENES Y CONSTRUYE TU PÁGINA WEB
Versión 3.0 — Frontend preparado para integración Full Stack

> **Metodología educativa:** Desarrollo Web con Inteligencia Artificial  
> **Autor:** Joel Jonathan Pérez Delgado — Dkript  
> **Licencia del material educativo:** Creative Commons Attribution 4.0 International (CC BY 4.0)  
> *Consulta [LICENSE](LICENSE) y [NOTICE.md](NOTICE.md) para las condiciones completas.*

---

## ROL

Actúa como desarrollador frontend senior, diseñador UI/UX, director de arte digital, especialista en IA generativa y tutor de programación web.

Quiero construir una página web original, moderna, responsive e interactiva utilizando la identidad visual que aprobé en la etapa anterior.

## 1. ANALIZAR EL DISEÑO APROBADO

Antes de comenzar, localiza y lee:

`DESIGN_SYSTEM.md`

Este documento es la referencia principal para:

- Nombre y temática.
- Colores.
- Tipografías.
- Componentes.
- Estructura.
- Imágenes.
- Animaciones.
- Comportamiento responsive.
- Estilo previsto para login y administración.
- Contenido que posteriormente será administrable.

No reemplaces mis decisiones por una plantilla genérica.

Si falta información secundaria, resuélvela de forma coherente con el diseño aprobado.

No repitas la entrevista creativa.

## 2. TECNOLOGÍAS

Utiliza:

- HTML5.
- CSS3.
- JavaScript.
- Imágenes generadas mediante IA, cuando exista una herramienta disponible.

En esta etapa no utilices Laravel, React, MySQL ni frameworks complejos.

Crea una estructura sencilla:

```text
mi-proyecto-web/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── assets/
│   └── images/
├── DESIGN_SYSTEM.md
├── CONTENT_MAP.md
└── README.md
```

Puedes agregar archivos cuando exista una razón clara.

Usa nombres comprensibles y una organización apropiada para estudiantes.

## 3. GENERACIÓN DE IMÁGENES

Genera recursos visuales originales y coherentes con la temática.

Considera:

- Imagen principal del Hero.
- Recursos para secciones informativas.
- Imágenes de tarjetas.
- Galería, si corresponde.
- Fondos y elementos decorativos.

No generes cantidades fijas innecesarias.

Produce solamente los recursos que realmente necesite el diseño.

### Calidad visual

- Respeta la paleta seleccionada.
- Mantén consistencia artística.
- Utiliza dimensiones apropiadas.
- Evita marcas de agua.
- No incorpores texto dentro de las imágenes cuando pueda añadirse mediante HTML.
- Optimiza el peso de los archivos.
- Conserva suficiente espacio visual para textos y botones.

Guarda las imágenes localmente en `assets/images/`.

Si la herramienta no puede generar imágenes, no inventes resultados. Prepara prompts para un generador externo y registra los recursos pendientes.

## 4. CONSTRUIR LA PÁGINA

Desarrolla la estructura descrita en `DESIGN_SYSTEM.md`.

Utiliza una composición original y adaptada a la temática.

Implementa, según corresponda:

### Header

- Nombre o logotipo.
- Navegación.
- Menú responsive.
- Estados hover y focus.

### Hero

- Título.
- Descripción.
- Imagen principal.
- Botón de acción.
- Fondo atractivo.
- Animación de entrada cuando corresponda.

### Contenido temático

- Secciones informativas.
- Tarjetas.
- Características.
- Galería.
- Proyectos, productos o elementos temáticos.

### Contacto

Incluye una sección de contacto coherente con el diseño.

Cuando corresponda, prepara la interfaz de un formulario con:

- Nombre.
- Correo electrónico.
- Asunto.
- Mensaje.

Este formulario se conectará posteriormente con Laravel en el Prompt 03.

**No simules un envío exitoso de mensajes si todavía no existe backend.**

Durante esta etapa puedes mostrar claramente que el envío estará disponible en la versión Full Stack o utilizar una alternativa real sencilla, como un enlace de correo, cuando sea apropiado.

Prepara el diseño de los campos, mensajes de validación y confirmaciones para su posterior integración.

### Footer

Incluye:

- Nombre del proyecto.
- Navegación secundaria.
- Información pertinente.
- Enlaces funcionales.
- Créditos académicos discretos cuando corresponda.

## 5. ANIMACIONES E INTERACTIVIDAD

Implementa las animaciones aprobadas.

Puedes utilizar:

- Efectos hover.
- Apariciones al desplazarse.
- Tarjetas con movimiento 3D.
- Glassmorphism.
- Transiciones.
- Fondos animados.
- Interacciones ligeras con el cursor.

No utilices todos los efectos por obligación.

Prioriza una experiencia visual agradable y buen rendimiento.

Respeta `prefers-reduced-motion`.

No instales bibliotecas innecesarias.

Si existen Skills de UI/UX configuradas desde el Prompt 00, utilízalas cuando aporten valor.

## 6. PREPARACIÓN PARA LARAVEL Y DKRIPT CORE

La página se convertirá posteriormente en una aplicación Laravel.

Por ello:

### A. Separar estructura, estilos y lógica

- Mantén HTML organizado.
- Utiliza CSS reutilizable.
- Mantén JavaScript separado.
- Evita dependencias innecesarias.
- Utiliza nombres de clases comprensibles.

### B. Variables visuales compartidas

Define variables CSS para:

- Color primario.
- Secundario.
- Acento.
- Fondo.
- Superficies.
- Texto.
- Bordes.
- Estados visuales.
- Tipografías.

Estas variables servirán después como referencia para personalizar el panel de Dkript Core.

### C. Contenido administrable

Identifica cuáles elementos deberán convertirse en datos dinámicos:

- Títulos.
- Descripciones.
- Imágenes.
- Tarjetas.
- Galerías.
- Enlaces.
- Botones.
- Orden y visibilidad de secciones.

Mantén el contenido original organizado y fácilmente identificable.

### D. Mapa de contenido

Crea:

`CONTENT_MAP.md`

Documenta brevemente:

1. Secciones de la página.
2. Contenidos que serán editables.
3. Imágenes asociadas.
4. Componentes reutilizables.
5. Funcionalidad temática prevista.
6. Formulario de contacto previsto.
7. Elementos que permanecerán estáticos.

Este archivo ayudará a convertir la página a Laravel y MySQL sin perder información.

No crees modelos Eloquent, migraciones ni tablas todavía.

## 7. RESPONSIVE Y ACCESIBILIDAD

Comprueba que la página funcione correctamente en:

- Computadoras.
- Tablets.
- Celulares.

Verifica:

- Navegación funcional.
- Textos legibles.
- Imágenes adaptables.
- Ausencia de desplazamiento horizontal accidental.
- Botones utilizables.
- Etiquetas adecuadas en formularios.
- Contraste suficiente.
- Navegación básica con teclado.
- Textos alternativos en imágenes.

## 8. PRUEBAS ESENCIALES

Realiza una sola ronda de comprobaciones.

Verifica:

1. La página abre correctamente.
2. Los archivos CSS y JavaScript cargan.
3. Las imágenes están disponibles o sus faltantes están documentados.
4. La navegación funciona.
5. Los botones realizan acciones reales.
6. Las animaciones funcionan.
7. No hay errores importantes de JavaScript.
8. El diseño es responsive.
9. La identidad coincide con `DESIGN_SYSTEM.md`.

No ejecutes auditorías redundantes ni protocolos empresariales.

## 9. DOCUMENTACIÓN

Genera un `README.md` con:

- Nombre y temática.
- Descripción.
- Tecnologías.
- Estructura de carpetas.
- Recursos visuales.
- Animaciones.
- Cómo ejecutar la página.
- Cómo cambiar textos, colores e imágenes.
- Funcionalidades que se integrarán en la etapa Full Stack.

Explica cuatro conceptos importantes de HTML, CSS o JavaScript utilizados.

## Créditos y autoría del proyecto del estudiante

Esta metodología educativa fue desarrollada por **Joel Jonathan Pérez Delgado** bajo **Dkript**, licenciada bajo **CC BY 4.0** (ver [LICENSE](LICENSE) y [NOTICE.md](NOTICE.md)). La metodología es obra de su autor; el trabajo creativo original del estudiante es obra y autoría del estudiante.

- El trabajo creativo original del estudiante — código, diseño, imágenes y contenido propios — debe reconocerse como autoría del estudiante.
- Cuando se utilicen recursos externos (imágenes, fuentes, bibliotecas, iconos), deben conservarse los créditos y atribuciones exigidos por sus respectivas licencias.
- No se agregarán marcas de agua ni logotipos de Dkript Inc. automáticamente en las páginas del proyecto escolar.
- Las condiciones de las licencias de recursos de terceros deben respetarse e indicarse en el README.md cuando corresponda.

## 10. CIERRE OBLIGATORIO

Al terminar:

1. Finaliza las tareas iniciadas.
2. Cierra navegadores de prueba.
3. Cierra compilaciones y procesos auxiliares innecesarios.
4. Conserva únicamente el servidor del proyecto si es necesario.
5. No cierres procesos de otros proyectos.
6. Informa la carpeta y URL local.
7. No realices commits, push ni despliegues sin autorización.
8. Resume qué se implementó y qué está pendiente.
9. Finaliza completamente la ejecución del agente.

## RESULTADO ESPERADO

Una página web:

- Original.
- Visualmente atractiva.
- Responsive.
- Interactiva.
- Con imágenes adecuadas a su temática.
- Con código sencillo.
- Con diseño aprobado conservado.
- Con contacto preparado para la integración posterior.
- Con `DESIGN_SYSTEM.md`, `CONTENT_MAP.md` y `README.md`.

**INSTRUCCIÓN FINAL:** analiza el diseño aprobado, genera los recursos visuales disponibles y construye la página completa.

No avances todavía a Laravel.

Cuando termines, demuestra el resultado y explica cómo podrá convertirse en una aplicación Full Stack.