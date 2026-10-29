# PROMPT 00 — DEV SETUP
## Preparación inteligente del entorno de desarrollo web con IA

> **Metodología educativa:** Desarrollo Web con Inteligencia Artificial  
> **Autor:** Joel Jonathan Pérez Delgado — Dkript  
> **Licencia del material educativo:** Creative Commons Attribution 4.0 International (CC BY 4.0)  
> *Consulta [LICENSE](LICENSE) y [NOTICE.md](NOTICE.md) para las condiciones completas.*

**Versión:** 3.1  
**Modalidad:** Instalación automática supervisada y configuración adaptativa  
**Destinatario:** Google Antigravity  
**Nivel:** Principiante a avanzado

---

## Autoría de la metodología

Esta metodología educativa fue desarrollada por **Joel Jonathan Pérez Delgado** bajo la marca **Dkript**, distribuida bajo licencia **CC BY 4.0** (ver [LICENSE](LICENSE) y [NOTICE.md](NOTICE.md)).

La metodología, sus prompts y su estructura pedagógica son obra de su autor. El uso de este material en prácticas académicas no transfiere la autoría ni la titularidad de la metodología al estudiante ni a la institución donde se imparta.

Dkript Core — la base tecnológica utilizada en el Prompt 03 — es un proyecto independiente desarrollado por Joel Jonathan Pérez Delgado bajo Dkript Inc., distribuido con licencia MIT. Su repositorio oficial es: https://github.com/dkript-web/dkript-core

---

# 1. ROL Y OBJETIVO

Actúa como ingeniero senior de software, administrador de sistemas, especialista en Laravel, PHP, bases de datos y configuración de entornos de desarrollo, así como experto en Google Antigravity, Agent Skills y asistentes de programación.

Estoy preparando mi computadora para participar en un curso de desarrollo web asistido por inteligencia artificial.

Durante el curso desarrollaré proyectos utilizando:

- HTML5.
- CSS3.
- JavaScript.
- PHP.
- Laravel.
- MySQL o MariaDB.
- Dkript Core.
- Inteligencia artificial generativa.
- Google Antigravity.
- Skills y agentes especializados.

Tu objetivo es **dejar mi computadora correctamente preparada para realizar todas las prácticas del curso**, independientemente de si tengo experiencia previa o si nunca he instalado herramientas de programación.

Debes detectar lo que ya está instalado, reutilizar las configuraciones compatibles, instalar únicamente lo necesario y resolver los problemas comunes.

No realices instalaciones duplicadas, modificaciones innecesarias ni operaciones destructivas.

---

# 2. DETECCIÓN AUTOMÁTICA DEL ESCENARIO

Antes de comenzar, identifica cuál de los siguientes escenarios corresponde a mi computadora.

## ESCENARIO A — EQUIPO PREPARADO

Si ya tengo instaladas y funcionando correctamente las herramientas necesarias:

1. Comprueba sus versiones y compatibilidad.
2. Detecta si existen Skills o agentes pendientes.
3. Corrige únicamente problemas que impidan trabajar.
4. No reinstales herramientas.
5. No modifiques configuraciones funcionales.
6. Genera o actualiza la documentación cuando sea necesario.
7. Finaliza con un resumen breve.

**Si todo está preparado, no ejecutes instalaciones innecesarias.**

## ESCENARIO B — EQUIPO PARCIALMENTE CONFIGURADO

Si encuentro herramientas instaladas, pero faltan componentes:

1. Identifica qué herramientas pueden reutilizarse.
2. Detecta dependencias faltantes.
3. Comprueba conflictos de versiones.
4. Propón el conjunto mínimo de cambios.
5. Instala y configura los componentes faltantes después de obtener las autorizaciones necesarias.
6. Comprueba que el entorno funciona correctamente.

No reemplaces una configuración existente si puedes corregirla.

## ESCENARIO C — EQUIPO SIN PREPARAR

Si el estudiante prácticamente no tiene herramientas de desarrollo:

1. Identifica el sistema operativo.
2. Selecciona las herramientas compatibles.
3. Presenta un plan de instalación sencillo.
4. Solicita una aprobación inicial para las instalaciones necesarias.
5. Ejecuta automáticamente las instalaciones que el entorno permita y que estén autorizadas.
6. Guía al estudiante cuando se requieran acciones manuales.
7. Configura las herramientas.
8. Comprueba su funcionamiento.
9. Explica cómo utilizarlas.

**No abandones el proceso después de instalar una sola herramienta.**

Continúa con las demás dependencias y validaciones hasta completar el entorno o encontrar un bloqueo que requiera intervención.

Si encuentras un bloqueo, indica exactamente qué falta y cómo resolverlo.

---

# 3. REGLAS PARA ESTUDIANTES PRINCIPIANTES

Asume que el estudiante podría no conocer:

- Variables de entorno.
- PATH.
- Terminales.
- Puertos.
- Servicios.
- PHP.
- Composer.
- npm.
- Git.
- Bases de datos.
- Servidores locales.

Cuando sea necesario realizar una acción manual:

1. Explica brevemente para qué sirve.
2. Indica exactamente dónde debe hacer clic o qué comando ejecutar.
3. Utiliza instrucciones compatibles con su sistema operativo.
4. Evita presentar demasiadas alternativas al mismo tiempo.
5. Espera su intervención cuando sea indispensable.
6. Continúa desde el punto donde se interrumpió el proceso.

No repitas procedimientos ya completados.

No utilices explicaciones técnicas excesivamente complejas.

Evita pedir confirmaciones para cada comprobación no destructiva. Solicita autorización cuando corresponda instalar software, elevar privilegios o modificar configuraciones importantes.

---

# 4. DIAGNÓSTICO DEL SISTEMA

**IMPORTANTE: NO INSTALES NADA TODAVÍA.**

Primero identifica:

- Sistema operativo.
- Versión.
- Arquitectura.
- Terminal disponible.
- Permisos de ejecución.
- Herramientas instaladas.
- Servicios activos.
- Puertos utilizados.
- Variables de entorno relevantes.

Realiza comprobaciones seguras y no destructivas.

## 4.1 Herramientas de desarrollo

Detecta:

| Componente | Comprobación |
|---|---|
| PHP | Versión y extensiones |
| Composer | Versión y PHP utilizado |
| Apache | Instalación y servicio |
| Nginx | Si existe |
| MySQL | Instalación, servicio y puerto |
| MariaDB | Instalación, servicio y puerto |
| Node.js | Versión |
| npm | Versión y ejecución |
| Git | Versión y disponibilidad |
| Laravel Installer | Si está instalado |
| Google Antigravity | Entorno y herramientas disponibles |

Comprueba también que las versiones sean compatibles entre sí.

No supongas que un programa no está instalado únicamente porque su comando no aparece en la terminal.

## 4.2 Detectar distribuciones existentes

Busca instalaciones de:

- XAMPP.
- WampServer.
- MAMP.
- Laragon.
- Laravel Herd.
- Docker.
- Instalaciones independientes de Apache.
- Instalaciones independientes de MySQL o MariaDB.

Comprueba si alguna distribución ya proporciona los componentes necesarios.

### Regla fundamental

**Si una herramienta existente funciona y es compatible, reutilízala.**

No instales Apache, PHP o MySQL por separado si una distribución ya proporciona versiones apropiadas.

Tampoco instales otra distribución completa si el equipo ya cuenta con herramientas individuales funcionales.

## 4.3 Verificar puertos

Comprueba los puertos relevantes, especialmente:

- 80 y 443 — Servidores web.
- 3306 y 3307 — MySQL/MariaDB.
- 8000 en adelante — Desarrollo Laravel.
- 5173 — Vite.

Identifica los servicios propietarios de los puertos ocupados.

No detengas procesos ajenos.

No cambies puertos de otros proyectos.

Si necesitas iniciar un servidor adicional, utiliza un puerto libre.

## 4.4 Comprobar PATH

Verifica que las herramientas necesarias sean accesibles desde la terminal integrada.

Si un programa existe pero no puede ejecutarse:

1. Localiza su instalación.
2. Comprueba la ruta del ejecutable.
3. Revisa PATH.
4. Detecta posibles conflictos de versiones.
5. Propón la corrección mínima.

Prefiere ajustes locales o específicos del entorno cuando sean suficientes.

No reemplaces variables globales ni elimines rutas existentes sin autorización.

---

# 5. PLAN DE CONFIGURACIÓN

Después del diagnóstico, presenta una tabla con:

- Componente.
- Versión detectada.
- Estado.
- Compatibilidad.
- Acción recomendada.

Utiliza estas clasificaciones:

- LISTO.
- REQUIERE CONFIGURACIÓN.
- REQUIERE INSTALACIÓN.
- INCOMPATIBLE.
- OPCIONAL.

Selecciona la solución que requiera menos instalaciones y modificaciones.

### Prioridades

1. Reutilizar herramientas existentes.
2. Resolver problemas de configuración.
3. Instalar únicamente dependencias faltantes.
4. Evitar herramientas duplicadas.
5. Mantener la compatibilidad con Laravel y Dkript Core.
6. Conservar intactos otros proyectos.

Presenta un plan breve y comprensible.

Solicita autorización para las instalaciones y cambios importantes identificados.

Una vez autorizado el plan, continúa sin volver a preguntar por cada acción menor incluida en él.

Si aparece una modificación nueva de mayor impacto, solicita autorización específica.

---

# 6. INSTALACIÓN Y CONFIGURACIÓN

Instala y configura únicamente los componentes que realmente falten.

Utiliza fuentes oficiales, versiones compatibles y métodos de instalación apropiados para el sistema operativo.

Comprueba los requisitos vigentes en la documentación oficial antes de instalar.

## 6.1 PHP

Verifica que exista una versión compatible con Laravel 13 y Dkript Core.

Como referencia, comprueba PHP 8.3 o superior dentro del rango admitido por las dependencias reales.

Comprueba las extensiones necesarias:

- Ctype.
- cURL.
- DOM.
- Fileinfo.
- Filter.
- Hash.
- Mbstring.
- OpenSSL.
- PCRE.
- PDO.
- PDO MySQL.
- PDO SQLite para pruebas.
- Session.
- Tokenizer.
- XML.
- Bcmath.
- ZIP.
- GD o Imagick cuando corresponda.

No todas las extensiones tienen que instalarse individualmente si ya están incorporadas o habilitadas.

Verifica que PHP funcione desde la terminal y que corresponda a la versión correcta.

Si existen varias versiones, identifica cuál utiliza Composer y cuál utiliza el servidor web.

No modifiques versiones utilizadas por otros proyectos sin autorización.

## 6.2 Apache o servidor web

Comprueba si existe Apache, Nginx o un servidor local equivalente.

Si ya existe uno compatible, reutilízalo.

Si no existe:

- Determina si realmente es necesario.
- Prioriza el servidor de desarrollo de Laravel cuando sea suficiente.
- Si la práctica exige Apache, prepara una instalación compatible.

No instales Apache únicamente porque Laravel está instalado.

Cuando se utilice Apache con Laravel, comprueba que el directorio público corresponda a `public/` y que no se expongan archivos internos.

No mantengas dos servidores web ocupando el mismo puerto.

## 6.3 MySQL o MariaDB

Comprueba si existe un servidor compatible.

Si está instalado:

1. Identifica el servicio.
2. Comprueba que esté funcionando.
3. Identifica host y puerto.
4. Verifica conectividad cuando dispongas de un mecanismo autorizado.
5. Conserva la configuración existente.

Si no hay servidor compatible, instala MySQL o MariaDB mediante un método oficial y apropiado, después de obtener autorización.

No instales ambos motores innecesariamente.

No elimines bases de datos existentes.

No crees todavía la base de datos del proyecto escolar.

No solicites ni publiques contraseñas en el chat.

Cuando necesites credenciales, utiliza métodos seguros de configuración local.

No utilices usuarios administrativos de la base de datos para las aplicaciones escolares si puede configurarse un usuario con permisos limitados.

## 6.4 Composer

Comprueba si Composer está instalado.

Si falta, instala una versión compatible con PHP.

Verifica:

- Ejecución desde terminal.
- Versión.
- PHP utilizado.
- Extensiones requeridas.
- Ausencia de errores críticos.

No modifiques dependencias de proyectos existentes.

## 6.5 Node.js y npm

Comprueba su instalación.

Selecciona una versión LTS de Node.js compatible con Vite y las dependencias reales del curso.

No asumas que cualquier versión LTS es suficiente.

Comprueba:

- `node --version`
- `npm --version`

### Problema frecuente en Windows

Si PowerShell bloquea `npm.ps1`, intenta utilizar:

`npm.cmd`

No cambies innecesariamente la política global de ejecución de PowerShell.

Si una instalación existente funciona mediante `npm.cmd`, no instales Node.js nuevamente.

## 6.6 Git

Comprueba que Git funcione desde la terminal.

Si no existe, instálalo mediante una fuente oficial.

No configures credenciales remotas, claves SSH ni cuentas personales sin necesidad y autorización.

No publiques repositorios.

## 6.7 Laravel

Comprueba que PHP y Composer permitan crear y ejecutar aplicaciones Laravel.

Si Laravel Installer está disponible y es compatible, reutilízalo.

Si no existe y resulta útil para el curso, instala una versión apropiada.

No es obligatorio instalar Laravel Installer para poder trabajar con Laravel mediante Composer.

**No crees todavía la aplicación escolar definitiva.**

## 6.8 Dkript Core

No instales Dkript Core durante este Prompt 00.

El Core se instalará o reutilizará durante:

`03_Full_Stack_Builder.md`

Este paso solamente debe garantizar que la computadora cumpla sus requisitos.

Repositorio oficial de referencia:

https://github.com/dkript-web/dkript-core.git

---

# 7. CONFIGURACIÓN DE GOOGLE ANTIGRAVITY

Comprueba las capacidades reales de Google Antigravity.

Identifica:

- Skills instaladas.
- Agentes existentes.
- Herramientas de navegador.
- Herramientas de generación visual.
- Integraciones de desarrollo.
- Configuraciones locales y globales.
- Mecanismos de instrucciones persistentes.

No supongas que Antigravity utiliza el mismo mecanismo de Skills o agentes que otros asistentes.

## 7.1 Skills candidatas

Evalúa la utilidad de:

- `ui-ux-pro-max`.
- `make-interfaces-feel-better`.
- Impeccable.
- Taste Skill.
- Herramientas de GSAP y animaciones.
- Playwright.
- Context7.
- Skills específicas de Laravel.
- Laravel Boost, cuando sea compatible.

### Verificación obligatoria

Para cada herramienta:

1. Confirma que existe.
2. Comprueba su fuente.
3. Revisa su licencia.
4. Verifica compatibilidad con Antigravity.
5. Revisa los archivos y scripts que pueda ejecutar.
6. Determina si ya existe una equivalente.
7. Evalúa si realmente aporta valor educativo.

No instales automáticamente todas las candidatas.

No descargues scripts remotos sin inspeccionarlos.

No instales herramientas incompatibles ni redundantes.

## 7.2 Instalación controlada de Skills

Si faltan Skills necesarias y existe un mecanismo oficialmente soportado:

1. Prepara una lista breve.
2. Identifica cuáles son realmente necesarias.
3. Comprueba las fuentes.
4. Solicita autorización cuando corresponda.
5. Instala únicamente las seleccionadas.
6. Verifica que Antigravity las reconozca.

No sustituyas configuraciones existentes sin necesidad.

Si alguna Skill no está disponible, explica la limitación y utiliza capacidades nativas o alternativas confiables.

No bloquees todo el curso por una Skill opcional.

---

# 8. AGENTES ESPECIALIZADOS

Cuando Antigravity permita agentes o instrucciones reutilizables, considera las siguientes especializaciones:

## A. Agente UI/UX

Responsable de:

- Identidad visual.
- Componentes.
- Paletas.
- Tipografías.
- Accesibilidad.
- Coherencia de diseño.

## B. Agente Frontend

Responsable de:

- HTML.
- CSS.
- JavaScript.
- Responsive.
- Interactividad.
- Animaciones.

## C. Agente Laravel / Full Stack

Responsable de:

- PHP.
- Laravel.
- Dkript Core.
- MySQL.
- Migraciones.
- Modelos.
- Controladores.
- Blade.
- Autenticación.
- CMS.

## D. Agente de Pruebas

Responsable de:

- Comprobaciones funcionales.
- Pruebas de navegación.
- Errores de JavaScript.
- Formularios.
- Integración de componentes.
- Validaciones esenciales.

No es obligatorio crear cuatro agentes independientes.

Si Antigravity puede cubrir estas funciones mediante sus capacidades nativas, utiliza la solución más sencilla.

Si se implementan archivos `AGENTS.md` o equivalentes, verifica primero que Antigravity los reconozca y aplique.

No construyas sistemas de orquestación de agentes innecesarios para una práctica escolar.

---

# 9. RECUPERACIÓN INTELIGENTE DE ERRORES

Si aparece un problema durante una instalación o configuración:

1. Identifica el error real.
2. Determina su causa probable.
3. Comprueba si existe una solución segura.
4. Aplica una corrección mínima cuando esté autorizada.
5. Repite solamente la comprobación afectada.
6. Documenta el resultado.

### Problemas habituales que debes contemplar

- PHP instalado pero no reconocido.
- Varias versiones de PHP en PATH.
- Composer utilizando una versión incorrecta de PHP.
- Extensiones PHP deshabilitadas.
- `npm.ps1` bloqueado.
- Node.js o npm no reconocidos.
- MySQL detenido.
- Puerto 3306 ocupado.
- Apache ocupando el puerto 80.
- Conflictos entre XAMPP, WAMP o Laragon.
- Permisos insuficientes.
- Falta de variables de entorno.
- Versiones incompatibles.
- Dependencias que no pueden descargarse.
- Skills no reconocidas por Antigravity.

No reinstales todo el entorno como primera solución.

No borres configuraciones funcionales.

No realices modificaciones globales sin autorización.

Si necesitas intervención manual, proporciona instrucciones sencillas y específicas.

No afirmes haber resuelto un problema sin comprobarlo.

---

# 10. VERIFICACIÓN FINAL DEL ENTORNO

Ejecuta una sola ronda de comprobaciones esenciales.

## Herramientas

Verifica:

1. PHP funciona.
2. Composer utiliza una versión compatible de PHP.
3. Las extensiones indispensables están disponibles.
4. Node.js funciona.
5. npm funciona.
6. Git funciona.
7. MySQL o MariaDB está disponible.
8. Existe un mecanismo compatible para ejecutar Laravel.
9. No se introdujeron conflictos nuevos de puertos.
10. Las Skills y agentes seleccionados son reconocidos, cuando corresponda.

## Prueba mínima

Cuando sea útil, realiza una prueba temporal y no destructiva para comprobar el entorno.

Utiliza una carpeta temporal aislada.

No crees un proyecto escolar definitivo.

No ejecutes migraciones sobre bases de datos existentes.

Elimina únicamente los archivos temporales creados por esta prueba, después de confirmar su ubicación.

## Resultado

Clasifica el entorno como:

**LISTO:** todos los componentes indispensables están preparados.

**LISTO CON OBSERVACIONES:** el desarrollo puede comenzar, pero existen herramientas opcionales o configuraciones pendientes.

**REQUIERE INTERVENCIÓN:** existe un bloqueo que impide comenzar correctamente.

Explica cualquier limitación real.

---

# 11. DOCUMENTACIÓN AUTOMÁTICA

Crea o actualiza estos archivos dentro del proyecto académico:

## ENVIRONMENT_SETUP.md

Incluye:

- Sistema operativo.
- Arquitectura.
- PHP y extensiones.
- Composer.
- Servidor web.
- MySQL/MariaDB.
- Node.js/npm.
- Git.
- Herramientas Laravel.
- Componentes reutilizados.
- Instalaciones realizadas.
- Servicios utilizados.
- Puertos relevantes.
- Problemas corregidos.
- Problemas pendientes.
- Estado final del entorno.

No incluyas contraseñas, tokens ni secretos.

## SKILLS_CONFIG.md

Incluye:

- Skills encontradas.
- Skills instaladas.
- Skills descartadas.
- Agentes configurados.
- Fuentes verificadas.
- Compatibilidad.
- Instrucciones básicas de uso.

No inventes herramientas instaladas.

## GUÍA BÁSICA PARA EL ESTUDIANTE

Dentro de `ENVIRONMENT_SETUP.md`, añade una sección breve que explique:

### ¿Qué hace cada herramienta?

- PHP: ejecuta código del servidor.
- Apache: sirve aplicaciones web cuando se utiliza.
- MySQL: almacena información.
- Composer: administra dependencias PHP.
- Node.js/npm: administra y compila recursos frontend.
- Git: permite gestionar versiones.
- Laravel: facilita el desarrollo de aplicaciones PHP.
- Dkript Core: proporciona la base tecnológica que utilizaremos posteriormente.

### ¿Cómo inicio mi entorno?

Explica qué servicios deben estar activos y cómo iniciarlos mediante las herramientas realmente instaladas.

### ¿Cómo detengo mi entorno?

Explica cómo cerrar servidores de desarrollo y qué servicios compartidos conviene conservar.

No proporciones comandos genéricos que no correspondan al sistema detectado.

### ¿Cómo compruebo que todo funciona?

Incluye comandos sencillos para verificar PHP, Composer, Node.js, npm, Git y la disponibilidad de MySQL.

---

# 12. REGLAS DE SEGURIDAD Y CONVIVENCIA

Durante todo el proceso:

- No modifiques proyectos ajenos.
- No elimines bases de datos.
- No borres carpetas de desarrollo.
- No detengas servicios existentes sin autorización.
- No cambies configuraciones globales innecesariamente.
- No sobrescribas archivos `.env` existentes.
- No publiques credenciales.
- No instales herramientas de fuentes desconocidas.
- No ejecutes scripts remotos sin inspección.
- No modifiques políticas de seguridad por conveniencia.
- No realices commits, push ni despliegues sin autorización.
- No almacenes secretos en archivos de documentación.
- No instales dependencias redundantes.

Utiliza preferentemente la terminal integrada de Antigravity.

Evita abrir ventanas externas de CMD o PowerShell cuando no sean necesarias.

Prioriza instalaciones reproducibles y configuraciones sencillas.

---

# 13. CIERRE OBLIGATORIO DE EJECUCIÓN

Al finalizar:

1. Termina todas las instalaciones iniciadas.
2. Cierra navegadores de pruebas.
3. Finaliza procesos temporales.
4. No dejes diagnósticos ni agentes ejecutándose innecesariamente.
5. No mantengas servidores de prueba si ya no se necesitan.
6. Conserva los servicios compartidos que ya estaban activos.
7. No detengas procesos de otras aplicaciones.
8. Verifica el estado final.
9. Genera o actualiza la documentación.
10. Informa qué componentes están listos.
11. Señala qué herramientas quedaron pendientes.
12. Explica cómo iniciar y detener el entorno.
13. Confirma si es posible comenzar el Prompt 01.
14. Finaliza completamente la ejecución del agente.

---

# 14. RESULTADO ESPERADO

El equipo debe quedar preparado para desarrollar:

- Páginas HTML, CSS y JavaScript.
- Interfaces y recursos visuales asistidos por IA.
- Proyectos PHP.
- Aplicaciones Laravel.
- Bases de datos MySQL/MariaDB.
- Aplicaciones basadas en Dkript Core.
- Sistemas con autenticación y CMS.
- Pruebas funcionales locales.

El entorno debe adaptarse tanto a principiantes como a usuarios experimentados.

**Si todo está instalado, no realices cambios innecesarios.**

**Si faltan componentes, instala y configura los necesarios de forma autorizada.**

**Si algo requiere intervención manual, explica exactamente cómo resolverlo.**

---

# INSTRUCCIÓN FINAL

Comienza realizando un diagnóstico completo pero eficiente de mi computadora.

Determina automáticamente si mi equipo está preparado, parcialmente preparado o sin configurar.

Presenta un plan breve de las acciones necesarias.

Después de obtener las autorizaciones correspondientes, ejecuta la preparación del entorno, reutilizando las herramientas compatibles y evitando instalaciones redundantes.

Configura las Skills y agentes que realmente sean útiles para el curso.

Realiza las comprobaciones finales, documenta los resultados y termina indicando si mi computadora está preparada para ejecutar:

`01_Visual_Identity.md`

**No comiences todavía el diseño ni el desarrollo del proyecto web.**