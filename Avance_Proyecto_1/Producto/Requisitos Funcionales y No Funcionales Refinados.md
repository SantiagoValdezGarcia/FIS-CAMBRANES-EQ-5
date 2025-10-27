# Requisitos Funcionales y No Funcionales
## EpilepsiApp

**Descripción General:**  
EpilepsiApp es una aplicación móvil para ayudar a personas con epilepsia. Permite registrar medicación, registrar crisis, enviar alertas de emergencia con ubicación en tiempo real y compartir información con médicos. Debe ser fácil de usar, segura y funcionar incluso sin conexión.

---

## Requisitos Funcionales

1. **Registro de usuario e inicio de sesión**
   - Crear cuenta con correo o teléfono.
   - Iniciar sesión con contraseña o huella digital.
   - Almacenar datos de forma segura.

2. **Perfil del paciente**
   - Registrar nombre, edad, peso, médico tratante y hasta 3 contactos de emergencia.
   - Validar formato de teléfono y correo.

3. **Gestión de medicación**
   - Agregar medicamentos con nombre, dosis, horario y duración.
   - Generar recordatorios automáticos para cada toma.

4. **Recordatorios de medicación**
   - Recibir notificaciones de toma.
   - Marcar cada toma como “realizada” o “omitida”.

5. **Historial de medicación**
   - Mostrar resumen gráfico o lista de cumplimiento.
   - Permitir exportar datos a PDF o CSV.

6. **Registro de crisis epilépticas**
   - Botón “Reportar crisis” con formulario de fecha, hora, duración, síntomas y causas.
   - Adjuntar fotos, videos o notas de voz.

7. **Botón de emergencia**
   - Enviar SMS o notificación a contactos con ubicación GPS actual.
   - Incluir nombre del paciente y enlace de ubicación.

8. **Ubicación en tiempo real**
   - Compartir ubicación activa en emergencias hasta que se detenga.
   - Uso eficiente del GPS.

9. **Modo sin conexión**
   - Registrar crisis o medicación sin internet.
   - Sincronizar automáticamente al conectarse.

10. **Compartir información con el médico**
    - Generar reporte automático (PDF o enlace temporal) con historial.
    - Enviar por correo o enlace seguro.

11. **Gestión de permisos y privacidad**
    - Solicitar permiso antes de usar ubicación, cámara, SMS o micrófono.
    - Mostrar aviso claro sobre uso de datos.

---

## Requisitos No Funcionales

1. **Seguridad**
   - Cifrar todos los datos con AES-256.
   - Requerir autenticación segura (MFA o PIN).
   - Cumplir con leyes de privacidad correspondientes.

2. **Rendimiento**
   - La app debe iniciar en menos de 3 segundos.
   - Las alertas deben enviarse en menos de 30 segundos.

3. **Disponibilidad**
   - Backend con disponibilidad del 99.5%.
   - Alertas deben enviarse incluso con poca señal (usar SMS).

4. **Usabilidad**
   - Acciones principales (emergencia, registrar crisis, tomar medicina) en máximo 3 toques.
   - Interfaz accesible y con íconos grandes.

5. **Interoperabilidad**
   - Permitir exportar e importar datos en PDF, CSV o JSON.

6. **Mantenibilidad**
   - Código limpio, modular y documentado.
   - Pruebas automáticas básicas incluidas.

7. **Consumo de energía**
   - Optimizar GPS y notificaciones para no gastar más del 5% de batería al día.
