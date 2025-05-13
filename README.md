# 🧹 App de Gestión de Tareas del Hogar con Recompensas

Este proyecto es una aplicación web desarrollada como Trabajo de Fin de Ciclo, cuyo objetivo es facilitar la organización de tareas domésticas dentro de una familia utilizando técnicas de **gamificación**. Los miembros de la familia reciben puntos al completar tareas, y semanalmente se les otorgan recompensas en base a su rendimiento.

---

## 🚀 Tecnologías utilizadas

### Backend:
- [Symfony 6](https://symfony.com/)
- PHP 8.2
- MySQL 8
- Doctrine ORM
- API Platform
- JWT Authentication

### Frontend:
- [Angular 17](https://angular.io/)
- TypeScript
- TailwindCSS
- RxJS

### Otros:
- Docker (para desarrollo y despliegue)
- Postman (para pruebas API)
- Git (control de versiones)

---

## 📦 Características principales

- Registro e inicio de sesión con autenticación JWT.
- Creación y unión a familias.
- Asignación de tareas a miembros de la familia.
- Sistema de puntos por tarea completada.
- Recompensas automáticas generadas semanalmente.
- Panel de usuario con ranking y estadísticas.
- Notificaciones tipo toast.
- Interfaz moderna, adaptativa y amigable.

---

## 🧩 Estructura del proyecto

```
/backend
  └── Symfony app (API RESTful)
/frontend
  └── Angular SPA (Single Page Application)
/docker
  └── Dockerfiles y configuración de entorno
```

---

## 📋 Requisitos previos

- PHP >= 8.1
- Node.js >= 18
- Composer
- Docker + Docker Compose
- Git

---

## ⚙️ Instalación rápida

### Backend (Symfony):

```bash
cd backend
composer install
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
```

### Frontend (Angular):

```bash
cd frontend
npm install
ng serve
```

### Con Docker:

```bash
docker-compose up --build
```

---

## 🧪 Pruebas

- PHPUnit para el backend.
- Jasmine + Karma para Angular.
- Pruebas funcionales con Postman.

---

## 📄 Licencia

Este proyecto es parte del Trabajo de Fin de Ciclo de Yosu Jiménez y se distribuye bajo la licencia MIT.

---

## 📬 Contacto

Si tienes sugerencias o deseas colaborar:

- 📧 Email: yosu1991@gmail.com
- 🔗 LinkedIn: www.linkedin.com/in/yosu91
