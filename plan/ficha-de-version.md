# Ficha de versión · Kubuntu (VM gráfica)
| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Kubuntu 26.04 LTS - Plasma 6 Fecha de lanzamiento: 23 de Abril, 2026 | https://kubuntu.org/download/ |
| Hasta cuándo recibe actualizaciones de seguridad | Recibe actualizaciones de seguridad y mantenimiento hasta Abril de 2029 | (https://kubuntu.org/download/) |
| Requisitos de hardware y si funciona en VirtualBox | Kubuntu en su página oficial no posee un apartado que indique los requerimientos del sistemas. Como es un "sabor de Ubuntu" usaremos los mismos requerimientos del sistema que pide Ubuntu. Ubuntu Desktop 26.04 LTS requires a 2 GHz dual-core processor or better, a minimum of 6 GB RAM and 25 GB of free storage space for a comfortable experience. Kubuntu funciona en VirtualBox| https://documentation.ubuntu.com/release-notes/26.04/#requirements-and-compatibility |
| ¿El instalador permite particionado manual? | Sí, Kubuntu soporta partición manual | [Particion Manual Kubuntu](https://kfocus.org/wf/reinstall.html?srsltid=AYCX9vJzVVVO6dTNr5Fwx8omWFDa8oWKW4Lv7Y_F5kepU6uPEbYUoBgd#bkm_part_disks) |
| Guía oficial para instalar Docker Engine en esa familia | Docker soporta Ubuntu 26.04, pero aclara que no soporta oficialmente las distribuciones derivadas, como Linux Mint. Kubuntu es un sabor oficial, no una vderivada, así que la guía de Ubuntu tambien aplica aquí. | https://docs.docker.com/engine/install/ubuntu/ |
| Imagen base del Dockerfile para esa versión | Kubuntu no tiene imagen Docker propia, así que usa Ubuntu. La imagen oficial es ubuntu:26.04. | https://hub.docker.com/_/ubuntu |


# Ficha de versión · Debian (VM de consola)
| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Debian 13.7 Fecha de lanzamiento: 12 de septiembre, 2026 | https://www.debian.org/releases/stable/ |
| Hasta cuándo recibe actualizaciones de seguridad | Recibe actualizaciones de seguridad y mantenimiento hasta el 9 de agosto, 2028 | https://www.debian.org/releases/stable/ |
| Requisitos de hardware y si funciona en VirtualBox | Lista un Pentium 4, sistema de 1GHz como el mínimo recomendado para un sistema de escritorio. Sin escritorio: RAM 512MB y Almacenamiento 4GB, con escritorio: RAM 1GB y almacenamiento 10GB. El os funciona en VIrtualBox | https://www.debian.org/releases/trixie/amd64/ch03s04.en.html |
| ¿El instalador permite particionado manual? | Sí. El instalador ofrece particionado guiado, o “Manual” si no quieres autoparticionar. | https://d-i.debian.org/manual/en.i386/apas03.html | 
| Guía oficial para instalar Docker Engine en esa familia | Docker soporta Debian 13 (trixie) 12 y 11. | https://docs.docker.com/engine/install/debian/ |
| Imagen base del Dockerfile para esa versión | La imagen oficial existe en Docker y soporta la versión instalada | https://hub.docker.com/_/debian |


# Ficha de versión · Rocky Linux (Imagen base de Dockerfile)
| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Rocky Linux 10 “Red Quartz”. Salió el 11 de junio de 2025. La documentación oficial ya lista la 10.3 como versión actual. | https://docs.rockylinux.org/releases/ |
| Hasta cuándo recibe actualizaciones de seguridad | Recibe soporte general con fecha limite del 31 de Mayo | https://docs.rockylinux.org/releases/ |
| Requisitos de hardware y si funciona en VirtualBox | CPU 	1 GHz 64-bit (AVX-capable x86_64-v3) or equivalent for ARM/POWER/Z/RISC-V. RAM 	1 GB (2 GB for GUI). Disk Space 	10 GB (20 GB+ recommended; 40 GB+ for GUI). Network 	Ethernet or wireless adapter. Display 	1024×768 capable (only for GUI). Media Access 	USB or DVD-ROM. Firmware 	UEFI/BIOS (UEFI recommended); Secure Boot optional. El OS funciona en VirtualBox  | https://docs.rockylinux.org/10/ja/guides/minimum_hardware_requirements/ |
| ¿El instalador permite particionado manual? | Sí, con la opción “Custom” del instalador. La guía oficial de Rocky solo muestra el modo automático, así que para lo manual usé la guía de Tecmint, que explica elegir Custom en “Installation Destination” | https://www.tecmint.com/install-rocky-linux/ | 
| Guía oficial para instalar Docker Engine en esa familia | La guía oficial de Rocky usa el repositorio RHEL de Docker: dnf config-manager --add-repo https://download.docker.com/linux/rhel/docker-ce.repo, y luego instala docker-ce, containerd.io, etc. | https://docs.rockylinux.org/gemstones/containers/docker/ |
| Imagen base del Dockerfile para esa versión | La imagen oficial existe en Docker y soporta la versión instalada | hub.docker.com/r/rockylinux/rockylinux |
