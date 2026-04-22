# Tale of Recognition - KeyStudios

<p align="center">
	<img src="https://img.shields.io/badge/Team-KeyStudios-2563eb?style=for-the-badge" alt="Development team badge" />
	<img src="https://img.shields.io/badge/Project-Tale%20of%20Recognition-1f6feb?style=for-the-badge" alt="Project badge" />
	<img src="https://img.shields.io/badge/Type-Multirepo%20Game%20Platform-0f766e?style=for-the-badge" alt="Multirepo badge" />
	<img src="https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge" alt="License badge" />
</p>

## Misión

 crea experiencias de juego digitales innovadoras, accesibles y colaborativas, uniendo diseño, tecnología y trabajo en equipo para ofrecer una plataforma sólida e intuitiva en tiempo real.

<p align="center">
	<img
		src="../assets/banner.jpeg"
		alt="A Tale Of Recognition Banner"
		width="78%"
		style="max-width: 840px; border-radius: 16px; display: block; margin: 0 auto; box-shadow: 0 10px 30px rgba(15, 23, 42, 0.18);"
	>
</p>

## ✨ Overview

A Tale of Recognition es una plataforma software inspirada en Dixit y Dixit Stella que digitaliza la experiencia de juego y la adapta a partidas en línea con soporte web y móvil.

## 🔎 What it includes

- Partidas en tiempo real con soporte web y móvil.
- Backend modular con API REST y comunicación por sockets.
- Infraestructura separada para despliegue y orquestación.
- Cliente móvil desarrollado con Expo.
- Utilidad específica para probar sockets con tokens.

## 👥 Equipo de Desarrollo

### Frontend (Web)
- **Eduardo Sánchez** - [@EduSS282](https://github.com/EduSS282)
- **Samuel Gallego** - [@SamuGallego](https://github.com/SamuGallego)

### Mobile
- **Sergio Guerra** - [@868307](https://github.com/868307)
- **Mohamed Rayen** - [@RayanUnizar](https://github.com/RayanUnizar)

### Backend
- **Violeta Veras** - [@FSPPX](https://github.com/FSPPX)
- **Athanasios Usero** - [@Azzal-e](https://github.com/Azzal-e)
- **Hugo López Navarro** - [@hachelpez13](https://github.com/hachelpez13)
- **Elías Zabaleta** - [@EliZaba-dev](https://github.com/EliZaba-dev)

## 🏗️ Repositories

| Repository | Purpose |
| --- | --- |
| `infraestructura-proyecto` | Orquestación y despliegue con Docker Compose para backend y frontend web. |
| `Backend` | API y lógica del servidor. |
| `Frontend` | Frontend web. |
| `Movil` | Aplicación móvil. |
| `socket-tester` | Utilidad para probar sockets del backend con tokens. |
| `.github` | Documentación y configuración compartida de la organización. |

## 🛠️ Tech Stack

### Frontend
<p>
	<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
	<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
</p>

### Mobile
<p>
	<img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
	<img src="https://img.shields.io/badge/React%20Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native" />
	<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
</p>

### Backend
<p>
	<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
	<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
	<img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.io" />
	<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
	<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
	<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
</p>

### Infraestructura
<p>
	<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
	<img src="https://img.shields.io/badge/Docker%20Compose-0052CC?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose" />
</p>

## 🧩 Architecture at a glance

- Frontend web en Angular consumiendo API REST y WebSockets.
- Backend en Node.js con Express y Socket.io.
- Persistencia en PostgreSQL.
- Estado en tiempo real y caching con Redis.
- Despliegue y entorno local gestionados desde `infraestructura-proyecto`.

## 🚀 Instalación y Configuración

La instalación y el arranque del entorno se gestionan desde el repositorio `infraestructura-proyecto`, donde está documentado el flujo completo de despliegue local y las variables necesarias. Consulta el README de ese repositorio para levantar la infraestructura común del proyecto.

## 📦 Quick links

- [Repositorio de infraestructura](https://github.com/Unizar-30226-2026-11/infraestructura-proyecto)
- [Frontend web](https://github.com/Unizar-30226-2026-11/Frontend)
- [Backend](https://github.com/Unizar-30226-2026-11/Backend)
- [Móvil](https://github.com/Unizar-30226-2026-11/Movil)
- [Utilidad de sockets](https://github.com/Unizar-30226-2026-11/socket-tester)

## 📝 Convenciones de Desarrollo

### Git Workflow
- `main`: rama principal de producción
- `develop`: rama de desarrollo
- `feature/*`: ramas para nuevas funcionalidades
- `bugfix/*`: ramas para corrección de errores

### Commits
Seguir el formato: `tipo(alcance): descripción`
- `feat`: nueva funcionalidad
- `fix`: corrección de error
- `docs`: documentación
- `style`: formato, espacios en blanco
- `refactor`: refactorización de código
- `test`: añadir o modificar tests
- `chore`: tareas de mantenimiento

## 📚 Documentación

La documentación específica de cada parte del sistema se mantiene en el README de cada repositorio y en la sección Wiki de la organización cuando procede.

## 🤝 Cómo Contribuir

1. Hacer un fork del repositorio correspondiente.
2. Crear una rama de trabajo a partir de `develop` o de la rama indicada en ese repositorio.
3. Realizar los cambios y comprobar que encajan con las convenciones del proyecto.
4. Abrir un Pull Request hacia el repositorio original.
5. Esperar revisión del equipo responsable.
