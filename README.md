# 👋 ¡Hola! Soy Garik

Soy **desarrollador web full-stack** de Sevilla (Andalucía/España). Trabajo a diario con **Java, Spring Boot, Angular y SQL**, y me muevo también con **TypeScript, Next.js, React, Node.js, Tailwind CSS, Docker y Git**.

Me interesa especialmente el ciclo completo: no solo escribir la aplicación, sino dejarla desplegada, monitorizada y con un proceso de releases que no dependa de la suerte.

---

## 💼 Experiencia

### Accenture — Desarrollador full-stack _(desde febrero de 2026)_
Desarrollo de aplicaciones empresariales con **Java / Spring Boot** en el backend, **Angular** en el frontend y **Oracle Database (SQL y PL/SQL)** como base de datos. Trabajo en equipo con control de versiones, revisiones de código y entregas por entornos.

---

## 🚀 Proyectos Destacados

### 🎸 Valkyria – Plataforma de Festival Musical → [valkyriafest.es](https://valkyriafest.es)
Proyecto personal más completo, en producción y mantenido con releases versionadas. Es una **demo** de un festival ficticio: los pagos usan el modo de pruebas de Stripe.

**Aplicación:** cartel de artistas y escenarios, venta de entradas y camping con control de stock, pagos con **Stripe**, generación de **entradas en PDF con código QR**, envío de correos transaccionales, autenticación propia y con **Google (OAuth 2.0)**, panel de administración e internacionalización español/inglés.

**Stack:** Angular 21 + Tailwind CSS 4 · Spring Boot 4 (Java 25) + MariaDB con migraciones Flyway · tests con JUnit y Testcontainers en el backend y Vitest en el frontend.

**Despliegue y CI/CD:** VPS propio en **Hetzner** con **Docker Compose** y **nginx** como proxy inverso con HTTPS. **GitHub Actions** ejecuta los tests en cada pull request y, al publicar una etiqueta de versión, construye las imágenes, las sube a **GHCR** y despliega en el servidor previa aprobación manual, con copia de seguridad de la base de datos antes de cada despliegue.

📦 Código: [valkyria-frontend](https://github.com/asa7ur/valkyria-frontend) · [valkyria-backend](https://github.com/asa7ur/valkyria-backend)

### 💻 Portfolio de Desarrollo → [asa7ur-coding.vercel.app](https://asa7ur-coding.vercel.app/)
Mi portfolio personal, donde reúno una selección de seis proyectos con su stack y su código. Hecho con **Next.js 16**, **React 19**, **TypeScript** y **Tailwind CSS 4**, con animaciones en **GSAP** y desplazamiento suave con **Lenis**. Diseño y maquetación propios, pensados para que el apartado visual pese tanto como el técnico.

📦 Código: [coding_portfolio](https://github.com/asa7ur/coding_portfolio)

### 🎨 Portfolio de Artista → [asa7ur-art-portfolio.vercel.app](https://asa7ur-art-portfolio.vercel.app/)
Página web personal para mostrar y vender mis retratos a carboncillo. Construida con **Next.js 16** (App Router), imágenes gestionadas desde **Cloudinary** y datos servidos desde **Neon** (PostgreSQL serverless).

📦 Código: [asa7ur_art_portfolio](https://github.com/asa7ur/asa7ur_art_portfolio)

### 🧺 Tender – ¿Tiendes fuera o dentro? → [tender-jet.vercel.app](https://tender-jet.vercel.app/)
App web con **Next.js 16** y **Tailwind CSS 4** que consulta el tiempo en tiempo real (vía **Open-Meteo**, sin API key) y te dice si es buen momento para tender la ropa fuera. Incluye geolocalización automática, búsqueda de ciudades, gráfico de temperatura por horas con probabilidad de lluvia y previsión para la mañana siguiente, útil si pones la lavadora por la noche.

📦 Código: [tender-app](https://github.com/asa7ur/tender-app)

---

## 🎓 Formación

- 📚 **Técnico Superior en Desarrollo de Aplicaciones Web** – IES Alixar (2024 – 2026)
- 🏆 Cursos online en freeCodeCamp, Google Learn y Udemy

---

## 📫 Contacto

- [LinkedIn](https://www.linkedin.com/in/garik-asatryan-077a07275/)
- [Instagram](https://www.instagram.com/asa7ur/)
- ✉️ asa7ur@proton.me

---

_Powered by espressos, teclas mecánicas y commits a medianoche._
