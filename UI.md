# 🖥️ Interfaces de Usuario - Recicla Nuevo Chimbote

Este documento describe las interfaces principales de usuario (UI) para la aplicación móvil **Recicla Nuevo Chimbote**, orientadas tanto al **usuario reciclador (ciudadano)** como al **reciclador recolector**. Se especifican pantallas, componentes, y flujos clave.

---

## 👤 Usuario Ciudadano

### 1. Pantalla de Registro / Inicio de Sesión
- **Inputs:**
  - Nombres y Apellidos
  - Número de Teléfono (verificación por SMS)
  - Dirección
  - Contraseña
- **Botones:**
  - `Registrarse`
  - `Iniciar Sesión`
  - `¿Olvidaste tu contraseña?`

---

### 2. Dashboard Principal
- **Componentes:**
  - Resumen de Puntos
  - Acceso a Canje de Recompensas
  - Acceso al Mapa de Reciclaje
  - Acceso al Chatbot
- **Botones:**
  - `Ver Historial de Puntos`
  - `Ver Historial de Canjes`

---

### 3. Pantalla de Canje de Recompensas
- **Lista de Recompensas:**
  - Imagen del producto
  - Nombre del producto
  - Puntos requeridos
  - Botón `Canjear`
- **Modal de Confirmación:**
  - Detalles del canje
  - Confirmación del usuario

---

### 4. Mapa de Puntos de Reciclaje
- **Mapa Interactivo:**
  - Vista geolocalizada
  - Marcadores: puntos de reciclaje (tachos)
- **Componentes:**
  - Nombre del punto
  - Dirección
  - Tipo de reciclaje aceptado
  - Horarios de disponibilidad

---

### 5. Chatbot de Reciclaje
- **Interfaz de Chat:**
  - Entrada de texto del usuario
  - Respuestas automatizadas (tipos de reciclaje, cómo separar, ubicaciones)
- **Botones Rápidos:**
  - `¿Qué puedo reciclar?`
  - `¿Dónde reciclo plástico?`
  - `Ver puntos cercanos`

---

### 6. Perfil de Usuario
- **Datos Personales:**
  - Nombres y Apellidos
  - Teléfono
  - Dirección
- **Resumen:**
  - Puntos Acumulados
  - Nivel de Usuario (opcional, gamificación)
- **Acciones:**
  - `Editar Información`
  - `Cerrar Sesión`

---

## 🚛 Usuario Reciclador Recolector

### 1. Pantalla de Inicio de Sesión
- **Inputs:**
  - Usuario (número telefónico o ID)
  - Contraseña
- **Botones:**
  - `Iniciar Sesión`
  - `¿Olvidaste tu contraseña?`

---

### 2. Escaneo de QR
- **Interfaz de Cámara:**
  - Activación automática de la cámara
  - Cuadro delimitador de QR
- **Resultado del Escaneo:**
  - Nombre del usuario
  - Fecha y hora
  - Puntos a otorgar
  - Botón `Confirmar Registro`

---

### 3. Historial de Registros
- **Lista Cronológica:**
  - Usuario registrado
  - Fecha y hora
  - Cantidad de puntos entregados
- **Filtros:**
  - Por fecha
  - Por nombre de usuario

---

## 🧩 Consideraciones de Diseño

- **Framework UI Sugerido:** Jetpack Compose o XML Layouts en Android.
- **Estilo visual:** Minimalista, colores verdes y blancos, íconos amigables.
- **UX Principios:**
  - Navegación intuitiva
  - Confirmaciones claras en acciones sensibles
  - Feedback visual en escaneos y canjes

---

## ✅ Próximos Pasos
- Bocetado de pantallas (Wireframes)
- Prototipo en Figma
- Integración con backend (Firebase u otra solución BaaS)
