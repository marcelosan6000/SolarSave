# ☀️ SolarSave Pro - Calculadora de Independencia Energética

![Versión](https://img.shields.io/badge/Version-1.0.0-emerald)
![Licencia](https://img.shields.io/badge/License-MIT-blue)
![Hosting](https://img.shields.io/badge/Hosted_on-GitHub_Pages-black?logo=github)

**SolarSave Pro** es una herramienta web de alto rendimiento diseñada para ayudar a propietarios de viviendas y pequeñas empresas a estimar el ahorro real que obtendrían al instalar paneles solares, basándose en su ubicación geográfica exacta.

---

## 🚀 Características Principales

-   **📍 Geolocalización Inteligente:** Integra la API de Open-Meteo para detectar la radiación solar real (HSP) según la latitud y longitud del usuario.
-   **💰 Soporte Multimoneda:** Cálculos adaptados a USD, EUR, MXN y más, con precios de kWh configurables.
-   **📈 Visualización Dinámica:** Gráficos interactivos generados con `Chart.js` que muestran el punto de equilibrio (ROI) y la proyección de ahorro a 25 años.
-   **📱 Diseño "Clean Tech":** Interfaz moderna, minimalista y totalmente responsive construida con `Tailwind CSS`.
-   **🔒 Privacidad Primero:** Todos los cálculos se realizan en el lado del cliente (browser). Las coordenadas solo se usan para la consulta climática.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 / CSS3** (Tailwind CSS para el estilado)
* **JavaScript (ES6+)**
* **Chart.js** (Motores de visualización de datos)
* **Open-Meteo API** (Datos meteorológicos y de radiación)
* **Formspree** (Gestión de leads y contacto)

---

## 📦 Instalación y Despliegue

Este proyecto es una **Single Page Application (SPA)** y no requiere servidor (Backend). Para desplegarlo en GitHub Pages:

1.  Haz un **Fork** de este repositorio.
2.  Sube tu archivo `index.html`.
3.  Ve a `Settings > Pages` en tu repositorio de GitHub.
4.  Selecciona la rama `main` y guarda los cambios.
5.  ¡Tu calculadora estará viva en `https://tu-usuario.github.io/tu-repo/`!

---

## 📈 Estrategia de Monetización

Este proyecto está diseñado para ser monetizado de tres formas:
1.  **Marketing de Afiliación:** Secciones integradas para productos solares en Amazon/AliExpress.
2.  **Captación de Leads:** Formulario de contacto directo para enviar prospectos a instaladores locales.
3.  **Publicidad:** Espacios optimizados para Google AdSense.

---

## 📝 Notas Técnicas

El cálculo del Retorno de Inversión (ROI) utiliza la siguiente fórmula simplificada:
$$ROI = \frac{Costo\ de\ Instalación}{Ahorro\ Mensual \times 12}$$
*Asumiendo una eficiencia del sistema del 95% y una degradación mínima anual de los paneles.*

---

## 🤝 Contribuciones

¿Tienes alguna idea para mejorar el motor de cálculo o el diseño? ¡Las Pull Requests son bienvenidas!

1. Abre un **Issue** para discutir el cambio.
2. Haz un **Fork** del proyecto.
3. Crea tu rama de funciones (`git checkout -b feature/MejoraIncreible`).
4. Haz un **Commit** de tus cambios (`git commit -m 'Añadir nueva funcionalidad'`).
5. Haz un **Push** a la rama (`git push origin feature/MejoraIncreible`).
6. Abre un **Pull Request**.

---

Desarrollado con ❤️ para un futuro más sostenible.
