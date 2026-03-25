# 🚀 BuzzClick

**BuzzClick** es una plataforma web innovadora que conecta personas con ideas y personas con habilidades, facilitando la creación de proyectos colaborativos de forma dinámica e interactiva.

Inspirada en aplicaciones como Tinder, BuzzClick permite descubrir oportunidades mediante un sistema de *swipe* (deslizar), generando matches entre usuarios interesados en colaborar.

---

## 🚀 Características principales

* 🔐 Autenticación de usuarios (registro e inicio de sesión)
* 💡 Publicación de ideas y proyectos
* ❤️ Sistema de *match* tipo swipe (like/dislike)
* 💬 Chat en tiempo real
* 🧠 Recomendación básica de perfiles según intereses
* 📱 Diseño tipo aplicación móvil (responsive)
* 🔔 Notificaciones del navegador

---

## 🛠️ Tecnologías utilizadas

* **Frontend:**

  * HTML5
  * CSS3
  * JavaScript

* **Backend (BaaS):**

  * Supabase (Base de datos, autenticación y tiempo real)

* **Otros:**

  * API de notificaciones del navegador
  * Integración tipo app con Capacitor (opcional)

---

## 📂 Estructura del proyecto

```
buzzclick/
│
├── index.html   # Aplicación principal
└── README.md    # Documentación del proyecto
```

---

## ⚙️ Instalación y uso

1. Clona o descarga este repositorio
2. Abre el archivo `index.html` en tu navegador

---

## 🔑 Configuración de Supabase

1. Crea un proyecto en Supabase

2. Obtén:

   * Project URL
   * anon public key

3. Reemplaza en el código:

```javascript
const supabase = supabase.createClient(
  "TU_URL",
  "TU_API_KEY"
);
```

---

## 🗄️ Base de datos requerida

Crear las siguientes tablas en Supabase:

### 📊 ideas

* title (text)
* description (text)

### 💬 chat

* message (text)

### ❤️ matches

* idea (text)

---

## 🌐 Demo

Puedes ver la aplicac
