# 🌍 Geoportal - Danoninoun

![Supabase](https://img.shields.io/badge/Backend-Supabase_PostGIS-green?logo=supabase)
![Leaflet](https://img.shields.io/badge/Frontend-LeafletJS-blue?logo=leaflet)
![Status](https://img.shields.io/badge/Style-Neon_Glassmorphism-fuchsia)

Un visor de mapas interactivo y moderno que conecta directamente con una base de datos **Supabase (PostGIS)** para renderizar puntos de interés en tiempo real.

El proyecto destaca por su interfaz "Dark Mode" con efectos de neón, animaciones cinemáticas de cámara y marcadores pulsantes.

## ✨ Características Principales

* **🗺️ Cartografía Interactiva:** Integración de **Leaflet.js** con mapas base de alto contraste (*CartoDB Dark Matter*).
* **📡 Conexión en Tiempo Real:** Fetch de datos asíncrono desde la tabla `places_view` en Supabase.
* **🎥 Animación Cinemática (FlyTo):** El mapa inicia con una vista global y realiza un vuelo suave automático hacia las coordenadas de Málaga tras la carga.
* **🎨 UI/UX Cyberpunk:**
    * Tarjetas flotantes con efecto **Glassmorphism** (desenfoque y transparencias).
    * Marcadores personalizados con animación de "latido" (CSS Keyframes pulse).
    * Tipografía moderna **Outfit**.

## 🚀 Instalación y Uso

Al ser una aplicación *Vanilla JS* sin dependencias de compilación (como Webpack o Vite), su despliegue es inmediato.

### 1. Clonar el repositorio
```bash
git clone [https://github.com/tu-usuario/geoportal-supabase.git](https://github.com/tu-usuario/geoportal-supabase.git)
```

### 2. Ejecutar
Simplemente abre el archivo index.html en tu navegador web favorito (Chrome, Firefox, Edge).

### 3. Configuración
El proyecto ya incluye las credenciales públicas (anon key) configuradas en el código para conectar con el backend de Supabase.
Pero en caso de que quieras usar tu propia base de datos con otras localizaciones tendrias que cambiar las siguientes líneas por tus APIs de Supabase:
```JavaScript
const supabaseUrl = "[https://oxughwuqwusiddtfawzi.supabase.co](https://oxughwuqwusiddtfawzi.supabase.co)"; 
const supabaseKey = "eyJhbGciOiJIUzI1NiIsIn..."; // Public Anon Key
```
