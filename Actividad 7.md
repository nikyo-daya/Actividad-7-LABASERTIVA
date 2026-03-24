# Actividad 7

**Universidad de San Carlos de Guatemala**

**Facultad de Ingeniería**

**Escuela de Ingeniería en Ciencias y Sistemas**

**Laboratorio: Comunicación Asertiva — Sección A**


## Integrantes

| Integrante     | Carné     |
| -- | -- |
| Jeimy González | 202504807 |
| Danya Nicolle Gómez Ruiz | 202503869 |

---

## Mini‑Proyecto

### Aplicación de Seguimiento de Hábitos


## 1. Integrantes y Roles

| Nombre  | Roles asignados         |
| --| -- |
| Jeimy  | Moderadora · Timekeeper |
| Danya Nicolle Gómez Ruiz | Notetaker  |

### Descripción de roles

* **Moderadora (Jeimy):** Dirige la sesión de trabajo, coordina la participación del equipo, facilita la toma de decisiones y distribuye las tareas.
* **Timekeeper (Jeimy):** Controla el tiempo asignado a cada fase para cumplir con las 3 horas estimadas.
* **Notetaker (Danya):** Registra acuerdos, decisiones, avances y conclusiones durante toda la sesión.

### Distribución de tareas

* **Diseño de la aplicación:** Ambas integrantes
* **Desarrollo del código:** Danya
* **Manual de usuario (PDF):** Jeimy


## 2. Registro de Comunicación

### Chat con Netiqueta Profesional

Los siguientes mensajes simulan una conversación profesional durante una sesión de trabajo remoto, aplicando normas de netiqueta: comunicación clara, tono respetuoso, estructura ordenada y confirmación de tareas.

![](img/chat1.png)
![](img/chat2.png)
![](img/chat3.png)
![](img/chat4.png)
![](img/chat5.png)


## 3. Issues y Pull Requests

### [ISSUE‑01] Definición del problema de la aplicación

**Descripción:**
Se identifica y redacta de forma clara el problema principal que busca resolver la aplicación de seguimiento de hábitos.

**Cambios realizados:**

* Análisis de necesidades del usuario
* Redacción del problema central
* Delimitación del alcance del sistema
* Enfoque en gestión y constancia de hábitos

**Justificación:**
Definir el problema permite orientar el desarrollo hacia una solución concreta y alineada con las necesidades reales del usuario.

**Solicita revisión a:** Moderadora
**Estado:** Listo para revisión


### [ISSUE‑02] Funcionalidades principales del sistema

**Descripción:**
Identificación y detalle de las funcionalidades esenciales para el correcto funcionamiento de la aplicación.

**Cambios realizados:**

* Registro de usuarios
* Seguimiento de hábitos
* Recordatorios automáticos
* Estadísticas de progreso
* Panel de control del usuario

**Justificación:**
Estas funcionalidades permiten cumplir el propósito principal del sistema: ayudar al usuario a gestionar y monitorear hábitos de forma eficiente.

**Solicita revisión a:** Moderadora
**Estado:** Listo para revisión


### [ISSUE‑03] Definición de usuarios del sistema

**Descripción:**
Determinación de los tipos de usuarios que interactúan con la aplicación y sus permisos.

**Cambios realizados:**

* Identificación del usuario administrador
* Identificación del usuario estándar
* Definición de permisos por rol
* Accesos y restricciones del sistema

**Justificación:**
Definir los tipos de usuario mejora la organización, seguridad y gestión de la aplicación.

**Solicita revisión a:** Moderadora
**Estado:** Listo para revisión


### [ISSUE‑04] Funcionamiento de la aplicación

**Descripción:**
Explicación clara y secuencial de la interacción del usuario con el sistema.

**Cambios realizados:**

* Flujo de registro e inicio de sesión
* Creación y gestión de hábitos
* Configuración de recordatorios
* Visualización de estadísticas
* Navegación general de la interfaz

**Justificación:**
Documentar el funcionamiento facilita la comprensión del sistema y reduce errores de uso.

**Solicita revisión a:** Moderadora
**Estado:** Listo para revisión


### [ISSUE‑05] Integración del documento final

**Descripción:**
Consolidación de todas las secciones del proyecto en un único documento.

**Cambios realizados:**

* Unificación de secciones
* Revisión de coherencia
* Corrección de redacción y formato
* Validación de estructura final

**Justificación:**
La integración asegura una presentación clara, ordenada y profesional.

**Solicita revisión a:** Moderadora
**Estado:** Listo para revisión

### [PR‑01] Definición del problema y usuarios del sistema

**Descripción:**
Redacción de la definición del problema y especificación de los tipos de usuario.

**Cambios:**

* Sección: Definición del problema
* Sección: Usuarios del sistema (Usuario Registrado y Administrador)

**Justificación:**
Establece la base conceptual del proyecto.

**Solicita revisión a:** Danya (Notetaker)
**Estado:** Aprobado


### [PR‑02] Funcionalidades y flujo de uso

**Descripción:**
Incorporación de funcionalidades principales y descripción del funcionamiento.

**Cambios:**

* Funcionalidades principales (registro de hábitos, seguimiento diario, recordatorios y estadísticas)
* Flujo de uso de la aplicación (reconstruido tras evento de fallback)

**Justificación:**
Define el núcleo funcional del sistema y clarifica la experiencia del usuario.

**Solicita revisión a:** Jeimy (Moderadora)
**Estado:** Aprobado


## 4. Documento Compartido

### 4.1 Definición del problema

Muchas personas tienen dificultades para mantener hábitos saludables de forma constante debido a la falta de seguimiento, organización y motivación. No existe una herramienta personalizada y sencilla que permita registrar hábitos, monitorear el progreso y recibir recordatorios oportunos en un solo lugar. Esta aplicación busca resolver esa necesidad mediante una interfaz intuitiva y accesible.

### 4.2 Funcionalidades principales

1. **Registro de hábitos:** Crear, editar y eliminar hábitos personalizados (nombre, categoría y frecuencia).
2. **Seguimiento diario:** Registro del cumplimiento diario con historial visual.
3. **Recordatorios automáticos:** Notificaciones configurables.
4. **Estadísticas de progreso:** Gráficas y porcentajes de cumplimiento semanal y mensual.
5. **Rachas (streaks):** Conteo de días consecutivos de cumplimiento para fomentar constancia.

### 4.3 Usuarios del sistema

| Tipo de usuario  | Descripción |
| -- | -- |
| **Usuario Registrado** | Crea una cuenta, gestiona hábitos y consulta su progreso. |
| **Administrador**  | Gestiona cuentas, monitorea el uso y realiza mantenimiento del sistema. |

### 4.4 Funcionamiento de la aplicación

1. El usuario instala la aplicación o accede desde el navegador.
2. Se registra con correo y contraseña o mediante inicio de sesión social.
3. Desde el panel principal, crea hábitos indicando nombre, categoría y frecuencia.
4. Marca diariamente los hábitos cumplidos.
5. La aplicación actualiza automáticamente historial y estadísticas.
6. Recibe notificaciones según recordatorios configurados.
7. Consulta gráficas de progreso y rachas para mantenerse motivado.



## 5. Procedimiento de Fallback Aplicado

**Evento simulado:** Pérdida del avance del proyecto por cierre inesperado del editor.

**Procedimiento aplicado:**

1. Notificación inmediata del incidente al equipo.
2. Evaluación del tiempo restante por parte de la Moderadora.
3. Reasignación inmediata del proyecto.
4. Reconstrucción del contenido con base en acuerdos previos.

**Lección aprendida:**
Guardar avances con frecuencia, usar herramientas con autoguardado y mantener comunicación inmediata son prácticas esenciales en el trabajo remoto.



## 6. Presentación Final

### Organización del equipo

El equipo se organizó mediante la asignación clara de roles desde el inicio. Jeimy asumió los roles de Moderadora y Timekeeper, coordinando la sesión y gestionando los tiempos. Danya asumió el rol de Notetaker, registrando avances y acuerdos. Las tareas se distribuyeron equitativamente según capacidades y disponibilidad.

### Gestión de la comunicación

La comunicación se realizó mediante chat simulado, aplicando principios de netiqueta profesional: mensajes claros, tono respetuoso, colaboración constante, confirmación de tareas y notificación inmediata de imprevistos.

### Dificultades encontradas

La principal dificultad fue la pérdida accidental del avance del proyecto por cierre inesperado del editor. Además, al tratarse de un equipo de dos integrantes, cada persona asumió mayor carga de trabajo.

### Estrategias de solución

* **Fallback inmediato:** Reasignación rápida para evitar retrasos
* **Comunicación proactiva:** Reporte constante de avances y problemas
* **Distribución flexible:** Ajuste de responsabilidades según la situación
