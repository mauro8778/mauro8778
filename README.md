# 5tart Travel API ✈️🌍

API RESTful desarrollada con **NestJS**, **TypeScript** y **PostgreSQL** para la gestión integral de agencias de viajes, cotización automatizada de paquetes turísticos, reservas y administración de usuarios.

---

## 🛠️ Stack Tecnológico

- **Entorno & Lenguaje:** Node.js, TypeScript (ES6+)
- **Framework Backend:** NestJS
- **Base de Datos:** PostgreSQL
- **ORM:** TypeORM
- **Autenticación & Seguridad:** JWT, Passport.js, Google OAuth 2.0 y control de acceso basado en roles (RBAC)
- **Comunicación en Tiempo Real:** WebSockets (Socket.IO)
- **Servicios Cloud & Multimedia:** Cloudinary (almacenamiento de imágenes)
- **Mailing Transaccional:** Nodemailer (confirmaciones de reserva y notificaciones)
- **Geolocalización:** API de Geocoding para destinos y rutas turísticas
- **Contenedores:** Docker & Docker Compose

---

## ✨ Características Principales

- **Gestión de Paquetes Turísticos:** Creación, edición, filtrado avanzado y consulta de paquetes de viaje y destinos.
- **Cotizador Automatizado:** Cálculo dinámico de costos de viaje, estadías y servicios adicionales para agencias y clientes.
- **Control de Roles (RBAC):** Permisos diferenciados para tres niveles de usuarios:
  - `Admin`: Supervisión global de la plataforma, agencias y transacciones.
  - `Agency`: Publicación y gestión de paquetes propios, cotizaciones y reservas.
  - `Customer`: Búsqueda de destinos, solicitud de presupuestos y gestión de reservas.
- **Autenticación Híbrida:** Registro tradicional con credenciales cifradas (bcrypt) e inicio de sesión federado con cuentas de Google.
- **Notificaciones en Tiempo Real:** Emisión de alertas instantáneas ante nuevas cotizaciones o cambios de estado de reservas vía WebSockets.
- **Carga de Archivos:** Subida optimizada de fotografías de hoteles y paquetes hacia Cloudinary.

---

## 📋 Requisitos Previos

- [Node.js](https://nodejs.org/) (versión 18.x o superior)
- [PostgreSQL](https://www.postgresql.org/) (versión 14.x o superior) o [Docker Desktop](https://www.docker.com/)
- Gestor de paquetes `npm`

---

## 🚀 Instalación y Puesta en Marcha

### 1. Clonar el repositorio
```bash
git clone [https://github.com/mauro8778/5tart-travel.git](https://github.com/mauro8778/5tart-travel.git)
cd 5tart-travel
