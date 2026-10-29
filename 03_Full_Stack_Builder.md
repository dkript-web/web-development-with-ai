# PROMPT 03 — TRANSFORMA TU WEB EN UNA APLICACIÓN FULL STACK CON DKRIPT CORE
Versión 3.0 — Instalación, Laravel, CMS, panel personalizado y contacto

> **Metodología educativa:** Desarrollo Web con Inteligencia Artificial  
> **Autor:** Joel Jonathan Pérez Delgado — Dkript  
> **Licencia del material educativo:** Creative Commons Attribution 4.0 International (CC BY 4.0)  
> *Consulta [LICENSE](LICENSE) y [NOTICE.md](NOTICE.md) para las condiciones completas.*

---

## ROL

Actúa como arquitecto Full Stack senior, desarrollador Laravel, especialista en Dkript Core, MySQL/MariaDB, diseño UI/UX, integración de correo y tutor académico.

Soy estudiante y ya desarrollé una página web original con HTML, CSS, JavaScript, imágenes y animaciones.

Quiero transformarla en una aplicación Full Stack utilizando Dkript Core como base tecnológica.

El resultado debe conservar mi identidad visual y ofrecer funcionalidades reales desde la base de datos.

### OBJETIVOS OBLIGATORIOS

1. Instalar o reutilizar Dkript Core correctamente.
2. Conservar la página pública original.
3. Personalizar visualmente el login y todo el panel administrativo.
4. Implementar una funcionalidad principal relacionada con mi temática.
5. Crear un CMS ligero para administrar la página pública.
6. Implementar el formulario de contacto con almacenamiento real y configuración desde el dashboard.
7. Aprovechar el sistema de correo existente de Dkript Core cuando se confirme su funcionamiento.
8. Mantener el proyecto sencillo y comprensible para una práctica escolar.

No construyas funcionalidades empresariales adicionales que no sean necesarias.

---

# FASE 1 — REVISAR EL PROYECTO Y PREPARAR EL ENTORNO

## 1.1 Analizar la página existente

Localiza y lee:

- `DESIGN_SYSTEM.md`.
- `CONTENT_MAP.md`, si existe.
- `README.md`.
- HTML.
- CSS.
- JavaScript.
- Imágenes y recursos.

Identifica:

- Temática.
- Identidad visual.
- Secciones.
- Formularios.
- Componentes reutilizables.
- Contenidos administrables.
- Funcionalidad temática principal.

No repitas la entrevista creativa.

## 1.2 Comprobar el entorno

Verifica:

- PHP compatible.
- Composer.
- Git.
- Node.js y npm.
- MySQL o MariaDB.
- Extensiones PHP.
- Servicios existentes de XAMPP, WAMP, MAMP, Laragon o equivalentes.

Reutiliza las configuraciones del Prompt 00.

No instales servicios duplicados ni cambies puertos de otros proyectos.

Si falta un componente indispensable, informa qué hace falta y prepara su instalación de forma segura y autorizada.

## 1.3 Detectar Dkript Core

Determina si existe:

A. Una aplicación escolar derivada de Dkript Core ya instalada.

B. Una copia local limpia y autorizada.

C. El repositorio original de otro proyecto.

D. Ninguna instalación disponible.

Si ya existe una aplicación escolar derivada compatible, reutilízala.

No reinstales ni sobrescribas un proyecto que ya esté funcionando.

Si solo existe un repositorio original o una copia utilizada por otra aplicación, no lo modifiques.

---

# FASE 2 — INSTALACIÓN AUTOMÁTICA DE DKRIPT CORE

## 2.1 Repositorio oficial

Utiliza:

https://github.com/dkript-web/dkript-core.git

Referencia estable inicial:

`v1.0.0`

Verifica que la referencia exista y revisa la documentación del repositorio antes de instalar.

Si hay una versión estable más reciente, informa sus diferencias relevantes y determina cuál es más apropiada para la práctica.

No utilices automáticamente ramas experimentales.

## 2.2 Crear la aplicación escolar

Si no existe una aplicación adecuada:

1. Identifica una carpeta de destino nueva y vacía.
2. Conserva intacto el proyecto frontend original.
3. Clona Dkript Core.
4. Prepara una aplicación derivada independiente.
5. Conserva la licencia y atribuciones correspondientes.

Comando de referencia:

```bash
git clone --branch v1.0.0 --single-branch https://github.com/dkript-web/dkript-core.git mi-proyecto-laravel
```

Adapta el nombre de la carpeta.

El proyecto derivado debe ser independiente del repositorio oficial.

Desvincula el historial Git heredado únicamente dentro de la nueva copia derivada, después de verificar su ruta.

No elimines directorios `.git` ajenos.

No hagas commits ni push sin autorización.

## 2.3 Dependencias

Dentro del proyecto nuevo, ejecuta cuando corresponda:

```bash
composer install
npm ci
```

En Windows puedes utilizar `npm.cmd ci` si PowerShell bloquea el script de npm.

Comprueba compatibilidad antes de modificar dependencias.

No ejecutes actualizaciones indiscriminadas.

## 2.4 Base de datos

Utiliza MySQL o MariaDB existente.

Crea una base de datos exclusiva para el proyecto, después de comprobar que el nombre no pertenece a otra aplicación.

Configura `.env` con:

- `APP_NAME`.
- `APP_ENV=local`.
- `APP_URL`.
- Conexión de base de datos.
- Host y puerto.
- Nombre de la base.
- Usuario y credenciales locales.

No utilices bases de datos corporativas ni de otros estudiantes.

No publiques contraseñas.

## 2.5 Instalador oficial

Utiliza:

```bash
php artisan dkript:install
```

Antes de ejecutarlo, verifica que la conexión activa apunta a la base escolar nueva y vacía.

Utiliza preferentemente el instalador interactivo.

Permite que el estudiante introduzca sus credenciales administrativas directamente mediante un mecanismo seguro.

No registres secretos en informes.

No utilices `--force` sobre instalaciones existentes.

No dupliques usuarios, permisos ni tablas del Core.

## 2.6 Comprobación inicial

Ejecuta las verificaciones pertinentes:

```bash
npm run build
php artisan route:list
```

Comprueba que Laravel y la autenticación funcionen.

No ejecutes todavía pruebas o modificaciones ajenas al proyecto escolar.

---

# FASE 3 — INTEGRACIÓN DEL FRONTEND CON LARAVEL

Convierte la página HTML/CSS/JavaScript a vistas Blade.

Conserva:

- Estructura.
- Paleta.
- Tipografías.
- Fondos.
- Imágenes.
- Componentes.
- Galerías.
- Animaciones.
- Navegación.
- Diseño responsive.

No sustituyas la página original por una plantilla genérica de Laravel.

Utiliza layouts y componentes Blade reutilizables cuando aporten claridad.

Mantén los estilos CSS y scripts JavaScript organizados.

Adapta enlaces y formularios a rutas Laravel reales.

Conserva los contenidos originales para utilizarlos como datos iniciales.

---

# FASE 4 — PERSONALIZACIÓN VISUAL COMPLETA DE DKRIPT CORE

## REQUISITO OBLIGATORIO

**La página pública, el login y el dashboard deben compartir la identidad visual aprobada del proyecto.**

No es suficiente cambiar únicamente el logotipo o el color primario.

## 4.1 Analizar el diseño

Lee `DESIGN_SYSTEM.md`.

Identifica:

- Colores.
- Tipografías.
- Fondos.
- Superficies.
- Bordes.
- Sombras.
- Gradientes.
- Iconografía.
- Estilo claro u oscuro.
- Estados visuales.
- Personalidad gráfica.

Utiliza estas decisiones como sistema de diseño compartido.

## 4.2 Revisar Dkript Core

Inspecciona sus mecanismos existentes de:

- Branding.
- Configuración de parámetros.
- Temas, si existen.
- Layouts Blade.
- Componentes.
- Archivos CSS.
- Navegación administrativa.

Utiliza primero los mecanismos oficiales de personalización.

No supongas que existe un motor de temas completo si el código no lo confirma.

Evita modificar componentes troncales innecesariamente.

## 4.3 Personalizar el login

Adapta:

- Fondo.
- Logotipo.
- Tipografía.
- Formularios.
- Botones.
- Enlaces.
- Mensajes de error.
- Estados visuales.

La identidad debe corresponder al proyecto del estudiante, no al branding corporativo de Dkript.

## 4.4 Personalizar el dashboard

Adapta:

- Menú lateral.
- Barra superior.
- Encabezados.
- Tarjetas.
- Indicadores reales.
- Botones.
- Tablas.
- Formularios.
- Modales.
- Alertas.
- Paginación.
- Pantallas de administración.

Conserva la navegación, permisos y funcionalidades originales.

No inventes estadísticas.

## 4.5 Estilos reutilizables

Implementa un mecanismo centralizado de estilos o variables para que todos los módulos administrativos utilicen automáticamente la identidad elegida.

Evita CSS duplicado y modificaciones individuales en cada pantalla.

Los módulos nuevos deben heredar los estilos compartidos siempre que sea técnicamente posible.

No permitas que los estilos públicos rompan el panel ni viceversa.

## 4.6 Calidad visual

El panel debe ser:

- Responsive.
- Legible.
- Accesible.
- Coherente.
- Intuitivo.
- Funcional.

No es necesario copiar todas las animaciones de la página pública.

Prioriza la experiencia administrativa.

Comprueba que formularios, botones, tablas y navegación sigan funcionando después de personalizarlos.

---

# FASE 5 — MÓDULO TEMÁTICO Y BASE DE DATOS

Identifica una funcionalidad principal relacionada con la temática del estudiante.

Ejemplos:

- Videojuegos: administración de juegos y puntuaciones.
- Música: artistas y canciones.
- Negocios: productos y solicitudes.
- Eventos: eventos e inscripciones.
- Portafolio: proyectos y mensajes.
- Naturaleza: especies y observaciones.

Crea las entidades, relaciones y formularios necesarios.

Utiliza:

- Migraciones.
- Modelos Eloquent.
- Controladores.
- Form Requests.
- Validación.
- Rutas.
- Blade.
- MySQL.

## Generador de Dkript Core

Cuando sea apropiado, utiliza:

```bash
php artisan dkript:make-module NombreModulo --dry-run
```

Define los campos reales antes de generar el módulo.

Verifica previamente que la conexión activa apunta a la base escolar.

Recuerda que el generador puede registrar permisos y menús en MySQL.

Después de verificar la simulación, genera el módulo y aplica sus migraciones.

No utilices `--force` para sobrescribir archivos existentes sin autorización.

Los formularios y vistas nuevas deben heredar automáticamente el tema visual personalizado.

No reconstruyas la autenticación, los usuarios o el sistema de permisos que Dkript Core ya proporciona.

---

# FASE 6 — CMS LIGERO ADMINISTRABLE

## Objetivo

El propietario debe poder cambiar el contenido de la página principal desde el dashboard, sin editar archivos de código.

## 6.1 Contenido editable

Permite administrar los elementos existentes:

### Hero

- Título.
- Subtítulo.
- Descripción.
- Imagen.
- Botón.
- Enlace.

### Secciones

- Títulos.
- Descripciones.
- Imágenes.
- Orden.
- Visibilidad.

### Tarjetas

- Crear.
- Editar.
- Eliminar con confirmación.
- Reordenar cuando corresponda.
- Activar y desactivar.

### Galerías

- Agregar y reemplazar imágenes.
- Editar títulos y descripciones.
- Eliminar elementos.
- Reordenar cuando corresponda.

### Configuración general

- Nombre del sitio.
- Logotipo.
- Información pública de contacto.
- Redes sociales.
- Enlaces autorizados.

No implementes todas las opciones si el proyecto no contiene esos componentes.

## 6.2 Base de datos

Inspecciona primero las tablas existentes de Dkript Core.

Evalúa entidades como:

- `site_settings`.
- `pages`.
- `page_sections`.
- `media_assets`.

Utiliza solamente las que sean necesarias.

Evita duplicar la tabla `parameters` u otras estructuras existentes.

No almacenes toda la página como HTML arbitrario editable.

## 6.3 Conexión real

El contenido administrable debe persistirse en MySQL.

La página pública debe obtenerlo mediante Laravel y Blade.

Conserva las imágenes, textos y tarjetas originales como datos iniciales.

Los seeders no deben sobrescribir los cambios posteriores del administrador.

## 6.4 Seguridad

- Rutas protegidas.
- Permisos.
- Protección CSRF.
- Validación en servidor.
- Archivos multimedia validados.
- Contenido publicado y borradores, solo si se implementan realmente.
- Sin ejecución de HTML o JavaScript arbitrario desde el administrador.

---

# FASE 7 — CONTACTO Y CONFIGURACIÓN DE CORREO

## OBJETIVO OBLIGATORIO

La página pública debe tener un mecanismo de contacto funcional.

El administrador debe poder consultar los mensajes y configurar las opciones disponibles desde el dashboard.

## 7.1 Revisar el correo existente de Dkript Core

Antes de desarrollar un nuevo servicio, inspecciona:

- `MailConfigService`.
- Configuración de correo en `parameters`.
- Formularios de configuración del dashboard.
- Controladores y rutas de correo.
- Configuración de Laravel Mail.
- Clases Mailable disponibles.
- Pruebas existentes.
- Manejo de errores.
- Protección de credenciales.

Determina:

1. Si el dashboard guarda correctamente la configuración SMTP.
2. Si Laravel utiliza esa configuración para enviar.
3. Si existe una función de correo de prueba.
4. Si las credenciales se protegen correctamente.
5. Si puede utilizarse el servicio desde un formulario público.
6. Qué limitaciones requieren corrección.

No confundas existencia de código con funcionamiento verificado.

No sustituyas automáticamente el sistema de correo existente.

## 7.2 Formulario público

Implementa un formulario con:

- Nombre.
- Correo electrónico.
- Asunto.
- Mensaje.

Respeta el diseño definido en `DESIGN_SYSTEM.md`.

Utiliza rutas Laravel, validación en servidor y protección CSRF.

El formulario debe funcionar realmente y no limitarse a mostrar una animación de éxito.

## 7.3 Almacenamiento de mensajes

Crea o reutiliza una entidad adecuada para almacenar los mensajes recibidos.

Registra:

- Nombre.
- Correo.
- Asunto.
- Mensaje.
- Fecha.
- Estado de notificación o envío, si corresponde.

No almacenes datos personales adicionales sin necesidad.

El administrador debe poder consultar los mensajes desde su panel protegido.

Evita duplicar información o crear sistemas de mensajería excesivamente complejos.

## 7.4 Configuración desde el dashboard

Reutiliza la configuración de correo de Dkript Core cuando esté funcional.

El administrador debería poder gestionar, según las capacidades disponibles:

- Servidor SMTP.
- Puerto.
- Cifrado.
- Usuario SMTP.
- Credencial SMTP.
- Nombre del remitente.
- Dirección del remitente.
- Destinatario o destinatarios del formulario.
- Activación o desactivación del formulario.
- Envío de prueba.
- Estado de la última prueba, cuando corresponda.

Distingue la configuración del servidor SMTP de la configuración funcional del formulario de contacto.

Si alguna opción requiere ampliar Dkript Core, implementa la ampliación exclusivamente en la aplicación escolar derivada y de manera compatible con su arquitectura.

No expongas credenciales.

## 7.5 Flujo de envío

Cuando un visitante envíe el formulario:

1. Laravel recibe la solicitud.
2. Valida los campos.
3. Aplica protección contra solicitudes abusivas.
4. Guarda el mensaje en MySQL.
5. Comprueba si las notificaciones por correo están habilitadas.
6. Utiliza el servicio de correo configurado.
7. Registra el resultado del intento.
8. Muestra una respuesta correcta al visitante.

Usa el remitente SMTP autorizado y configura `Reply-To` con el correo validado del visitante cuando corresponda.

No utilices arbitrariamente el correo del visitante como dirección `From`.

## 7.6 Comportamiento si SMTP no funciona

Si falta configuración SMTP, no existen credenciales válidas o la auditoría detecta problemas:

- Conserva el formulario funcional.
- Guarda los mensajes en MySQL.
- Permite consultarlos desde el panel.
- Registra que la notificación por email está pendiente, deshabilitada o falló.
- No afirmes que se envió un correo que no fue entregado al transportador configurado.
- Informa claramente qué configuración falta para habilitar las notificaciones.

No bloquees todo el desarrollo por una configuración externa pendiente.

No afirmes que el correo llegó a la bandeja de entrada si solo se comprobó que el servidor SMTP aceptó el envío.

## 7.7 Protección contra spam

Implementa medidas sencillas y pertinentes:

- Validación de campos.
- Límites de longitud.
- Rate limiting.
- CSRF.
- Protección contra inyección de encabezados.
- Honeypot u otra protección ligera, cuando corresponda.

No instales CAPTCHA complejo por defecto.

## 7.8 Pruebas del correo

Utiliza simulación de correo o transporte local seguro para las pruebas automatizadas.

No envíes mensajes reales sin autorización.

Si existe un botón de correo de prueba en el dashboard, la acción debe ser explícita del administrador.

Verifica que los errores se gestionen correctamente y que los mensajes permanezcan disponibles en la base de datos.

---

# FASE 8 — PRUEBAS DE ACEPTACIÓN

Realiza una ronda de pruebas pertinentes.

No ejecutes auditorías repetitivas innecesarias.

## A. Entorno

Comprueba:

- Laravel inicia.
- Dkript Core funciona.
- MySQL está conectado.
- El administrador puede iniciar y cerrar sesión.
- Los permisos impiden accesos no autorizados.

## B. Identidad visual

Comprueba:

1. El frontend conserva el diseño aprobado.
2. El login utiliza la temática.
3. El dashboard comparte la identidad.
4. El menú lateral y la barra superior están personalizados.
5. Los formularios y tablas mantienen consistencia.
6. Los módulos nuevos heredan el diseño.
7. El panel es responsive.
8. Las funciones originales del Core siguen operando.

## C. Módulo temático

Comprueba que se puedan crear, consultar y modificar registros reales, y eliminarlos cuando corresponda.

## D. CMS — Prueba principal

1. Abre la página pública.
2. Identifica el título principal.
3. Inicia sesión como administrador.
4. Accede al dashboard.
5. Modifica el título.
6. Guarda.
7. Vuelve a la página pública.
8. Comprueba que el cambio aparece.
9. Recarga y verifica que persiste.
10. Restaura el contenido original desde el panel.

Si esta prueba falla, el CMS todavía no está terminado.

## E. Contacto

1. Abre el formulario público.
2. Introduce datos de prueba.
3. Envía el formulario.
4. Comprueba las validaciones.
5. Verifica que el mensaje se guarda en MySQL.
6. Accede al dashboard.
7. Comprueba que el administrador puede consultarlo.
8. Verifica el estado de la notificación por correo.
9. Comprueba que se rechazan solicitudes inválidas.
10. Verifica que el formulario no permite acceder a información administrativa.

Si SMTP está configurado y existe autorización, realiza una prueba controlada de entrega.

Si no existe SMTP, documenta claramente la limitación sin considerar fallido el almacenamiento de mensajes.

## F. Pruebas del Core

No repitas toda la suite de Dkript Core cuando no se hayan modificado sus componentes centrales.

Ejecuta las pruebas específicas del proyecto y las comprobaciones de integración necesarias.

---

# FASE 9 — DOCUMENTACIÓN ACADÉMICA

Actualiza `README.md`.

Incluye:

- Nombre y temática.
- Versión de Dkript Core y referencia Git utilizada.
- Tecnologías.
- Estructura del proyecto.
- Base de datos.
- Modelos y relaciones.
- Rutas.
- Controladores.
- Vistas Blade.
- Funcionalidad temática.
- CMS.
- Configuración del administrador.
- Personalización visual del panel.
- Sistema de contacto.
- Configuración de correo.
- Comandos para ejecutar el proyecto.
- Pruebas efectuadas y pendientes.

No incluyas contraseñas ni credenciales.

Explica de manera comprensible:

1. Qué es Dkript Core.
2. Qué es Laravel.
3. Cómo funciona MVC.
4. Qué hace un modelo Eloquent.
5. Qué es una migración.
6. Cómo Blade muestra información de MySQL.
7. Cómo funciona el CMS.
8. Cómo se relacionan el formulario público, el controlador, MySQL y el servicio de correo.

---

# AUTORÍA, LICENCIA Y CRÉDITOS DE DKRIPT CORE

Dkript Core es desarrollado por **Joel Jonathan Pérez Delgado** bajo **Dkript Inc.**

Repositorio oficial: https://github.com/dkript-web/dkript-core

Dkript Core se distribuye con **licencia MIT**. Copyright (c) 2026 Dkript Inc.

La aplicación escolar podrá utilizar su propia identidad visual y los componentes autorizados de Dkript Core, siempre respetando las siguientes reglas:

1. **Reconocimiento del desarrollador.** Dkript Core fue desarrollado por Joel Jonathan Pérez Delgado bajo Dkript Inc. Este reconocimiento debe conservarse.
2. **Repositorio oficial.** El repositorio de referencia es https://github.com/dkript-web/dkript-core
3. **Licencia MIT y copyright.** La licencia MIT y los avisos de copyright de Dkript Core deben conservarse en la aplicación derivada sin modificación ni eliminación.
4. **Originalidad del código base.** El estudiante no debe presentar Dkript Core como un desarrollo propio. El código base proviene del repositorio oficial indicado.
5. **Reconocimiento de las contribuciones del estudiante.** El código, diseño, módulos y funcionalidades desarrollados por el estudiante son contribuciones originales de su autoría.
6. **Integridad de los créditos del repositorio original.** No deben modificarse ni eliminarse los créditos del repositorio oficial de Dkript Core.
7. **Sección de créditos en el README.** El README de cada aplicación derivada debe incluir una sección de créditos que identifique la procedencia de Dkript Core y distinga las contribuciones originales del estudiante. Ver la instrucción de generación automática al final de esta sección.
8. **Identidad visual del proyecto escolar.** No se impondrá la identidad visual corporativa de Dkript Inc. al proyecto escolar. El estudiante puede definir su propio branding.
9. **Licencias de terceros.** Las condiciones de licencia de paquetes, bibliotecas e imágenes de terceros utilizados en la aplicación deben respetarse.
10. **Ámbito de las licencias y no contagio.** El software Dkript Core está sujeto a su propia licencia MIT. La metodología educativa y sus prompts están bajo licencia Creative Commons Attribution 4.0 International (CC BY 4.0) (ver [LICENSE](LICENSE) y [NOTICE.md](NOTICE.md)). La aplicación escolar desarrollada por el estudiante no adquiere automáticamente la licencia CC BY 4.0 por el hecho de utilizar los materiales formativos; el estudiante conserva la autoría sobre sus aportaciones originales, Dkript Core mantiene su licencia MIT, y los recursos de terceros mantienen sus respectivas licencias.

## Generación automática de la sección de créditos en el README

Al actualizar el `README.md` de la aplicación escolar en la Fase 9, genera automáticamente una sección titulada `## Créditos` con el siguiente formato:

```markdown
## Créditos

### Base tecnológica

Este proyecto utiliza [Dkript Core](https://github.com/dkript-web/dkript-core),
desarrollado por **Joel Jonathan Pérez Delgado** bajo **Dkript Inc.**
Distribuido con [licencia MIT](https://github.com/dkript-web/dkript-core/blob/main/LICENSE).

### Contribuciones del estudiante

El diseño visual, los módulos temáticos, las vistas Blade, el CMS y el contenido
de esta aplicación fueron desarrollados por [Nombre del estudiante].

### Recursos de terceros

- [Nombre del recurso] — [licencia] — [URL o procedencia]
```

Adapta el nombre del estudiante y los recursos de terceros según el proyecto real. No dejes la plantilla sin completar.

---

# FASE 10 — CIERRE OBLIGATORIO

Al terminar:

1. Finaliza las tareas iniciadas.
2. Cierra navegadores automatizados.
3. Detén pruebas y procesos auxiliares.
4. No dejes instalaciones ni compilaciones innecesarias en ejecución.
5. Mantén únicamente el servidor local del proyecto cuando sea necesario.
6. Conserva los servicios compartidos requeridos.
7. No detengas procesos ajenos.
8. No modifiques el repositorio oficial de Dkript Core.
9. No ejecutes operaciones destructivas sobre otras bases de datos.
10. No realices commits, push ni despliegues sin autorización.
11. Informa la ubicación del proyecto.
12. Informa la versión de Core utilizada.
13. Indica la URL local.
14. Indica la ruta de login y administración.
15. Explica cómo configurar de forma segura el primer administrador.
16. Informa si el CMS funciona.
17. Informa si el formulario de contacto guarda correctamente.
18. Distingue si las notificaciones SMTP funcionan, están sin configurar o no pudieron verificarse.
19. Resume los pendientes reales.
20. Finaliza completamente la ejecución del agente.

## CRITERIOS FINALES DE ACEPTACIÓN

### 1. Identidad

La página pública, el login y el panel administrativo deben compartir la identidad visual definida en `DESIGN_SYSTEM.md`.

### 2. Funcionalidad

El módulo principal debe operar con datos reales en MySQL.

### 3. CMS

El administrador debe poder modificar contenido público desde el dashboard y comprobar los cambios sin editar código.

### 4. Contacto

El formulario debe validar y guardar mensajes reales en MySQL.

Si el correo está configurado y verificado, debe utilizar el servicio existente para enviar notificaciones.

Si no lo está, la recepción y consulta de mensajes deben seguir funcionando, indicando claramente el estado del correo.

### 5. Independencia

La aplicación escolar debe ser independiente y no modificar el repositorio ni la base de datos de otro proyecto.

## RESULTADO ESPERADO

Una aplicación escolar basada en Dkript Core con:

- Laravel.
- MySQL o MariaDB.
- Autenticación.
- Página pública original.
- Login personalizado.
- Dashboard con la temática del proyecto.
- Módulo temático funcional.
- CMS ligero.
- Administración de imágenes y contenido.
- Formulario de contacto.
- Configuración y aprovechamiento del correo cuando esté disponible.
- Diseño responsive.
- Documentación académica.

## INSTRUCCIÓN FINAL

Comienza inspeccionando el proyecto y el entorno.

Instala Dkript Core desde el repositorio oficial si es necesario.

Conserva la identidad visual, integra Laravel y MySQL, personaliza el panel completo y construye las funcionalidades temáticas y el CMS.

Revisa el servicio de correo existente antes de reutilizarlo y prepara el contacto público con almacenamiento real.

Realiza las pruebas de aceptación y finaliza cuando las funcionalidades principales estén verificadas, indicando cualquier limitación externa pendiente.