# Implementación de Docker Swarm

## Configuración del clúster
- Nodo Manager: docker-desktop (127.0.0.1)
- Servicios desplegados: web (nginx)

## Estructura de archivos
- `docker-compose.yml`: Configuración de servicios
- `html/`: Contenido estático
- `.github/workflows/deploy.yml`: Pipeline CI/CD

## Comandos útiles
- Ver servicios: `docker service ls`
- Ver logs: `docker service logs web`
- Actualizar: `docker service update --image nginx:latest web`