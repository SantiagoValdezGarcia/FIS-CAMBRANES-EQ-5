# Requerimientos Finales - EpilepsiApp

## Requerimientos Funcionales

### 1. Pantalla de inicio
1.1 La aplicación debe mostrar un botón de emergencia que permita enviar una alerta a los contactos de emergencia con la ubicación del usuario.  
1.2 La aplicación debe permitir registrar una nueva crisis, indicando tipo, duración, síntomas y posibles desencadenantes.  
1.3 La aplicación debe permitir agregar un nuevo medicamento, con nombre, dosis, horario, frecuencia y duración.  
1.4 El sistema debe mostrar una lista de “Próximos Medicamentos” con opción para marcar cada uno como “Tomada” u “Omitida”.  
1.5 La aplicación debe mostrar una lista de las últimas crisis registradas con su tipo, fecha y duración.  

### 2. Historial
2.1 El sistema debe mostrar un historial general con todos los eventos registrados (crisis, medicación y emergencias).  
2.2 El usuario debe poder filtrar el historial por tipo de registro (crisis, medicación o emergencia).  
2.3 Cada elemento del historial debe incluir fecha, tipo de evento, descripción y estado.  

### 3. Reportes y estadísticas
3.1 La aplicación debe permitir al usuario generar reportes personalizados con sus datos médicos.  
3.2 El sistema debe mostrar estadísticas visuales como:  
- Cumplimiento de medicación (%)  
- Número de crisis por mes  
- Tipos de crisis más frecuentes  
- Número de alertas enviadas  
3.3 El usuario debe poder exportar sus datos en diferentes formatos (PDF, CSV, JSON).  
3.4 El usuario debe poder seleccionar rango de fechas y tipo de datos antes de exportar.  

### 4. Perfil
4.1 El sistema debe mostrar la información personal del usuario (nombre, fecha de nacimiento, teléfono).  
4.2 Debe mostrar la información médica (médico tratante, teléfono médico, tipo de epilepsia).  
4.3 Debe mostrar y permitir editar los contactos de emergencia.  
4.4 Debe permitir editar la información personal y médica mediante botones de edición.  
4.5 Debe mostrar la configuración del sistema (notificaciones, ubicación, modo sin conexión).  

### 5. Emergencias
5.1 Al presionar el botón de emergencia, debe abrirse una ventana de confirmación.  
5.2 El sistema debe permitir confirmar o cancelar el envío de la alerta.  
5.3 Al confirmar, debe notificar a los contactos de emergencia y compartir la ubicación actual por un tiempo determinado.  
5.4 Debe mostrar los contactos con su estado en línea o desconectado.  

### 6. Funciones adicionales (PWA y offline)
6.1 La aplicación debe poder instalarse como PWA en dispositivos móviles.  
6.2 Debe detectar la conexión a internet y mostrar un aviso cuando esté en modo sin conexión.  
6.3 Debe permitir registrar datos y ver información aunque no haya conexión.  
6.4 Debe sincronizar la información cuando vuelva a haber conexión.  

---

## Requerimientos No Funcionales

### 1. Usabilidad
1.1 Interfaz intuitiva
La pantalla de la app debe ser muy clara:
- Los **iconos** deben representar exactamente lo que hacen (por ejemplo, un ícono de campana para alertas).
- Los **textos** deben ser simples, sin palabras complicadas.

1.2 Botones importantes siempre visibles: Algunas funciones deben ser accesibles **todo el tiempo**, sin buscar en menús.
Por ejemplo, el botón **“Emergencia”** debe estar siempre en pantalla para que el usuario pueda usarlo rápido si lo necesita.

 1.3 Navegación sin recargar la app: El usuario debe poder cambiar entre pantallas como **Inicio**, **Historial**, **Reportes** y **Perfil** sin que la app se reinicie o tarde mucho.  
Es decir, cambiar de una sección a otra debe ser fluido y sin tiempos de espera.

1.4 Mensajes y alertas claras
La app debe mostrar mensajes claros cuando:
- El usuario haga una acción importante (por ejemplo: “¿Seguro que deseas borrar este reporte?”).
- O cuando ocurra un error (por ejemplo: “No se pudo enviar el reporte. Intenta otra vez.”).

### 2. Rendimiento
2.1 La aplicación debe cargar completamente en menos de 3 segundos en dispositivos móviles.  
2.2 Las transiciones entre pantallas deben ser suaves y sin retrasos perceptibles.  
3.3 Las alertas, formularios y botones deben responder en menos de 1 segundo al interactuar.  

### 3. Compatibilidad
3.1 La aplicación debe funcionar correctamente en los navegadores Google Chrome, Microsoft Edge y Safari móvil.  
3.2 Debe ser compatible con los sistemas operativos Android y iOS mediante instalación PWA.  
3.3 Debe adaptarse automáticamente al tamaño de pantalla de teléfonos y tabletas.  

### 4. Seguridad
4.1 Los datos personales, médicos y de emergencia deben almacenarse de forma segura y privada.  
4.2 Solo el usuario autenticado debe poder acceder a su información médica y contactos.  
4.3 Los datos enviados (por ejemplo, en alertas de emergencia) deben transmitirse usando conexiones seguras (HTTPS).  
4.4 La aplicación no debe compartir información con terceros sin consentimiento del usuario.  

### 5. Confiabilidad y disponibilidad
5.1 La aplicación debe poder funcionar en modo sin conexión, permitiendo registrar datos y ver información guardada.  
5.2 Al recuperar la conexión, los datos deben sincronizarse automáticamente con la base de datos.  
5.3 La app debe tener una disponibilidad del 99% del tiempo operativo.  
5.4 Debe mostrar un indicador de conexión cuando el dispositivo esté offline o vuelva al modo online.  

### 6. Accesibilidad
6.1 Los colores de la interfaz deben tener contraste suficiente para personas con baja visión.  
6.2 La tipografía debe ser legible y escalable en diferentes tamaños de pantalla.  
6.3 Los botones y campos deben tener tamaño adecuado para interacción táctil.  
6.4 La aplicación debe ofrecer indicaciones visuales y auditivas en funciones críticas (como emergencias).  

### 7. Interoperabilidad
7.1 Los archivos exportados (PDF, CSV, JSON) deben ser compatibles con programas como Excel, Google Sheets y sistemas médicos externos.  
7.2 Los datos exportados deben mantener estructura y formato uniforme.  
7.3 La aplicación debe permitir en el futuro integrarse con servicios médicos o APIs externas.  

### 8. Mantenibilidad
8.1 El código fuente debe estar organizado y documentado para facilitar modificaciones.  
8.2 Las funciones y componentes deben estar modularizados para permitir mejoras sin afectar el resto del sistema.  
8.3 El sistema debe permitir actualizaciones periódicas sin pérdida de datos.  

8.4 Los errores comunes deben poder detectarse y corregirse fácilmente durante el mantenimiento.  
