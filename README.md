# 🎵 El Rincón del Vinillo

[cite_start]Este repositorio contiene la documentación, diseño y código base para **El Rincón del Vinillo**, una tienda online dedicada a la venta de discos de vinilo[cite: 2]. 

[cite_start]Este proyecto fue desarrollado como parte de la Actividad Formativa del **Taller de Aplicaciones de Internet** (AIEP). [cite_start]Nuestro equipo se enfocó fuertemente en la fase de análisis de sistemas, abarcando el levantamiento de requerimientos, el diseño de la experiencia de usuario (Wireframes) y la estructuración de los datos[cite: 6, 11, 23].

## 👥 Equipo de Trabajo

* [cite_start]Aline Medina [cite: 4]
* [cite_start]René Muñoz [cite: 4]
* [cite_start]Felipe Aviño [cite: 4]
* [cite_start]Christián Escobar [cite: 4]

---

## 🔗 Enlaces del Proyecto

* [cite_start]**Despliegue en Vivo:** [El Rincón del Vinillo (Vercel)](https://el-rincon-del-vinillo.vercel.app/) [cite: 65, 66]
* [cite_start]**Repositorio:** [GitHub](https://github.com/ChristianMarquezE/El_Rincon_Del_Vinillo) [cite: 67, 68]
* [cite_start]**Diseño UX/UI:** [Wireframes Interactivos en Moqups](https://app.moqups.com/1Fd97Kl4smDhAihliqW58kwrSrVz6WAx/view/page/ad64222d5?ui=0&fit_width=1) [cite: 69]

---

## 📋 Levantamiento de Requerimientos

El análisis inicial del proyecto definió las bases para el desarrollo del catálogo dinámico. Destacamos los 3 Requisitos Funcionales (RF) principales modelados para el sistema:

1.  [cite_start]**RF-001 - Mostrar Catálogo:** El sistema debe consumir un archivo `discos.json` y renderizar dinámicamente las tarjetas de productos mostrando carátula, artista, álbum, género, precio y disponibilidad[cite: 35].
2.  [cite_start]**RF-002 - Búsqueda y Navegación:** Interfaz responsiva que permite al usuario buscar mediante texto y filtrar el catálogo completo según categorías musicales específicas (Jazz, Rock, Blues)[cite: 36].
3.  [cite_start]**RF-003 - Interfaz de Compra:** Proyección de un flujo electrónico que permita añadir productos a un carrito, procesar transacciones y retornar un token de confirmación[cite: 37].

[cite_start]*Para ver el listado completo de requisitos funcionales y no funcionales (como tiempos de carga y responsividad), revisar la documentación adjunta del proyecto[cite: 24, 30].*

---

## 📐 Diseño y Wireframes

[cite_start]Antes del desarrollo, se realizó un prototipado de alta fidelidad separando la interfaz en componentes lógicos[cite: 44]. La arquitectura visual se dividió en:

* [cite_start]`<Navbar>`: Navegación y barra de búsqueda centralizada[cite: 45].
* [cite_start]`<HeroBanner>`: Sección visual de bienvenida[cite: 46].
* [cite_start]`<FiltroGenero>`: Sistema de filtrado por género[cite: 47].
* [cite_start]`<CatalogoCarga>`: Indicadores visuales de estado (Loading/Error) para mejorar el feedback de las peticiones AJAX[cite: 49].
* [cite_start]`<TarjetaDisco>`: Componente atómico iterativo para cada producto[cite: 48].

[cite_start]El diseño contempla una estrategia *Mobile-First*, garantizando que la disposición de los filtros y la grilla de productos se adapte correctamente a pantallas pequeñas[cite: 57].

---

## 🛠️ Stack Tecnológico Base

Aunque nuestro enfoque principal fue la documentación y estructuración, el sistema resultante fue implementado utilizando un enfoque "Vanilla" y optimizado sin dependencias pesadas:

* [cite_start]**Frontend:** HTML5, CSS3, Bootstrap 5 (CDN)[cite: 62].
* [cite_start]**Reactividad:** Vue.js 3 (Composition API vía CDN)[cite: 62].
* [cite_start]**Asincronía:** Fetch API (Vanilla JS) para el consumo de datos AJAX.
* [cite_start]**Estructura de Datos:** JSON puro (`discos.json`) para simular la base de datos de 9 productos iniciales[cite: 17, 59].

---

## ⚙️ Uso Local

Si deseas correr este proyecto en tu entorno local para revisar la maquetación:

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/ChristianMarquezE/El_Rincon_Del_Vinillo.git](https://github.com/ChristianMarquezE/El_Rincon_Del_Vinillo.git)