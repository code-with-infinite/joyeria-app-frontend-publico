# 💎 Joyería Luxury - Frontend 

¡Bienvenido al repositorio del frontend de **Joyería**! Este es un sistema desacoplado, moderno y de alto rendimiento diseñado exclusivamente para ofrecer una experiencia de usuario premium en la visualización, personalización y cotización de piezas exclusivas de joyería.

---

## :rocket: Estado del Proyecto: 65% (Fase de Desarrollo y UI Core)
Actualmente, el sistema cuenta con los módulos esenciales de catálogo dinámico, carrito de compras en memoria y una interfaz de usuario completamente responsiva y modular. Se encuentra en desarrollo el 35% restante enfocado en la integración asíncrona con la API de Django (Backend), pasarela de pagos simulada y el panel de seguimiento de pedidos para clientes VIP.

## :hammer_and_wrench: Tecnologías Utilizadas
* **Frontend Core:** HTML5, CSS3, JavaScript moderno (ES6+).
* **Librería Principal:** React (Estructura desacoplada y modular basada en componentes).
* **Sintaxis:** JSX (Extensión de sintaxis para renderizado ágil de interfaces).
* **Estilos y Diseño:** Tailwind CSS / Styled Components (Diseño moderno, utilitario y altamente estilizado).
* **Gestión de Estado y Ciclo de Vida:** React Hooks (`useState` para persistencia en memoria local y `useEffect` para el control de renderizado y peticiones).

## :bulb: Características Principales
* **Catálogo de Joyas Dinámico:** Filtrado avanzado de piezas por categorías (Anillos, Cadenas, Pulseras,) y materiales (Oro, Plata, Piedras Preciosas).
* **Interfaz Ultra-Moderna:** Diseño visual minimalista, elegante y adaptativo (Mobile-First) optimizado para dispositivos móviles, tablets y escritorio.
* **Componentes Modulares:** Arquitectura limpia mediante componentes reutilizables (Tarjetas de producto, Navbar dinámico, Modales de visualización rápida).
* **Experiencia de Usuario Fluida:** Gestión de estado dinámico que simula la interacción de compra en tiempo real sin recargas de página.

## :gear: Arquitectura y Seguridad Local
* **Arquitectura Desacoplada:** El frontend opera de forma 100% independiente del backend, comunicándose únicamente mediante peticiones HTTP estructuradas.
* **Variables de Entorno:** Configuración protegida y aislada mediante un archivo `.env` local para mitigar la exposición de las URLs de los endpoints de la API de producción.
* **Control de Versiones:** Repositorio estructurado bajo Git con exclusión estricta de carpetas de dependencias (`node_modules/`) y credenciales mediante un archivo `.gitignore`.

## :link: Repositorio del Backend
Para revisar la lógica del servidor, la gestión de la base de datos Django y los endpoints que consume esta interfaz, accede al repositorio del servidor:
* ⚙️ **Backend (Django / API REST ):** [Enlace a repositorio de Django REST Framework ](https://github.com/code-with-infinite/joyeria-app-backend.git)

## :technologist: Autor
* **Creado por:** code-with-infinite (Desarrollador de Software)
