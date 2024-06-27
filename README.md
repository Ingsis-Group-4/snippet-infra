# Repositorio de Infraestructura - snippet-infra

Este repositorio es responsable de unificar la creación de contenedores para todos los microservicios en un solo lugar. Proporciona una forma centralizada de gestionar y orquestar todos los servicios necesarios para nuestra aplicación.

## Microservicios

Los microservicios incluidos en este repositorio son:

- `snippet-permission`: Este servicio se encarga de gestionar los permisos de los usuarios.
- `snippet-manager`: Este servicio se encarga de gestionar los snippets.
- `snippet-runner`: Este servicio se encarga de ejecutar los snippets.

## Cómo usar

Para construir y levantar todos los servicios, ejecuta el siguiente comando en la raíz del repositorio:

```bash
docker-compose up --build