# Servidor FreeRADIUS en Docker para WiFi WPA2-Enterprise

Este proyecto levanta un servidor **FreeRADIUS** en Docker usando `docker compose`, pensado para autenticar clientes WiFi mediante WPA2/WPA3-Enterprise (EAP-PEAP, usuario/contraseña).

## Requisitos

### Generales

- Acceso a Internet para descargar imágenes de Docker.
- Un punto de acceso / router WiFi que soporte WPA2-Enterprise con servidor RADIUS externo.

### Linux

- Docker y Docker Compose v2 instalados (`docker compose` ya incluido en Docker moderno).[web:36][web:48]  
- Usuario en el grupo `docker` (opcional, para no usar `sudo`).

### Windows

- Windows 10/11.
- Docker Desktop instalado (incluye Docker Compose v2).[web:46][web:48]  
- WSL2 habilitado durante la instalación de Docker Desktop.[web:46]

Puedes verificar que Docker Compose está disponible con:

```bash
docker compose version
