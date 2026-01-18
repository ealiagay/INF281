# 🏛️ Proyecto Bicentenario - Plataforma de Gestión de Eventos

Este repositorio contiene la solución integral para la gestión, administración e inscripción de eventos masivos del Bicentenario. El proyecto está diseñado bajo una arquitectura moderna que separa la lógica de negocio del lado del servidor de la interfaz de usuario.

---

## 📂 Organización del Repositorio

Para facilitar el mantenimiento y el despliegue, el proyecto se divide en dos módulos principales:

### ⚙️ [Backend (API)](./backend)
Desarrollado con **NestJS** y **TypeScript**. Es el núcleo del sistema, encargado de la seguridad, la base de datos PostgreSQL (vía Prisma ORM) y la integración con servicios de IA.
* **Tecnologías:** NestJS, Prisma, PostgreSQL, JWT, SendGrid, Cloudinary.
* **Documentación:** Contiene diagramas de arquitectura, modelo de base de datos y especificaciones de la API.

### 🎨 [Frontend (Cliente)](./fronted)
Interfaz de usuario moderna desarrollada en **Next.js**. Permite a los usuarios finales e invitados interactuar con la plataforma de forma fluida.
* **Tecnologías:** Next.js, React, Tailwind CSS, Google Auth.
* **Funcionalidad:** Dashboard dinámico, autenticación social y visualización de eventos en tiempo real.

---

## 🚀 Cómo empezar

Al ser un proyecto monorepo (organizado en carpetas), cada módulo tiene sus propias dependencias e instrucciones específicas:

1.  **Configurar el Backend:** Sigue las instrucciones en [backend/README.md](./backend#⚡-inicio-rápido).
2.  **Configurar el Frontend:** Sigue las instrucciones en [fronted/README.md](./fronted#⚙️-configuración-y-ejecución).

---

### 👨‍💻 Información del Desarrollador

* **Desarrollador:** [Edwin Aliaga Yujra](https://www.linkedin.com/in/edwin-aliaga-yujra)
* **Institución:** Universidad Mayor de San Andrés (UMSA)
* **Materia:** Taller de Sistemas de Información (INF-281)
* **Contexto:** Plataforma integral "Bicentenario" para la gestión de eventos masivos, IA y despliegue.
