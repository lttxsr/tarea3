# Implementación de Docker Swarm con CI/CD

## Configuración del Entorno

### Requisitos
- Docker Desktop (Windows/Mac) o Docker Engine (Linux)
- Docker Compose
- Cuenta en Docker Hub
- Cuenta en GitHub

### Estructura del Proyecto
- `docker-compose.yml`: Define los servicios, redes y volúmenes
- `Dockerfile`: Construcción de la imagen personalizada
- `.github/workflows/deploy.yml`: Pipeline de CI/CD
- `html/`: Contenido estático para el servidor web

## Configuración de Docker Swarm

1. Inicializar el swarm:
```bash
docker swarm init