# Ficha Médica — Registro de Pacientes

Sistema web moderno y responsivo para la gestión y registro de fichas clínicas de pacientes. Desarrollado con HTML, CSS vainilla y JavaScript.

![Ficha Médica Preview](https://img.shields.io/badge/Estado-Activo-277E4D) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Vercel](https://img.shields.io/badge/Vercel-Ready-black?style=flat&logo=vercel)

---

## 🚀 Características Principales

- **Validación Avanzada de RUT Chileno:** Algoritmo de verificación por Módulo 11 con formateo automático (`12.345.678-9`).
- **Gestión Completa de Fichas (CRUD):** Creación, edición, consulta y eliminación de pacientes con modales de confirmación.
- **Búsqueda Dinámica:** Búsqueda en tiempo real por nombres, apellidos o RUT con contador de resultados.
- **Cálculo Automático de Edad:** Muestra la edad actual calculada según la fecha de nacimiento ingresada.
- **Exportación e Importación de Datos (JSON):** Genera copias de respaldo locales para resguardar la información o migrar a otros dispositivos.
- **Persistencia Local:** Los datos se guardan en el `localStorage` del navegador.
- **Diseño Moderno & Elegante:** Interfaz clínica en tonos esmeralda/salvia, 100% responsiva para computadores y dispositivos móviles.

---

## 🛠️ Estructura del Formulario

La ficha médica recopila la siguiente información:
- **RUT:** (Formato chileno validado)
- **Estado Civil:** Soltero/a, Casado/a, Conviviente civil, Divorciado/a, Viudo/a
- **Nombres y Apellidos**
- **Dirección y Ciudad**
- **Teléfono y Email**
- **Fecha de Nacimiento:** (Con indicador de edad)
- **Comentarios u Observaciones Clínicas:** (Hasta 500 caracteres)

---

## 💻 Instalación y Uso Local

No requiere compilación ni dependencias externas:

1. **Abrir directamente:**
   Doble clic en `index.html` en tu navegador.
2. **Servidor local (opcional):**
   ```bash
   npx serve .
   ```

---

## ☁️ Despliegue en Vercel (Recomendado)

El proyecto es **100% compatible con Vercel** de forma nativa (Zero Configuration):

1. Ve a [Vercel](https://vercel.com/) e inicia sesión.
2. Haz clic en **"Add New Project"** > **"Project"**.
3. Selecciona tu repositorio de GitHub `crist38/ficha-clinica`.
4. Haz clic en **"Deploy"**.

Cada vez que hagas un `git push` a la rama `main`, Vercel actualizará el sitio automáticamente.

---

## 🌐 Despliegue en GitHub Pages

1. Ve a los ajustes del repositorio en GitHub: **Settings > Pages**.
2. En **Build and deployment > Branch**, selecciona `main` y `/ (root)`.
3. Haz clic en **Save**.
