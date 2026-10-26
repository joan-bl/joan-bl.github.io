# 📅 iPad 2 Personal Organization & Job Search Web App

Aplicación web ligera de un solo archivo creada específicamente para ejecutarse en un **iPad 2 (A1395 / iOS 9.3.5 / 9.3.6)** montado en escritorio o pared.

Resuelve las limitaciones de los dispositivos antiguos de Apple (motor WebKit de Safari desactualizado, falta de soporte para la App Store actual) utilizando **JavaScript ES5 nativo** y HTML5/CSS estándar, con un diseño inspirado en el calendario de iCloud.

---

## 🎯 Propósito y Objetivos

1. **Búsqueda activa de trabajo:** Distribución estructurada de franjas de 2 horas por la mañana y 2 horas por la tarde.
2. **Hábito de Gimnasio Flexible (Mínimo 3 veces/semana):** Asignación interactiva de días sin la rigidez de un horario fijo.
3. **Evento Cultural / Inspiración Semanal:** Regla mensual que requiere al menos un evento o salida a la semana (exposiciones, búsquedas presenciales, eventos culturales) para recargar energías.
4. **Hobby y Bienestar:** Franjas reservadas de 1 hora por la mañana y 1 hora por la tarde para proyectos personales.
5. **Lista de Tareas Rápidas:** Lista de pendientes integrada con persistencia local.

---

## 🛠️ Contexto Técnico y Optimización para iPad 2

- **Dispositivo Objetivo:** iPad 2 (Chip Apple A5 32-bit, 512 MB RAM, Safari en iOS 9.3.5).
- **Arquitectura:** Archivo único (`index.html`) con HTML, CSS y JS integrados.
- **Compatibilidad Cero-Errores con iOS 9 (ES5):** 
  - Sin sintaxis moderna (`let`, `const`, funciones flecha `=>`, template literals o encadenamiento opcional `?.`).
  - Zonas táctiles adaptadas a un tamaño mínimo de 44px para una interacción fluida en pantalla táctil.
- **Persistencia:** Uso de `localStorage` de Safari para guardar la información sin necesidad de base de datos ni conexión a internet continua.

---

## 🚀 Cómo instalar en el iPad 2

1. Aloja este archivo `index.html` en **GitHub Pages**, **Netlify** o un servidor local.
2. Abre **Safari** en el iPad 2 y navega a la URL donde lo alojaste.
3. Toca el botón **Compartir** (el icono del cuadrado con la flecha hacia arriba).
4. Selecciona **"Añadir a la pantalla de inicio"**.
5. Ábrela directamente desde el icono de la pantalla de inicio para ejecutarla en modo pantalla completa sin barras de navegación.

---

## 📜 Licencia
MIT License - Libre para usar y modificar.