# EpilepsiApp – Requisitos Unificados

## Descripción General
EpilepsiApp es una aplicación móvil y PWA diseñada para mejorar la calidad de vida de personas con epilepsia. Facilita el registro de crisis epilépticas y tratamientos médicos, envía alertas de emergencia con ubicación en tiempo real y permite comunicación segura entre paciente y médico. La app debe ser usable, confiable, segura y funcional incluso sin conexión a internet.

---

## Must Have (Versión 1.0)

### RF1. Registro e inicio de sesión
Permite crear cuenta mediante correo o teléfono e iniciar sesión con contraseña o huella digital.

### RF3. Gestión de medicación
Registra medicamentos (nombre, dosis, horario, duración) y permite marcar tomas realizadas u omitidas.

### RF4. Recordatorios de medicación
Genera notificaciones automáticas basadas en horarios configurados.

### RF6. Registro de crisis epilépticas
Registra fecha, duración, síntomas, causas y permite adjuntar multimedia.

### RF7. Botón de emergencia
Envía alertas con ubicación GPS a contactos de emergencia previa confirmación.

### RF11. Gestión de permisos y privacidad
Solicita autorización para GPS, cámara y micrófono, explicando uso de datos personales.

---

## Should Have

### RF2. Perfil del paciente
Registra y edita información personal, médica y contactos de emergencia.

### RF5. Historial de medicación y crisis
Historial filtrable con detalles completos para análisis clínico.

### RF8. Ubicación en tiempo real
Comparte ubicación activa durante emergencias hasta desactivación manual.

### RF10. Compartir información con el médico
Genera reportes exportables en PDF, CSV o JSON.

---

## Could Have

### RF9. Modo sin conexión (PWA)
Permite funcionamiento sin internet y sincroniza datos al reconectarse.

---

## Requisitos No Funcionales – Must Have

### RNF1. Seguridad
Cifrado AES-256, autenticación segura y uso de HTTPS cumpliendo normativas de privacidad.

### RNF3. Disponibilidad y confiabilidad
Funcionamiento estable del 99% y envío de alertas incluso con señal limitada.

### RNF4. Usabilidad y accesibilidad
Interfaz intuitiva; acciones principales en tres toques o menos; accesibilidad visual y auditiva.

---

## Requisitos No Funcionales – Should Have

### RNF2. Rendimiento
Carga < 3 segundos; respuesta < 1 segundo; transiciones fluidas.

### RNF6. Mantenibilidad
Código modular, documentado, estructurado y compatible con actualizaciones sin pérdida de datos.

---

## Requisitos No Funcionales – Could Have

### RNF5. Interoperabilidad
Exportación compatible con Excel, Google Sheets y sistemas médicos.

### RNF7. Consumo de energía
Optimización del GPS y notificaciones para no superar el 5% del consumo diario de batería.

---

## Priorización General (MoSCoW)

| Categoría       | Requisitos Funcionales             | Requisitos No Funcionales |
|-----------------|------------------------------------|----------------------------|
| **Must Have**   | RF1, RF3, RF4, RF6, RF7, RF11      | RNF1, RNF3, RNF4           |
| **Should Have** | RF2, RF5, RF8, RF10                | RNF2, RNF6                 |
| **Could Have**  | RF9                                | RNF5, RNF7                 |
| **Won’t Have**  | —                                  | —                          |

---

