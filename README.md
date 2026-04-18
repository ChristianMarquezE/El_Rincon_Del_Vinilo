# 🎵 El Rincón del Vinillo

Este repositorio contiene la documentación, diseño y código base para **El Rincón del Vinillo**, una tienda online dedicada a la venta de discos de vinilo. 

Este proyecto fue desarrollado como parte de la Actividad Formativa del **Taller de Aplicaciones de Internet** (AIEP). Nuestro equipo se enfocó fuertemente en la fase de análisis de sistemas, abarcando el levantamiento de requerimientos, el diseño de la experiencia de usuario (Wireframes) y la estructuración de los datos.

## 👥 Equipo de Trabajo

* Aline Medina
* René Muñoz
* Felipe Aviño
* Christián Escobar

---

## 🔗 Enlaces del Proyecto

* **Despliegue en Vivo:** [El Rincón del Vinillo (Vercel)](https://el-rincon-del-vinillo.vercel.app/)
* **Repositorio:** [GitHub](https://github.com/ChristianMarquezE/El_Rincon_Del_Vinillo)
* **Diseño UX/UI:** [Wireframes Interactivos en Moqups](https://app.moqups.com/1Fd97Kl4smDhAihliqW58kwrSrVz6WAx/view/page/ad64222d5?ui=0&fit_width=1)

---

## 📋 Levantamiento de Requerimientos

El análisis inicial del proyecto definió las bases para el desarrollo del catálogo dinámico. Destacamos los 3 Requisitos Funcionales (RF) principales modelados para el sistema:

1.  **RF-001 - Mostrar Catálogo:** El sistema debe consumir un archivo `discos.json` y renderizar dinámicamente las tarjetas de productos mostrando carátula, artista, álbum, género, precio y disponibilidad.
2.  **RF-002 - Búsqueda y Navegación:** Interfaz responsiva que permite al usuario buscar mediante texto y filtrar el catálogo completo según categorías musicales específicas (Jazz, Rock, Blues).
3.  **RF-003 - Interfaz de Compra:** Proyección de un flujo electrónico que permita añadir productos a un carrito, procesar transacciones y retornar un token de confirmación.

*Para ver el listado completo de requisitos funcionales y no funcionales (como tiempos de carga y responsividad), revisar la documentación adjunta del proyecto.*

---

## 📐 Diseño y Wireframes

Antes del desarrollo, se realizó un prototipado de alta fidelidad separando la interfaz en componentes lógicos. La arquitectura visual se dividió en:

* `<Navbar>`: Navegación y barra de búsqueda centralizada.
* `<HeroBanner>`: Sección visual de bienvenida.
* `<FiltroGenero>`: Sistema de filtrado por género.
* `<CatalogoCarga>`: Indicadores visuales de estado (Loading/Error) para mejorar el feedback de las peticiones AJAX.
* `<TarjetaDisco>`: Componente atómico iterativo para cada producto.

El diseño contempla una estrategia *Mobile-First*, garantizando que la disposición de los filtros y la grilla de productos se adapte correctamente a pantallas pequeñas.

---

## 🛠️ Stack Tecnológico Base

Aunque nuestro enfoque principal fue la documentación y estructuración, el sistema resultante fue implementado utilizando un enfoque "Vanilla" y optimizado sin dependencias pesadas:

* **Frontend:** HTML5, CSS3, Bootstrap 5 (CDN).
* **Reactividad:** Vue.js 3 (Composition API vía CDN).
* **Asincronía:** Fetch API (Vanilla JS) para el consumo de datos AJAX.
* **Estructura de Datos:** JSON puro (`discos.json`) para simular la base de datos de 9 productos iniciales.

---

## ⚙️ Uso Local

Si deseas correr este proyecto en tu entorno local para revisar la maquetación:

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/ChristianMarquezE/El_Rincon_Del_Vinillo.git](https://github.com/ChristianMarquezE/El_Rincon_Del_Vinillo.git)gi