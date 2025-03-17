# Proyecto_SyncBetter

**Servidor autoalojado con múltiples servicios: Nextcloud, Forgejo, Bitwarden, y más**

Este repositorio documenta el proyecto **SyncBetter**, un servidor autoalojado que integra varios servicios críticos para la gestión de archivos, repositorios de código y contraseñas. El proyecto se ha desarrollado y perfeccionado a lo largo de un año, añadiendo progresivamente diferentes configuraciones y mejoras. Este proyecto es uno de los más completos que realicé hasta ahora.

## Descripción General

- **Objetivo**  
  Ofrecer un entorno autogestionado que incluya:
  - **Nextcloud** para sincronización y almacenamiento de archivos personales.
  - **Forgejo** para alojar repositorios Git de forma privada (y como alternativa a GitHub).
  - **Bitwarden** para la gestión segura de contraseñas.
  - Otros servicios adicionales (Portainer, Adminer, WireGuard, etc.).
  
- **Sistema Operativo**  
  Ubuntu Server 22.04 LTS.

## Estado Actual

Este proyecto está **en constante evolución**. Se han documentado las configuraciones clave (discos, RAID/LVM, firewall, DNS, contenedores Docker, etc.), pero **todavía hay apartados en desarrollo**.

## Documentación

- [Documento Principal](https://github.com/mgion24/Proyecto_SyncBetter/blob/main/SyncBetter/Proyecto_SyncBetter.pdf)

### Contenido Destacado

- **Gestión de Almacenamiento**  
  Explicación de la estructura RAID1, LVM y discos externos para copias de seguridad.
- **Servicios**  
  - **Nextcloud**: Configuración manual con Apache, Redis, APCu, 2FA, etc.  
  - **Forgejo**: Forja de repositorios Git, con proxy inverso y planes futuros para CI/CD.  
  - **Bitwarden**: Despliegue en Docker, seguridad 2FA, integraciones y backups.  
- **DNS (Local y Público)**  
  Uso de Bind9 y Cloudflare, implementación de DynDNS.  
- **Seguridad y Firewall**  
  Integración de iptables, UFW, scripts personalizados y automatizaciones.

## Contribuciones

Cualquier sugerencia o mejora es bienvenida.

---

