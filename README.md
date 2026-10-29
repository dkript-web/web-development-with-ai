# Desarrollo Web con Inteligencia Artificial

**Guía académica de desarrollo web con Google Antigravity, Laravel, MySQL y Dkript Core**

> **Metodología educativa:** Desarrollo Web con Inteligencia Artificial  
> **Autor:** Joel Jonathan Pérez Delgado — Dkript  
> **Licencia del material educativo:** Creative Commons Attribution 4.0 International (CC BY 4.0)  
> *Consulta [LICENSE](LICENSE) y [NOTICE.md](NOTICE.md) para las condiciones completas.*

**Versión de la metodología:** 3.0  
**Nivel:** Principiante a intermedio  
**Modalidad:** Prácticas guiadas y aprendizaje basado en proyectos  

---

## 1. Descripción

Este repositorio contiene una metodología educativa para aprender desarrollo web utilizando inteligencia artificial como herramienta de apoyo.

El objetivo es que cada estudiante pueda diseñar y desarrollar un proyecto original, comenzando por su identidad visual y evolucionando progresivamente hasta obtener una aplicación Full Stack con Laravel, MySQL y un panel de administración.

La metodología utiliza **Google Antigravity** para facilitar el diseño, la programación, la integración de componentes y las pruebas.

La inteligencia artificial debe ayudar al estudiante a aprender, no sustituir su comprensión de los fundamentos del desarrollo de software.

### ¿Qué aprenderás?

- Diseño UI/UX e identidad visual.
- Uso de inteligencia artificial generativa.
- HTML5, CSS3 y JavaScript.
- Generación de imágenes para sitios web.
- Diseño responsive y animaciones.
- PHP y Laravel.
- Bases de datos MySQL/MariaDB.
- Arquitectura MVC.
- Autenticación y permisos.
- Administración de contenido mediante un CMS.
- Formularios y comunicación por correo electrónico.
- Resolución de errores y documentación técnica.

**Cada estudiante elegirá su propia temática, colores, imágenes y funcionalidades.**

No todos deben desarrollar la misma página ni el mismo sistema.

---

## 2. Estructura del repositorio

```text
desarrollo-web-con-ia/
│
├── README.md
│
├── 00_Dev_Setup.md
├── 01_Visual_Identity.md
├── 02_Web_Creator.md
└── 03_Full_Stack_Builder.md
```

### Descripción de los archivos

| Archivo | Función |
|---|---|
| `00_Dev_Setup.md` | Detectar, instalar y configurar herramientas de desarrollo, Skills y agentes. |
| `01_Visual_Identity.md` | Definir la temática, paleta de colores, tipografías, componentes y estilo visual. |
| `02_Web_Creator.md` | Generar recursos visuales y desarrollar una página con HTML, CSS y JavaScript. |
| `03_Full_Stack_Builder.md` | Convertir la página en una aplicación Laravel con Dkript Core, MySQL, CMS y panel personalizado. |

**Importante:** ejecuta los prompts en orden. No intentes desarrollar todas las etapas simultáneamente.

---

## 3. Requisitos iniciales

### Obligatorios para comenzar

- Computadora con Windows, macOS o Linux.
- Conexión a internet.
- Acceso a Google Antigravity.
- Carpeta local que contenga los archivos de este repositorio.
- Espacio disponible y permisos suficientes para instalar herramientas, cuando sea necesario.

### Herramientas de desarrollo

Durante la preparación se revisarán:

- PHP y sus extensiones.
- Apache u otro servidor de desarrollo compatible.
- MySQL o MariaDB.
- Composer.
- Node.js y npm.
- Git.
- Herramientas de Laravel.
- Skills y agentes compatibles con Antigravity.

**No es necesario instalar todas estas herramientas manualmente antes de comenzar.**

El Prompt 00 está preparado para detectar las instalaciones existentes y ayudar a configurar las que falten.

Las instalaciones dependerán del sistema operativo, los permisos disponibles y la compatibilidad real de las herramientas.

Apache no es obligatorio cuando se utiliza el servidor local de desarrollo de Laravel.

---

## 4. Descargar y preparar los archivos

### Opción A — Descargar ZIP (recomendada para principiantes)

1. Abre este repositorio en GitHub.
2. Selecciona **Code → Download ZIP**.
3. Extrae el archivo en una carpeta de tu computadora.
4. Abre Google Antigravity.
5. Selecciona **Open Folder** o la opción equivalente.
6. Abre la carpeta que contiene los cuatro archivos `.md`.

### Opción B — Clonar con Git

Si ya tienes Git instalado:

```bash
git clone URL_DE_ESTE_REPOSITORIO
```

Sustituye `URL_DE_ESTE_REPOSITORIO` por la dirección real del repositorio del curso.

Abre la carpeta descargada en Google Antigravity.

No es obligatorio utilizar Git para completar las primeras prácticas.

### Importante

Trabaja siempre sobre una copia propia de los archivos del curso.

No modifiques los prompts originales compartidos por el docente cuando quieras personalizar tu proyecto.

---

## 5. Paso 00 — Preparación del entorno

**Archivo:** `00_Dev_Setup.md`

**Objetivo:** preparar la computadora para desarrollar aplicaciones web.

Este prompt detecta las herramientas disponibles y ayuda a configurar las faltantes.

Antes de instalar cualquier componente, revisa si existen distribuciones como:

- XAMPP.
- WAMP.
- MAMP.
- Laragon.
- Laravel Herd.
- Docker.
- Instalaciones independientes de PHP, Apache o MySQL.

También revisa Skills y agentes de desarrollo compatibles con Antigravity.

### Instrucción para Antigravity

Copia el siguiente mensaje:

> Lee completamente el archivo `00_Dev_Setup.md` de este proyecto y ejecuta sus instrucciones.
>
> Soy estudiante y necesito preparar mi computadora para las prácticas de desarrollo web con IA.
>
> Comprueba primero qué herramientas tengo instaladas. Reutiliza las que funcionen y ayuda a instalar o configurar las que falten.
>
> Explícame los pasos manuales que necesite realizar y solicita autorización antes de modificar configuraciones importantes del sistema.
>
> Al finalizar, verifica los componentes esenciales y presenta un resumen.
>
> No avances todavía al Prompt 01.

### Resultados esperados

- Entorno de desarrollo preparado.
- Herramientas verificadas.
- Skills configuradas, cuando estén disponibles.
- `ENVIRONMENT_SETUP.md`.
- `SKILLS_CONFIG.md`.

### ¿Ya tienes todo instalado?

Puedes omitir el Prompt 00 si las herramientas y Skills necesarias ya funcionan correctamente.

El Prompt 03 realizará una revisión adicional de compatibilidad antes de instalar Dkript Core.

---

## 6. Paso 01 — Identidad visual

**Archivo:** `01_Visual_Identity.md`

**Objetivo:** diseñar la identidad de tu proyecto antes de programar.

Antigravity realizará una entrevista creativa para conocer tus preferencias.

Podrás elegir:

- Temática y nombre.
- Colores.
- Tipografías.
- Estilo visual.
- Componentes.
- Imágenes.
- Fondos.
- Animaciones.
- Secciones y funcionalidades futuras.

### Instrucción para Antigravity

> Lee y ejecuta completamente el archivo `01_Visual_Identity.md`.
>
> Sigue la entrevista creativa y ayúdame a definir una identidad visual original.
>
> Permíteme seleccionar mis propias preferencias y no comiences a programar todavía.
>
> Cuando apruebe el diseño, genera `DESIGN_SYSTEM.md`.
>
> No avances automáticamente a la siguiente etapa.

### Resultado esperado

Un archivo:

`DESIGN_SYSTEM.md`

Este documento describe la identidad visual aprobada y se utilizará como referencia en las siguientes etapas.

**No continúes al Prompt 02 hasta aprobar tu diseño.**

---

## 7. Paso 02 — Desarrollo de la página web

**Archivo:** `02_Web_Creator.md`

**Objetivo:** construir la página utilizando HTML5, CSS3 y JavaScript.

Antigravity deberá leer `DESIGN_SYSTEM.md` y respetar las decisiones visuales previamente aprobadas.

La página podrá incluir:

- Encabezado y navegación.
- Hero.
- Secciones informativas.
- Tarjetas interactivas.
- Galería.
- Animaciones.
- Formulario visual de contacto.
- Footer.
- Diseño responsive.

También se generarán imágenes mediante IA cuando las herramientas disponibles lo permitan.

### Instrucción para Antigravity

> Lee y ejecuta `02_Web_Creator.md`.
>
> Utiliza `DESIGN_SYSTEM.md` como referencia obligatoria.
>
> Genera los recursos visuales necesarios y construye mi página utilizando HTML, CSS y JavaScript.
>
> Conserva la identidad visual aprobada y prepara los elementos que posteriormente podrán administrarse desde Laravel.
>
> Realiza las comprobaciones esenciales y documenta el resultado.
>
> No avances todavía a la etapa Full Stack.

### Resultados esperados

Una página web funcional y archivos como:

```text
index.html
css/styles.css
js/main.js
assets/images/
DESIGN_SYSTEM.md
CONTENT_MAP.md
README.md
```

La ubicación exacta puede adaptarse a la estructura del proyecto.

### Importante

Durante esta etapa no existe todavía una conexión con MySQL.

Los formularios que requieren un servidor no deben mostrar mensajes falsos de éxito.

La integración real se realizará en el Prompt 03.

---

## 8. Paso 03 — Aplicación Full Stack

**Archivo:** `03_Full_Stack_Builder.md`

**Objetivo:** transformar la página en una aplicación Laravel administrable.

Esta etapa utiliza [Dkript Core](https://github.com/dkript-web/dkript-core), una base tecnológica para aplicaciones Laravel.

El prompt comprobará si existe una aplicación escolar compatible y, cuando sea necesario, preparará una copia independiente desde el repositorio oficial.

### ¿Qué implementará?

**Base tecnológica**

- Laravel.
- MySQL/MariaDB.
- Dkript Core.
- Autenticación.
- Roles y permisos.
- Modelos, controladores y migraciones.

**Diseño**

- Página pública original.
- Login personalizado.
- Dashboard adaptado a los colores y estilo del proyecto.
- Formularios y tablas visualmente coherentes.
- Componentes responsive.

**Funcionalidades**

- Módulo relacionado con la temática.
- Operaciones CRUD.
- CMS ligero.
- Administración de textos, imágenes, tarjetas y secciones.
- Formulario público de contacto.
- Almacenamiento de mensajes en MySQL.
- Configuración y uso del correo electrónico cuando esté disponible.

### Instrucción para Antigravity

> Lee completamente el archivo `03_Full_Stack_Builder.md` y ejecuta sus instrucciones.
>
> Analiza la página terminada, `DESIGN_SYSTEM.md` y `CONTENT_MAP.md`.
>
> Detecta si existe una aplicación escolar basada en Dkript Core. Si no existe, prepara una copia independiente desde el repositorio oficial siguiendo la versión estable indicada y verificando su compatibilidad.
>
> Integra Laravel y MySQL, conserva la página original, personaliza visualmente el login y dashboard, e implementa el módulo temático, el CMS y el formulario de contacto.
>
> Reutiliza las funcionalidades existentes de Dkript Core antes de crear nuevas.
>
> Ejecuta las pruebas de aceptación y entrega un resumen final.
>
> No modifiques otros proyectos ni realices commits o despliegues sin autorización.

### Resultados esperados

Una aplicación que permita:

1. Acceder a la página pública.
2. Iniciar sesión como administrador.
3. Utilizar un dashboard personalizado.
4. Administrar información del proyecto.
5. Editar contenido de la página pública.
6. Guardar los cambios en MySQL.
7. Recibir y consultar mensajes de contacto.
8. Utilizar notificaciones por correo si el servicio está configurado y verificado.

### Importante sobre el correo electrónico

La recepción y almacenamiento de mensajes debe funcionar aunque SMTP no esté configurado.

El envío real de correos requiere un servidor o proveedor compatible, credenciales válidas y pruebas autorizadas.

No se debe afirmar que un correo fue entregado si no existe evidencia suficiente.

---

## 9. Flujo completo de trabajo

```text
Preparar la computadora
         │
         ▼
00 — Dev Setup
         │
         ▼
01 — Visual Identity
         │
         ▼
Aprobar DESIGN_SYSTEM.md
         │
         ▼
02 — Web Creator
         │
         ▼
Revisar página HTML/CSS/JS
         │
         ▼
03 — Full Stack Builder
         │
         ▼
Dkript Core + Laravel + MySQL
         │
         ▼
Dashboard personalizado + CMS
         │
         ▼
Pruebas y presentación final
```

**Los prompts deben ejecutarse en secuencia, respetando las aprobaciones correspondientes.**

---

## 10. Evidencias de aprendizaje

Cada estudiante deberá demostrar que comprende el proyecto que desarrolló.

| Etapa | Evidencia principal |
|---|---|
| Preparación | Entorno configurado, cuando corresponda |
| Identidad | `DESIGN_SYSTEM.md` aprobado |
| Frontend | Página funcional y `CONTENT_MAP.md` |
| Full Stack | Aplicación Laravel/MySQL |
| Administración | Edición real de contenido desde el CMS |
| Evaluación | Demostración y explicación del proyecto |

### Prueba final obligatoria

El estudiante deberá:

1. Abrir su página principal.
2. Iniciar sesión como administrador.
3. Acceder al dashboard.
4. Modificar el título principal desde el CMS.
5. Guardar el cambio.
6. Volver a la página pública.
7. Comprobar que aparece el título actualizado.
8. Recargar la página y verificar que el cambio permanece.

La funcionalidad debe operar mediante Laravel y MySQL, no mediante datos simulados.

---

## 11. Problemas frecuentes

### Antigravity no encuentra el archivo `.md`

Comprueba que abriste la carpeta correcta y que el nombre del archivo coincide exactamente con el indicado.

### PHP no se reconoce

Puede estar instalado, pero no configurado en PATH. Solicita a Antigravity que localice la instalación existente antes de instalar otra versión.

### npm está bloqueado en PowerShell

En Windows, cuando el bloqueo afecta a `npm.ps1`, normalmente puedes utilizar `npm.cmd`.

### MySQL no inicia

Comprueba si otro servicio utiliza el puerto 3306. No detengas servicios ajenos para liberar el puerto.

### La página no muestra imágenes

Comprueba las rutas y verifica si los archivos fueron generados realmente o quedaron pendientes.

### Laravel no puede conectar con MySQL

Revisa la configuración local de `.env`, el host, puerto, usuario y nombre de la base de datos.

No publiques contraseñas para solicitar ayuda.

### El correo no se envía

Comprueba la configuración SMTP y utiliza el mecanismo de prueba disponible.

Los mensajes almacenados en MySQL deben permanecer accesibles desde el administrador.

---

## 12. Seguridad y buenas prácticas

Durante las prácticas:

- No compartas contraseñas, claves API ni tokens.
- No subas archivos `.env` con credenciales reales a GitHub.
- No publiques bases de datos que contengan información personal.
- No modifiques repositorios empresariales.
- No ejecutes operaciones destructivas sin comprenderlas.
- No utilices datos personales reales para las pruebas escolares.
- No instales Skills de fuentes desconocidas.
- No aceptes cambios globales en el sistema sin revisarlos.
- No realices despliegues públicos sin autorización.
- Conserva el código fuente y los archivos de documentación de tu proyecto.

La inteligencia artificial puede cometer errores. Revisa los resultados antes de utilizarlos.

---

## 13. Recomendaciones para docentes

Este material puede utilizarse en:

- Tutorías individuales.
- Prácticas universitarias.
- Talleres de programación.
- Cursos de desarrollo web.
- Actividades de inteligencia artificial generativa.
- Proyectos integradores.

Se recomienda:

1. Preparar los equipos antes de comenzar las prácticas.
2. Demostrar cada etapa con un proyecto de ejemplo.
3. Permitir que los estudiantes elijan temáticas diferentes.
4. Evaluar tanto el resultado como la comprensión técnica.
5. No exigir funciones empresariales avanzadas en proyectos introductorios.
6. Solicitar evidencias de funcionamiento real.
7. Promover explicaciones, modificaciones manuales y resolución de problemas.

La metodología puede ajustarse a diferentes calendarios y niveles de experiencia.

---

## Autoría, atribución y licencias

### Autoría de la metodología educativa

- **Autor:** Joel Jonathan Pérez Delgado
- **Marca de origen:** Dkript
- **Licencia:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
- **Términos legales completos:** Consulta el archivo [LICENSE](LICENSE)
- **Aviso de atribución y alcance:** Consulta el archivo [NOTICE.md](NOTICE.md)
- **Copyright:** Copyright © 2026 Joel Jonathan Pérez Delgado

### Base tecnológica independiente: Dkript Core

- **Proyecto:** Dkript Core
- **Desarrollador:** Joel Jonathan Pérez Delgado — Dkript Inc.
- **Repositorio oficial:** [https://github.com/dkript-web/dkript-core](https://github.com/dkript-web/dkript-core)
- **Licencia de software:** [MIT](https://github.com/dkript-web/dkript-core/blob/main/LICENSE)
- **Copyright de software:** Copyright (c) 2026 Dkript Inc.

Dkript Core es una base de software independiente regida exclusivamente por su propia licencia MIT. La licencia CC BY 4.0 de este material educativo **no sustituye ni modifica** la licencia MIT de Dkript Core.

### Proyectos estudiantiles y aportaciones originales

Cada estudiante conserva la autoría y titularidad sobre sus aportaciones creativas y técnicas originales (código, diseño, módulos, contenido e imágenes). La licencia CC BY 4.0 de la metodología no se transfiere automáticamente al código ni a los recursos creados por los estudiantes.

### Exclusión de marcas y recursos de terceros

- **Marcas y signos distintivos:** Los nombres, logotipos e identidad corporativa de Dkript y Dkript Inc. no están licenciados bajo CC BY 4.0 y quedan expresamente reservados. No se deben incorporar marcas de agua ni logotipos de Dkript de forma automática en las páginas de los estudiantes.
- **Recursos de terceros:** Paquetes, bibliotecas, tipografías e imágenes de terceros conservan sus respectivas licencias originales.

### Cómo reutilizar este material respetando la licencia CC BY 4.0

Usted es libre de compartir (copiar y redistribuir) y adaptar (remezclar, transformar y crear a partir de) este material educativo para cualquier propósito, incluso comercial, bajo las siguientes condiciones:

1. **Atribución obligatoria:** Debe otorgar crédito explícito a **Joel Jonathan Pérez Delgado (Dkript)**, proporcionar un enlace a la licencia CC BY 4.0 y a los archivos [LICENSE](LICENSE) y [NOTICE.md](NOTICE.md).
2. **Indicar modificaciones:** Si modifica, traduce o adapta los textos, prompts o guías, debe señalar con claridad que se realizaron cambios respecto al original.
3. **Sin patrocinio ni respaldo:** No debe sugerir, directa ni indirectamente, que el autor o Dkript avalan, patrocinan o respaldan su proyecto o adaptación.
4. **Sin restricciones adicionales:** No puede imponer medidas tecnológicas ni términos legales que impidan a otros ejercer los derechos permitidos por CC BY 4.0.

---

## 14. Sobre Dkript Core

[Dkript Core — Repositorio oficial](https://github.com/dkript-web/dkript-core)

Dkript Core es una base tecnológica reutilizable desarrollada por Dkript para aplicaciones Laravel.

El proyecto dispone de licencia MIT y su repositorio contiene documentación técnica e instrucciones de instalación.

Las aplicaciones escolares deberán funcionar como proyectos independientes.

No deben modificar los repositorios o bases de datos utilizados por otros desarrollos.

La licencia de Dkript Core es independiente de la licencia que se asigne a este repositorio educativo.

---

## 15. Mantenimiento del material

La metodología utiliza cuatro prompts versionados.

Cuando se realicen cambios importantes:

- Actualiza el número de versión correspondiente.
- Documenta qué se modificó.
- Mantén coherencia entre los cuatro prompts.
- Evita instrucciones contradictorias.
- Verifica que los nombres de archivos coincidan con el README.
- Conserva versiones anteriores cuando sea necesario para reproducir prácticas.

Las herramientas externas, versiones de Laravel y características de Antigravity pueden cambiar con el tiempo.

Por ello, los agentes deben verificar la compatibilidad real antes de instalar o modificar componentes.

---

## Autor y créditos

**Joel Jonathan Pérez Delgado**  
Ingeniero en Computación · Desarrollador de Software · Docente

**Dkript — Diseñamos el futuro de las experiencias digitales.**

Sitios de referencia:

- [Dkript](https://dkript.com)
- [Inteligencia Digital](https://inteligenciadigital.mx)
- [Dkript Core en GitHub](https://github.com/dkript-web/dkript-core)

---

**Objetivo educativo:** aprender a diseñar, construir y comprender aplicaciones web reales, utilizando la inteligencia artificial como apoyo creativo y técnico.