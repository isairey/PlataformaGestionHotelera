<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3176/3176363.png" />

# 🏨 FrontDesk PMS

### Plataforma de gestión hotelera y administración de propiedades 🚀

<p align="center">
  <b>FrontDesk PMS</b> es un sistema avanzado de administración de propiedades (PMS) diseñado para hoteles, alojamientos y servicios de renta, permitiendo gestionar habitaciones, reservas, usuarios y operaciones administrativas desde una plataforma moderna y centralizada.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PropertyManagement-PMS-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-FuelPHP-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/Bootstrap-SBAdmin2-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**FrontDesk PMS** es un sistema profesional de administración de propiedades diseñado para hoteles, hostales, alojamientos y servicios de alquiler, facilitando la automatización de reservas, administración de habitaciones y control operativo desde una interfaz moderna.

La plataforma fue desarrollada para:

- 🏨 Gestionar propiedades
- 🛏️ Administrar habitaciones
- 📅 Controlar reservas
- 👥 Gestionar usuarios
- 💳 Supervisar pagos
- 📊 Administrar operaciones
- 🔐 Gestionar accesos
- 🌐 Optimizar servicios de alojamiento

---

# ✨ Características

## 🏨 Gestión de propiedades

- 🏢 Registro de instalaciones
- 🛏️ Gestión de habitaciones
- 📍 Administración de ubicaciones
- 📋 Configuración de tarifas
- ⚙️ Gestión de servicios

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- ⚡ Administración centralizada
- 📊 Control de accesos

---

## 📅 Sistema de reservas

- 📆 Reservas de habitaciones
- 💳 Gestión de pagos
- 📋 Historial de reservas
- ⚡ Confirmaciones rápidas
- 🛎️ Administración hotelera

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 🏨 Gestión de propiedades
- 👥 Administración de usuarios
- 📅 Supervisión de reservas
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 🏨 Property Module

Este módulo administra todas las propiedades y alojamientos registrados dentro del sistema.

### Funcionalidades:

- ➕ Registro de propiedades
- 🛏️ Administración de habitaciones
- 📋 Configuración de tarifas
- ⚙️ Gestión de servicios
- 📍 Administración de instalaciones

---

## 👤 Customer Module

Este módulo es utilizado por clientes y huéspedes.

### Funcionalidades:

- 🔐 Inicio de sesión
- 📅 Reservar habitaciones
- 💳 Gestión de pagos
- 📄 Consultar historial
- 🛎️ Solicitar servicios

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🏨 Supervisión de propiedades
- 📊 Dashboard administrativo
- 📅 Administración de reservas
- 🔐 Gestión general

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js,jquery" />
</p>

- HTML5
- CSS3
- Bootstrap 3
- JavaScript
- jQuery 3.4.1
- SBAdmin2 Template

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP 7.3
- FuelPHP 1.8.2
- Arquitectura MVC
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL 5.7
- Relaciones SQL
- Persistencia de datos
- Gestión hotelera

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- Composer
- Nginx

---

# 📂 Estructura del proyecto

```bash
PlataformaGestionHotelera/
│
├── fuel/                     # Núcleo FuelPHP
├── public/                   # Recursos públicos
├── fuel/app/                 # Configuración y lógica
├── fuel/packages/            # Paquetes adicionales
├── public/images/            # Recursos gráficos
├── public/assets/            # Recursos frontend
├── migrations/               # Migraciones SQL
├── nginx.conf                # Configuración Nginx
├── composer.json             # Dependencias PHP
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 7.3+
- MySQL 5.7
- Composer
- Nginx
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaGestionHotelera.git
```

---

## 2️⃣ Acceder al proyecto

```bash
cd PlataformaGestionHotelera
```

---

## 3️⃣ Instalar dependencias

```bash
composer install
```

---

## 4️⃣ Ejecutar instalación

```bash
php oil refine install
```

---

## 5️⃣ Configurar base de datos

Editar:

```bash
fuel/app/config/db.php
```

Agregar:

```php
'connection' => array(
    'hostname' => 'localhost',
    'database' => 'frontdesk',
    'username' => 'root',
    'password' => '',
),
```

---

## 6️⃣ Ejecutar migraciones

```bash
php oil refine migrate --packages=auth

php oil refine migrate:current

php oil refine migrate
```

---

## 7️⃣ Ejecutar proyecto

Abrir:

```bash
http://localhost/PlataformaGestionHotelera/
```

---

# 📊 Funcionalidades principales

## 🏨 Gestión hotelera

- Administración de habitaciones
- Gestión de tarifas
- Configuración de servicios
- Control de disponibilidad

---

## 👥 Administración de usuarios

- Registro y autenticación
- Gestión de perfiles
- Roles administrativos
- Control de accesos

---

## 📅 Gestión de reservas

- Reservas en tiempo real
- Gestión de pagos
- Historial de reservas
- Confirmaciones automáticas

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 📊 Dashboard principal
![Dashboard](./public/images/fd-dashboard.png)

### 🏨 Gestión de propiedades
![Properties](https://images.unsplash.com/photo-1566073771259-6a8506099945?q=80&w=1200&auto=format&fit=crop)

### 🛏️ Gestión de habitaciones
![Rooms](https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?q=80&w=1200&auto=format&fit=crop)

### 📅 Sistema de reservas
![Booking](https://images.unsplash.com/photo-1522798514-97ceb8c4f1c8?q=80&w=1200&auto=format&fit=crop)

### 👥 Administración de usuarios
![Users](https://images.unsplash.com/photo-1521737604893-d14cc237f11d?q=80&w=1200&auto=format&fit=crop)

### 💳 Gestión de pagos
![Payments](https://images.unsplash.com/photo-1556740749-887f6717d7e4?q=80&w=1200&auto=format&fit=crop)

### ⚙️ Configuración del sistema
![Settings](https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=1200&auto=format&fit=crop)

### 📈 Panel administrativo
![Admin](https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=1200&auto=format&fit=crop)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web con FuelPHP
- Gestión hotelera
- Bases de datos relacionales
- CRUD administrativos
- Sistemas de autenticación
- Arquitectura MVC
- Automatización de reservas

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 🤖 Automatización inteligente
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real
- 📊 Reportes avanzados
- 💳 Integración de pagos online

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por plataformas inmobiliarias, sistemas administrativos y arquitectura web moderna 🚀

</div>
---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT orientado a la administración hotelera y gestión de propiedades.

---

<div align="center">

### 🏨 FrontDesk PMS — administración inteligente para hoteles y alojamientos 🚀

</div>
