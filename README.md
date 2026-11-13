# 💎 Joyería Luxury - Frontend / Luxury Jewelry - Frontend

[![Live Demo](https://img.shields.io/badge/Live_Demo-Ver_Aplicación_en_Vivo-success?style=for-the-badge&logo=render)](https://joyeria-app-frontend.onrender.com) 
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()

[🇪🇸 Español](#-español) · [🇬🇧 English](#-english)

---

## 🇪🇸 Español

¡Bienvenido al repositorio del frontend de **Joyería**! Este es un sistema desacoplado, moderno y de alto rendimiento diseñado exclusivamente para ofrecer una experiencia de usuario premium en la visualización, personalización y cotización de piezas exclusivas de joyería.

🔗 **[Prueba la aplicación en vivo aquí](https://joyeria-app-frontend.onrender.com)**

---

### 💡 Nota de Arquitectura y Seguridad
El código fuente original de esta aplicación está resguardado en un repositorio privado por razones de confidencialidad y protección de propiedad intelectual. La ofuscación y minificación del bundle (código compilado) se implementan como una medida disuasoria habitual para dificultar la ingeniería inversa, pero no constituyen una garantía criptográfica absoluta. Las credenciales, secretos y la lógica sensible residen exclusivamente en el backend. 

### 🚀 Estado del Proyecto: 65% (Fase de Desarrollo y UI Core)
Actualmente, el sistema cuenta con los módulos esenciales de catálogo dinámico, carrito de compras en memoria y una interfaz de usuario completamente responsiva y modular. Se encuentra en desarrollo el 35% restante enfocado en la integración asíncrona con la API de Django (Backend), pasarela de pagos simulada y el panel de seguimiento de pedidos para clientes VIP.

### 🛠️ Tecnologías Utilizadas
* **Frontend Core:** HTML5, CSS3, JavaScript moderno (ES6+).
* **Librería Principal:** React (Estructura desacoplada y modular basada en componentes).
* **Sintaxis:** JSX (Extensión de sintaxis para renderizado ágil de interfaces).
* **Estilos y Diseño:** Tailwind CSS / Styled Components (Diseño moderno, utilitario y altamente estilizado).
* **Gestión de Estado y Ciclo de Vida:** React Hooks (`useState` para persistencia en memoria local y `useEffect` para el control de renderizado y peticiones).

### 💡 Características Principales
* **Catálogo de Joyas Dinámico:** Filtrado avanzado de piezas por categorías (Anillos, Cadenas, Pulseras,) y materiales (Oro, Plata, Piedras Preciosas).
* **Interfaz Ultra-Moderna:** Diseño visual minimalista, elegante y adaptativo (Mobile-First) optimizado para dispositivos móviles, tablets y escritorio.
* **Componentes Modulares:** Arquitectura limpia mediante componentes reutilizables (Tarjetas de producto, Navbar dinámico, Modales de visualización rápida).
* **Experiencia de Usuario Fluida:** Gestión de estado dinámico que simula la interacción de compra en tiempo real sin recargas de página.

### ⚙️ Arquitectura y Seguridad Local
* **Arquitectura Desacoplada:** El frontend opera de forma 100% independiente del backend, comunicándose únicamente mediante peticiones HTTP estructuradas.
* **Variables de Entorno:** Configuración gestionada mediante un archivo `.env` local para organizar las URLs de los endpoints. En aplicaciones frontend (React), todo lo que se incluye en el cliente es público, por lo que estas variables no deben usarse para almacenar secretos ni credenciales sensibles; esas credenciales se gestionan exclusivamente en el backend.
* **Control de Versiones:** Repositorio estructurado bajo Git con exclusión estricta de carpetas de dependencias (`node_modules/`) y credenciales mediante un archivo `.gitignore`.

### 🔒 Arquitectura y Repositorio del Backend
Por razones de seguridad, confidencialidad y protección de propiedad intelectual, el código fuente del servidor se encuentra alojado en un **repositorio privado**. El acceso está restringido exclusivamente al autor del proyecto y evaluadores externos autorizados.

El núcleo de servicios se encuentra **desplegado y en ejecución en entornos de producción en la nube (Render)** bajo una arquitectura de microservicios independiente.

Sin embargo, para fines de evaluación técnica, se detalla la pila tecnológica que compone el core del servidor:
* 🖥️ **Entorno de Ejecución & Hosting:** Python / Django REST Framework desplegado en la nube a través de Render.
* 🗄️ **Base de Datos:** PostgreSQL (Diseño relacional optimizado para la integridad de los datos).
* 🛡️ **Seguridad:** Implementación de variables de entorno protegidas y mitigación de brechas de exposición en producción.

### 👨‍💻 Autor
* **Creado por:** [code-with-infinite](https://github.com/code-with-infinite) (Desarrollador de Software)
* © Todos los derechos reservados.

<br>

---

## 🇬🇧 English

Welcome to the frontend repository for **Jewelry**! This is a decoupled, modern, and high-performance system designed exclusively to offer a premium user experience in the visualization, customization, and quotation of exclusive jewelry pieces.

🔗 **[Test the live application here](https://joyeria-app-frontend.onrender.com)**

---

### 💡 Architecture and Security Note
The original source code for this application is securely hosted in a private repository for confidentiality and intellectual property protection reasons. Bundle obfuscation and minification are implemented as a standard deterrent measure to make reverse engineering harder, but they do not constitute an absolute cryptographic guarantee. Credentials, secrets, and sensitive logic reside exclusively in the backend.

### 🚀 Project Status: 65% (Development and Core UI Phase)
Currently, the system features the essential modules for a dynamic catalog, an in-memory shopping cart, and a fully responsive and modular user interface. The remaining 35% is in development, focusing on asynchronous integration with the Django API (Backend), a simulated payment gateway, and the order tracking panel for VIP clients.

### 🛠️ Technologies Used
* **Core Frontend:** HTML5, CSS3, modern JavaScript (ES6+).
* **Main Library:** React (Decoupled and modular component-based structure).
* **Syntax:** JSX (Syntax extension for agile interface rendering).
* **Styles & Design:** Tailwind CSS / Styled Components (Modern, utility-first, and highly stylized design).
* **State Management & Lifecycle:** React Hooks (`useState` for local memory persistence and `useEffect` for render control and requests).

### 💡 Key Features
* **Dynamic Jewelry Catalog:** Advanced filtering of pieces by categories (Rings, Necklaces, Bracelets) and materials (Gold, Silver, Precious Stones).
* **Ultra-Modern Interface:** Minimalist, elegant, and adaptive visual design (Mobile-First) optimized for mobile devices, tablets, and desktop.
* **Modular Components:** Clean architecture using reusable components (Product cards, dynamic Navbar, Quick view modals).
* **Fluid User Experience:** Dynamic state management that simulates real-time purchase interaction without page reloads.

### ⚙️ Architecture and Local Security
* **Decoupled Architecture:** The frontend operates 100% independently of the backend, communicating solely through structured HTTP requests.
* **Environment Variables:** Managed configuration using a local `.env` file to organize API endpoint URLs. In frontend applications (React), everything included in the client is public, so these variables must not be used to store secrets or sensitive credentials; those credentials are managed exclusively in the backend.
* **Version Control:** Repository structured under Git with strict exclusion of dependency folders (`node_modules/`) and credentials via a `.gitignore` file.

### 🔒 Backend Architecture and Repository
For security, confidentiality, and intellectual property protection reasons, the server source code is hosted in a **private repository**. Access is strictly restricted to the project author and authorized external evaluators.

The core services are **deployed and running in cloud production environments (Render)** under an independent microservices architecture.

However, for technical evaluation purposes, the technology stack making up the server core is outlined below:
* 🖥️ **Runtime Environment & Hosting:** Python / Django REST Framework deployed to the cloud via Render.
* 🗄️ **Database:** PostgreSQL (Relational design optimized for data integrity).
* 🛡️ **Security:** Implementation of protected environment variables and mitigation of production exposure risks.

### 👨‍💻 Author
* **Created by:** [code-with-infinite](https://github.com/code-with-infinite) (Software Developer)
* © All rights reserved.