# Tuleap Docker Setup

Esta configuración permite instalar rápidamente **Tuleap Community Edition** usando Docker y Docker Compose.

Tuleap es una plataforma completa para la gestión del ciclo de vida de aplicaciones (ALM) que incluye:
- Gestión de proyectos
- Seguimiento de issues y bugs  
- Repositorios Git/SVN
- Wiki y documentación
- Foros y comunicación
- Integración continua
- Y mucho más

## 🚀 Instalación Rápida

### Prerequisitos

- [Docker](https://docs.docker.com/get-docker/) instalado
- [Docker Compose](https://docs.docker.com/compose/install/) instalado
- 4GB de RAM disponibles mínimo

### Pasos

1. **Clonar este repositorio:**
```bash
git clone https://github.com/tu-usuario/tuleap-docker-setup.git
cd tuleap-docker-setup

2. Copiar el archivo de ejemplo
cp .env.example .env

# Editar las credenciales (usar solo caracteres alfanuméricos)
nano .env

3. Iniciar Tuleap
docker-compose up -d

4. Ver progreso de instalación
docker-compose logs -f tuleap


5. Acceder a Tuleap:
URL: http://localhost
Usuario: admin
Contraseña: La que configuraste en SITE_ADMINISTRATOR_PASSWORD
