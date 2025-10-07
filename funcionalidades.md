# 🧪 Funcionalidades a Probar - FitCourt Beta

Esta lista te ayudará a probar todas las funcionalidades principales de FitCourt. Por favor, intenta realizar todas las acciones y reporta cualquier problema que encuentres.

## ✅ Checklist de Pruebas

### 🔐 Autenticación

- [ ] **Registro de nuevo usuario**

  - Crear cuenta con email y contraseña
  - Verificar que se solicite nombre completo
  - Verificar que la contraseña tenga mínimo 6 caracteres
  - ¿Recibiste algún error? ¿Cuál?

- [ ] **Inicio de sesión**

  - Iniciar sesión con las credenciales creadas
  - Cerrar sesión
  - Volver a iniciar sesión
  - ¿La sesión se mantiene al cerrar y abrir la app?

- [ ] **Validación de formularios**
  - Intentar registrarse sin llenar todos los campos
  - Intentar usar un email inválido (ej: "test@")
  - Intentar usar una contraseña muy corta (menos de 6 caracteres)
  - ¿Se muestran mensajes de error apropiados?

### 🗺️ Mapa Interactivo

- [ ] **Visualización del mapa**

  - El mapa se carga correctamente
  - Se muestran los tiles del mapa (no está en blanco/gris)
  - Se ve el logo de Google en la esquina inferior
  - ¿El mapa se ve completo y funcional?

- [ ] **Ubicación del usuario**

  - Se muestra tu ubicación actual (punto azul)
  - El mapa centra en tu ubicación al abrir
  - ¿La ubicación es precisa?

- [ ] **Navegación del mapa**

  - Hacer zoom in (acercar con dos dedos)
  - Hacer zoom out (alejar con dos dedos)
  - Desplazar el mapa en todas direcciones
  - ¿El mapa responde suavemente a los gestos?

- [ ] **Marcadores de parques**
  - Se muestran marcadores rojos en el mapa
  - Los marcadores representan parques/canchas
  - ¿Cuántos marcadores ves en tu área?

### 📍 Información de Parques

- [ ] **Callouts (burbujas de información)**

  - Tocar un marcador en el mapa
  - Se muestra una burbuja con nombre del parque
  - La burbuja muestra "Ver más →"
  - ¿La información es legible?

- [ ] **Detalles del parque**

  - Tocar "Ver más →" en un callout
  - Se abre pantalla de detalles completa
  - Se muestra:
    - Nombre del parque
    - Dirección
    - Ciudad
    - Horarios (si disponible)
    - Amenidades (si disponible)
    - Imagen del parque (si disponible)
  - ¿Toda la información se muestra correctamente?

- [ ] **Navegación entre parques**
  - Ver detalles de varios parques diferentes
  - Regresar al mapa
  - ¿La navegación es fluida?

### 👤 Perfil de Usuario

- [ ] **Visualización del perfil**

  - Ir a la pestaña "Perfil"
  - Se muestra tu nombre
  - Se muestra tu email
  - Se muestra foto de perfil (o placeholder)
  - ¿La información es correcta?

- [ ] **Edición de perfil** (si disponible)

  - Cambiar nombre de usuario
  - Cambiar foto de perfil
  - ¿Los cambios se guardan correctamente?

- [ ] **Cerrar sesión**
  - Tocar botón "Cerrar Sesión"
  - Se muestra confirmación
  - Confirmar cierre de sesión
  - ¿Regresa a la pantalla de bienvenida/login?

### 📱 Navegación General

- [ ] **Pestañas principales**

  - Cambiar entre pestaña "Mapa" y "Perfil"
  - Verificar que ambas pestañas funcionan
  - ¿Las pestañas responden rápidamente?

- [ ] **Botones de navegación**
  - Usar botón "Atrás" en pantallas de detalles
  - Verificar que regresa a la pantalla anterior
  - ¿La navegación es intuitiva?

### 🎨 Interfaz de Usuario

- [ ] **Diseño visual**

  - Verificar que los colores sean consistentes
  - Verificar que el texto sea legible
  - Verificar que los botones sean claros
  - ¿Hay algún elemento que se vea mal?

- [ ] **Animaciones**

  - Observar transiciones entre pantallas
  - Observar animaciones de botones al presionar
  - ¿Las animaciones son suaves?

- [ ] **Responsividad**
  - Rotar el dispositivo (horizontal/vertical)
  - Verificar que la UI se adapta correctamente
  - ¿La app funciona bien en ambas orientaciones?

## 🐛 Escenarios Específicos a Probar

### Conectividad

- [ ] **Sin conexión a internet**

  - Desactivar WiFi y datos móviles
  - Intentar usar la app
  - ¿Se muestra un mensaje de error apropiado?

- [ ] **Conexión lenta**
  - Usar la app con conexión 3G lenta
  - ¿El mapa se carga correctamente?
  - ¿Hay timeouts o errores?

### Permisos

- [ ] **Denegar ubicación**

  - Rechazar permiso de ubicación
  - ¿Se muestra un mensaje explicativo?
  - ¿La app sigue funcionando (sin ubicación)?

- [ ] **Conceder ubicación después**
  - Ir a Ajustes del dispositivo
  - Dar permiso de ubicación a FitCourt
  - Volver a la app
  - ¿Ahora muestra tu ubicación?

### Rendimiento

- [ ] **Uso de memoria**

  - Usar la app por 10-15 minutos
  - Navegar entre múltiples pantallas
  - ¿La app se siente lenta o se calienta el dispositivo?

- [ ] **Uso prolongado**
  - Dejar la app abierta en segundo plano
  - Volver a la app después de 30 minutos
  - ¿La app sigue funcionando correctamente?

## 📊 Casos Límite

- [ ] **Muchos parques en pantalla**

  - Hacer zoom out para ver muchos marcadores
  - ¿El mapa se mantiene fluido?

- [ ] **Zoom extremo**

  - Hacer zoom in al máximo
  - Hacer zoom out al máximo
  - ¿La app responde correctamente?

- [ ] **Cambios rápidos**
  - Cambiar rápidamente entre pestañas
  - Abrir y cerrar detalles de parques rápidamente
  - ¿La app maneja bien los cambios rápidos?

## 📝 ¿Encontraste un Problema?

Si encuentras algún bug o comportamiento inesperado:

1. **No cierres la app** (si es posible)
2. Toma un **screenshot** o **video** del problema
3. Anota exactamente qué estabas haciendo
4. Usa nuestro [Template de Reporte de Bugs](./template-bug-report.md)
5. Envía el reporte a: **[fitcourttech@gmail.com]**

## 💡 Sugerencias

Si tienes ideas para mejorar FitCourt:

- ¿Qué funcionalidad te gustaría ver?
- ¿Qué te resulta confuso o difícil de usar?
- ¿Qué te gusta más de la app?

Envía tus sugerencias a: **[fitcourttech@gmail.com]**

## 🎯 Prioridades de Prueba

### 🔴 Alta Prioridad

- Registro e inicio de sesión
- Visualización del mapa con Google Maps
- Marcadores de parques visibles
- Detalles de parques

### 🟡 Media Prioridad

- Edición de perfil
- Búsqueda de parques (si disponible)
- Filtros de parques (si disponible)

### 🟢 Baja Prioridad

- Animaciones y transiciones
- Soporte de orientación horizontal
- Rendimiento en dispositivos antiguos

---

¡Gracias por tomarte el tiempo de probar FitCourt! 🙏

Tu feedback es invaluable para mejorar la app. 🎉
