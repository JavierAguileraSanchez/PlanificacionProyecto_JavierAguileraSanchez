# Trabajo de Fin de Grado (TFG)
## Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)

---

## Título del proyecto
**Aplicación móvil multiplataforma para la gestión de reservas en centros deportivos**

---

## Datos del alumno
- **Nombre del alumno:** Javier Aguilera Sánchez
- **Centro educativo:** IES Rafael Alberti
- **Ciclo formativo:** Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)
- **Curso académico:** 2025 / 2026
- **Módulo:** Proyecto de Desarrollo de Aplicaciones Multiplataforma

---

## Descripción del proyecto
Este Trabajo de Fin de Grado consiste en el desarrollo de una aplicación móvil multiplataforma usando **Ionic Framework y Angular**, cuyo objetivo es facilitar la gestión de reservas en centros deportivos.

La aplicación permitirá a los usuarios registrarse e iniciar sesión, consultar las instalaciones disponibles y realizar reservas de pistas o actividades deportivas. También podrán consultar sus reservas y cancelarlas si lo necesitan.

Con este proyecto se pretende poner en práctica los conocimientos adquiridos durante el ciclo formativo, aplicando una forma de trabajo similar a la que se utiliza en un entorno profesional y utilizando tecnologías actuales.

---

## Objetivos

### Objetivo general
Desarrollar una aplicación multiplataforma que permita gestionar reservas deportivas de forma sencilla y cómoda para el usuario.

### Objetivos específicos
- Diseñar una interfaz clara y fácil de usar.
- Implementar un sistema de registro e inicio de sesión.
- Permitir a los usuarios crear, consultar y cancelar reservas.
- Organizar el proyecto siguiendo una arquitectura modular.
- Utilizar servicios externos mediante una API REST o Firebase.
- Controlar el acceso a la aplicación mediante autenticación.
- Documentar correctamente el desarrollo del proyecto.

---

## Tecnologías utilizadas

### Frontend
- Ionic Framework
- Angular
- TypeScript
- HTML5
- SCSS

### Backend (propuesto)
- Firebase Authentication
- Firebase Firestore


---

### Otras herramientas
- Git y GitHub
- Visual Studio Code
- Figma (para el diseño de la interfaz)

---

## Funcionalidades principales
- Registro de usuarios
- Inicio de sesión
- Consulta de instalaciones deportivas
- Gestión de reservas
- Cancelación de reservas
- Gestión del perfil de usuario
- Control de acceso mediante guards

---

## Estructura del proyecto
```text
src/
 ├── app/
 │   ├── core/
 │   │   ├── services/
 │   │   ├── guards/
 │   ├── pages/
 │   ├── models/
 │   └── app-routing.module.ts
 ├── assets/
 └── environments/
