##############################################################################################
En este repositorio se encuentran todos los archivos que se usó para el curso de Docker Avanzado. 
##############################################################################################
En cada carpeta esta un tema y la descripcion y resumen se puede ver en archivo de "Docto ..."
##############################################################################################

# 🐳 Curso de Docker Avanzado

## Contenido del Curso

### Fundamentos
- [Capas](/Capas) - Cómo funcionan las capas en Docker
- [Build Context](/BuildContext) - Optimización del contexto
- [Cache](/Cache) - Estrategias de caché

### Optimización
- [Multi-Stage](/MultiStage) - Builds multi-etapa
- [Distroless](/Distroless) - Imágenes mínimas
- [Dependencies](/Dependencies) - Gestión de dependencias

### Persistencia
- [Volumenes](/Volumenes) - Almacenamiento persistente

### Orquestación
- [Compose](/Compose) - Docker Compose
- [Stacks](/Stacks) - Docker Swarm Stacks

### CI/CD y Deployment
- [CI](/CI) - Integración continua
- [Despliegue en Azure](/Despliegue%20de%20Docker%20en%20Azure)

### Seguridad
- [DockerScan](/DockerScan) - Escaneo de vulnerabilidades
- [Usuarios](/Usuarios) - Usuarios no-root

### Utilidades
- [Prune](/Prune) - Limpieza de recursos
- [Scripts](/Scripts) - Scripts útiles

## Cómo usar este repositorio

Cada carpeta contiene ejemplos prácticos. Para ejecutarlos:
```bash
cd <carpeta>
docker build -t ejemplo .
docker run ejemplo
```

## Recursos adicionales
- [Documentación completa](./Docto%20docker)