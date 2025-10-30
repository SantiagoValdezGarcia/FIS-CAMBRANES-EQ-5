# EpilepsiApp

## Introducción
La epilepsia es un trastorno neurológico crónico que afecta a millones de personas en el mundo. Una de las principales dificultades que enfrentan los pacientes es mantener la adherencia al tratamiento, registrar sus crisis y contar con un sistema de apoyo rápido en emergencias.  

**EpilepsiApp** es una aplicación móvil innovadora que busca mejorar la calidad de vida de los pacientes y sus familias a través de herramientas digitales accesibles y confiables.

Este documento presenta el propósito, originalidad, funcionalidades principales, beneficios, limitaciones y análisis de valor de EpilepsiApp en el ámbito de la salud digital.

---

## Objetivo Principal
- Ayudar a las personas con epilepsia a mantener la adherencia al tratamiento mediante recordatorios de medicación.  
- Registrar y monitorear crisis con evidencia multimedia.  
- Mejorar la comunicación con el médico tratante.  
- Garantizar seguridad en emergencias mediante alertas automáticas a contactos de confianza.  

**Originalidad:** Integración de varios servicios en una sola plataforma específica para epilepsia, combinando cuatro pilares:
1. Registro y seguimiento de medicación.
2. Diario de crisis con evidencia multimedia.
3. Alertas automáticas a contactos/emergencias.
4. Historial visual y compartible con el médico.

La propuesta de valor se centra en la seguridad y acompañamiento del paciente, creando un ecosistema digital que conecta al paciente con su red de apoyo y su médico.

---

## Funcionalidades Principales

1. **Registro y seguimiento de medicación**
   - Ingresar tratamiento: medicamento, dosis, horario y duración.
   - Notificaciones automáticas para cada toma.
   - Marcar cada toma como realizada u omitida.
   - Generar historial gráfico compartible con el médico.

2. **Diario de crisis con evidencia multimedia**
   - Registrar cada crisis con fecha, hora, duración, síntomas y posibles desencadenantes.
   - Adjuntar fotos, audios o videos.
   - Historial visual accesible en calendario o línea de tiempo.

3. **Alertas automáticas a contactos/emergencias**
   - Configurar hasta tres contactos de confianza.
   - Enviar SMS con ubicación en tiempo real en crisis graves.
   - Botón de emergencia rápida para alertas inmediatas.

4. **Flujo de uso**
   1. Registrar medicación y contactos de emergencia.
   2. Recibir recordatorios diarios.
   3. Reportar crisis mediante botón “Reportar crisis”.
   4. Activar botón de emergencia si la crisis es grave.

---

## Utilidad e Impacto
- **Pacientes:** Mejora adherencia al tratamiento y ofrece seguridad en emergencias.  
- **Familiares:** Reciben alertas en tiempo real.  
- **Médicos:** Acceden a registros claros y completos para ajustar diagnósticos y tratamientos.  

**Impacto esperado:** Reducción de complicaciones, mejor control de crisis y aumento de tranquilidad para paciente y familia.

---

## Requisitos

### Funcionales
- Registro e inicio de sesión.
- Creación de perfiles con contactos de emergencia.
- Registro y recordatorio de medicación.
- Reporte de crisis y envío de ubicación en tiempo real.
- Botón de emergencia rápida.
- Visualización de adherencia terapéutica.
- Integración de evidencia multimedia.
- Compartir historiales médicos.
- Modo de uso sin conexión.

### No funcionales
- Seguridad: cifrado de datos, autenticación reforzada y cumplimiento normativo.
- Rendimiento: tiempos de respuesta adecuados, alta disponibilidad y entrega oportuna de notificaciones.
- Usabilidad: flujo simplificado en pocos pasos.
- Interoperabilidad: exportación de datos y soporte para APIs estandarizadas.
- Mantenibilidad del código.
- Optimización del consumo energético.

**Validación:** Documento SRS, diagramas de casos de uso, prototipos, modelos de datos, matriz de trazabilidad, pruebas unitarias, de integración, rendimiento, seguridad y usabilidad, y validación por pacientes, familiares y profesionales de la salud.

**Riesgos y mitigación:** Baja conectividad, divulgación de datos sensibles, mitigados mediante SMS y notificaciones redundantes, cifrado robusto y consentimiento informado.

---

## Pros y Contras

**Ventajas:**
- Fomenta autocuidado y disciplina terapéutica.
- Centraliza información clave para médicos y pacientes.
- Aumenta seguridad en situaciones críticas.
- Interfaz sencilla y accesible.
- Reduce riesgos de hospitalización por omisión de medicación.

**Limitaciones:**
- Requiere acceso constante a teléfono inteligente e internet.
- Posible dependencia excesiva de la app.
- Riesgo de fallos técnicos o de conectividad.
- Necesidad de mantener actualizada la información de medicación y contactos.

---

## Roles de Proyecto

1. **Jefe de Proyecto / Analista de Requerimientos (Santiago Valdez Garcia)**
   - Coordinar equipo, administrar tiempos y entregables.
   - Identificar necesidades y convertirlas en requisitos.
   - Mantener comunicación con médicos y asociaciones de pacientes.

2. **Diseñador UX/UI (Gabriel Cuadros Colorado)**
   - Diseñar interfaz clara y accesible.
   - Crear prototipos, wireframes e identidad visual.
   - Garantizar accesibilidad para usuarios con limitaciones visuales o motoras.

3. **Desarrollador Backend (Adrián Cab)**
   - Arquitectura de servidor y base de datos.
   - Seguridad y encriptación de información sensible.
   - Integración con servicios externos (geolocalización, alertas).

4. **Desarrollador Frontend / Móvil (Lucy Iriel Fernández)**
   - Implementación en Android e iOS.
   - Integración UX/UI con backend.
   - Funcionalidades clave: registro de crisis, botón de emergencia, notificaciones.

5. **Tester / QA y Comunicación (Diego Pérez Can)**
   - Pruebas en diferentes dispositivos y escenarios.
   - Detectar errores y sugerir mejoras.
   - Preparar materiales de comunicación y difusión.

6. **Especialista Médico-Asesor (José)**
   - Brindar información validada sobre epilepsia.
   - Asesorar sobre protocolos de emergencia.
   - Validar contenido educativo.
   - Asegurar funciones ajustadas a necesidades médicas.

---

## Competencias Técnicas
- **Análisis y levantamiento de requerimientos:** Identificación de necesidades, conversión en requisitos funcionales y no funcionales.
- **Diseño de software:** Arquitecturas frontend/backend, diagramas UML, casos de uso, flujos de interacción.
- **Desarrollo móvil y multiplataforma:** Android/iOS, integración con geolocalización, notificaciones y APIs externas.
- **Gestión de bases de datos:** Diseño seguro, escalable y encriptación de datos médicos.
- **Pruebas y QA:** Unitarias, funcionales y de usabilidad, automatización de testing.
- **Seguridad informática:** Protocolos de autenticación y cumplimiento de normativas (GDPR, LFPDPPP).

---

## Competencias de Gestión
- Trabajo en equipo multidisciplinario.
- Gestión de proyectos de software (Scrum, Kanban).
- Documentación y comunicación técnica y con usuarios/instituciones.

---

## Competencias Personales y Sociales
- Pensamiento crítico y resolución de problemas.
- Responsabilidad ética y profesional en manejo de información médica.
- Innovación y emprendimiento con impacto social y modelos de negocio sostenibles.

---

## Conclusión
EpilepsiApp es una propuesta innovadora en salud digital, combinando registro médico, comunicación con el entorno y seguridad en emergencias en una sola app. Sus beneficios superan las limitaciones técnicas y de acceso, buscando mejorar la calidad de vida de pacientes con epilepsia y contribuir a un modelo de atención integral, conectado y humano.
