# Proyecto Final - Sistemas Operativos (2026-2)
**Universidad del Valle - Sede Yumbo - Grupo 01**

## Objetivo del proyecto
Implementar y administrar dos máquinas virtuales Linux en VirtualBox (`g01-grafica` con Kubuntu y `g01-consola` con Debian), gestionar usuarios, seguridad, procesos y servicios, publicar una imagen propia basada en Ubuntu en Docker Hub y desplegarla en un clúster de Kubernetes (Minikube), documentando todo el proceso en este sitio web[cite: 1, 10, 11].

## Integrantes y roles (Grupo 01)

| Integrante | Rol asignado | Responsabilidades principales |
|---|---|---|
| **Jaycob** | Coordinación, repositorio, sitio web y videos | Administración del repositorio público, configuración de GitHub Pages, estructuración del sitio web, integración de evidencias y entregas en campus. |
| **Nicolás** | Máquinas virtuales, red, seguridad y usuarios | Instalación de `g01-grafica` y `g01-consola` con particionado manual, configuración de red (NAT + Solo-anfitrión), SSH, instantáneas, usuarios, permisos y firewall. |
| **Alejandro** | Scripts, procesos, Docker y Kubernetes | Desarrollo de scripts en Bash, gestión de procesos (`zombi.py`), instalación de Docker Engine, creación de `Dockerfile` (Ubuntu) y despliegue en Minikube. |

## Distribuciones asignadas

* **VM Gráfica (`g01-grafica`):** Kubuntu[cite: 9, 11]
* **VM Consola (`g01-consola`):** Debian[cite: 9, 11]
* **Imagen base Dockerfile:** Ubuntu[cite: 11]

---

## Navegación del proyecto

* 📋 [Plan de trabajo del grupo](plan/plan-de-trabajo.md)
* 🔍 [Ficha de verificación de versiones](plan/ficha-version.md)
* 🚀 **[Sprint 1 · Montaje de VMs, Red, SSH e Instantáneas](sprint-1.md)**
* 🔗 [Repositorio oficial en GitHub](https://github.com/JaycobCas/so_proyecto_g01.git)
