# Plan de trabajo · Grupo 01 (Yumbo)

## ¿Para qué sirve este archivo?

Define las responsabilidades de cada integrante del Grupo 01 (Sede Yumbo). Sirve como guía para la revisión de commits individuales en cada sprint y para la sustentación final, donde cada integrante explicará la parte asignada. Si se realiza algún cambio de roles durante el proyecto, se actualizará este archivo mediante un commit.

## Integrantes y partes

| Integrante | Rol | Qué hace | Archivos o carpeta propios |
|---|---|---|---|
| Jaycob Castañeda| Coordinación, repositorio, sitio web y videos | Administra el repositorio público, verifica los commits, configura GitHub Pages (`_config.yml`), estructura el sitio web, integra los videos y entrega el enlace en el campus | `README.md`, `_config.yml`, `index.md`, `plan/`, `comparativa.md` |
| Nicolás Mosos | Máquinas virtuales, red, seguridad y usuarios | Instala `g01-grafica` (Kubuntu) y `g01-consola` (Debian) con particionado manual, configura red (NAT + Solo-anfitrión), SSH, instantáneas, usuarios, grupo `proyecto`, permisos `/srv/proyecto`, `sudo` y firewall | `sprint-1.md`, `sprint-2-seguridad.md`, carpeta `capturas-vm/` |
| Alejandro Minotta| Scripts, procesos, Docker y Kubernetes | Desarrolla el script gráfico (`.desktop`) y el de consola en Bash, gestiona procesos (`zombi.py`), instala Docker Engine, crea el `Dockerfile` (Ubuntu), publica en Docker Hub y despliega en Minikube (Kubernetes) | `scripts/`, `docker/`, `k8s/`, `sprint-2-servicios.md`, `sprint-3.md` |

## Fechas de los sprints 

| Sprint | Cierre (Yumbo) | Qué entregamos |
|---|---|---|
| 0 · Arranque | viernes 20 de noviembre, 11:55 p. m. | Repositorio público con la carpeta `plan` (`plan-de-trabajo.md` y `ficha-version.md`) |
| 1 · Montaje | viernes 27 de noviembre, 11:55 p. m. | Dos VMs (`g01-grafica` y `g01-consola`), red, SSH e instantánea `instalacion-limpia` |
| 2 · Servicios | viernes 11 de diciembre, 11:55 p. m. | Usuarios, firewall, scripts Bash, procesos (`zombi.py`) y Docker Engine instalado |
| 3 · Cierre | viernes 18 de diciembre, 11:55 p. m. | Imagen propia en Docker Hub, despliegue en Kubernetes y sitio web completo |
| Sustentación | sábado 19 de diciembre (en clase) | Presentación del grupo (sitio web) y prueba individual con las dos VMs encendidas |

## Reglas del grupo

- Cada integrante edita únicamente sus propios archivos o carpetas. Si alguien necesita modificar un archivo de otro compañero, avisa previamente por el grupo de WhatsApp.
- Cada integrante realiza al menos 2 commits propios en los sprints 1, 2 y 3, usando mensajes descriptivos que indiquen qué cambió (ejemplo: *"agrego capturas de particionado manual en Debian"*). No se usarán mensajes genéricos como *"update"* o *"cambios"*.
- Los videos de cada sprint (3, 4 y 5 minutos máximo) se graban antes del cierre con el código de verificación del sprint visible en terminal junto con el comando `date`.
- Si algún integrante tiene dificultades con su parte, lo comunica al grupo con anticipación para buscar solución.
