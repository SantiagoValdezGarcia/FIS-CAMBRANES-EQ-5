# EpilepsiApp – Priorización de Requisitos con Metodología MoSCoW

## 1. Introducción

La epilepsia es un trastorno neurológico que afecta a millones de personas en todo el mundo. Los pacientes con epilepsia enfrentan múltiples desafíos en su vida diaria, tales como mantener una adherencia constante al tratamiento, registrar con precisión sus crisis y acceder rápidamente a soporte en situaciones de emergencia. La falta de herramientas adecuadas puede afectar negativamente la calidad de vida, incrementar el riesgo de accidentes y generar ansiedad y estrés en los pacientes y sus familiares.

Con el objetivo de mejorar la gestión de la enfermedad y proporcionar un soporte integral, se ha diseñado **EpilepsiApp**, una aplicación móvil enfocada en el monitoreo, registro y apoyo a pacientes con epilepsia. Para garantizar que la aplicación cumpla con las necesidades más críticas de los usuarios desde su lanzamiento, se ha implementado la metodología **MoSCoW**, que permite priorizar los requisitos según su importancia y relevancia.

## 2. Metodología MoSCoW

La metodología MoSCoW es un enfoque ampliamente utilizado en gestión de proyectos y desarrollo de software para la priorización de requisitos. Su nombre proviene de las iniciales de las categorías de priorización:

- **Must Have (Debe tener):** Requisitos esenciales e indispensables para el MVP. Sin estos, el producto no cumpliría su función principal.
- **Should Have (Debería tener):** Requisitos importantes que aportan valor significativo, pero que no comprometen la funcionalidad básica si no se incluyen inicialmente.
- **Could Have (Podría tener):** Requisitos opcionales que mejoran la experiencia del usuario o añaden funcionalidades complementarias, generalmente considerados para versiones futuras.
- **Won’t Have (No tendrá):** Requisitos descartados temporalmente que no se implementarán en el corto plazo debido a limitaciones de tiempo, recursos o relevancia.

Este enfoque asegura un desarrollo eficiente, permitiendo centrar los recursos en lo que realmente es crítico para el éxito inicial de la aplicación y planificar mejoras futuras de manera estratégica.

## 3. Priorización de Requisitos

### 3.1 Must Have (Indispensable para el MVP)

| Requisito              | Descripción |
|------------------------|-------------|
| Registro e inicio de sesión | Permite la creación de cuentas seguras para usuarios y pacientes, protegiendo la información personal y garantizando autenticación confiable. |
| Creación de perfil      | Incluye datos personales, contactos de emergencia y otra información relevante para un monitoreo efectivo. Mínimo un contacto obligatorio garantiza apoyo en caso de emergencia. |
| Registro de medicación  | Permite a los pacientes registrar sus medicamentos, horarios y dosis, con notificaciones automáticas que aseguran la adherencia al tratamiento. |
| Diario de crisis        | Registra fecha, hora, duración, síntomas y desencadenantes de cada crisis, proporcionando información valiosa para médicos y seguimiento personal. |
| Evidencia multimedia    | La inclusión de fotos, videos y audios de cada crisis permite un análisis más completo y facilita la comunicación con profesionales de la salud. |
| Botón de emergencia     | Acceso rápido para enviar alertas a contactos y servicios de emergencia con ubicación en tiempo real, asegurando respuesta rápida. |
| Historial visual        | Permite visualizar la medicación y las crisis en un calendario o línea de tiempo, facilitando la comprensión de patrones y adherencia. |
| Seguridad de datos      | Incluye cifrado y autenticación reforzada para proteger la información sensible del paciente, cumpliendo estándares de privacidad. |
| Cumplimiento normativo  | Garantiza que la aplicación cumple con regulaciones internacionales de protección de datos (ej. GDPR, HIPAA), reduciendo riesgos legales y aumentando confianza de usuarios. |

---

### 3.2 Should Have (Altamente deseables)

| Requisito                | Descripción |
|--------------------------|-------------|
| Visualización de adherencia | Presenta gráficos que permiten a pacientes y médicos evaluar el cumplimiento del tratamiento de manera visual y clara. |
| Compartir historiales      | Permite exportar la información de medicación y crisis en PDF o mediante enlace seguro para profesionales de salud, facilitando el seguimiento clínico. |
| Uso sin conexión           | Permite que la aplicación funcione aún sin conectividad, sincronizando los datos automáticamente cuando la conexión se restablece. |
| Alertas configurables      | Notificaciones ajustables según importancia (suaves o críticas), adaptándose a las necesidades y preferencias del paciente. |
| Flujo simplificado         | Optimiza la navegación de la aplicación para que los usuarios puedan registrar información en pocos pasos, aumentando la usabilidad. |
| Notificaciones inteligentes | Detecta la omisión de varias dosis consecutivas y ajusta alertas para mejorar la adherencia al tratamiento. |

---

### 3.3 Could Have (Mejoras opcionales)

| Requisito                | Descripción |
|--------------------------|-------------|
| Integración con wearables | Conexión con dispositivos portátiles como smartwatches para registrar datos de salud en tiempo real y detectar crisis automáticamente. |
| Reconocimiento de patrones | Uso de IA para identificar patrones en las crisis y ayudar en la predicción o prevención de episodios. |
| Calendarios externos      | Integración con Google Calendar o Outlook para sincronizar recordatorios de medicación y eventos importantes. |
| Chat seguro               | Comunicación directa con profesionales de salud a través de mensajería de texto segura. |
| Sección educativa         | Contenido didáctico sobre epilepsia, prevención de desencadenantes y hábitos saludables. |
| Gamificación              | Implementación de logros y recompensas virtuales para incentivar la adherencia y el compromiso del paciente. |
| Modo acompañante          | App ligera para familiares que reciben únicamente alertas y notificaciones importantes, fortaleciendo el soporte familiar. |

---

### 3.4 Won’t Have (Descartado por ahora)

| Requisito                | Descripción |
|--------------------------|-------------|
| Videollamadas            | Se descartan las teleconsultas integradas debido al alto consumo de recursos y la regulación compleja. |
| Acceso anónimo            | Requiere registro para garantizar seguridad, trazabilidad y protección de la información. |
| Publicidad                | No se incluirá publicidad de terceros para evitar distracciones y riesgos de privacidad. |
| Red social interna        | Evita la desinformación, sobrecarga de información y riesgos legales asociados a interacciones entre usuarios. |

---

## 4. Enfoque del MVP
El MVP de **EpilepsiApp** se centra en los elementos más críticos para garantizar seguridad, adherencia y documentación confiable:

- **Seguridad:** El botón de emergencia y las alertas permiten una respuesta rápida en caso de crisis, protegiendo la integridad del paciente.  
- **Adherencia:** Los recordatorios y el registro de medicación aseguran que los pacientes mantengan un control efectivo de su tratamiento.  
- **Documentación de crisis:** La recopilación de evidencia multimedia y el diario detallado permiten un seguimiento clínico preciso y ayudan a la toma de decisiones médicas.  
- **Historial accesible y compartible:** Facilita la revisión por profesionales de salud y mejora la comunicación entre pacientes y médicos, contribuyendo a un mejor control de la enfermedad.
