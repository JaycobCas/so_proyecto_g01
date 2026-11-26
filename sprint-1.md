## 1. VM gráfica (`g01-grafica` - Kubuntu)

Instalamos Kubuntu en VirtualBox con particionado manual (`/`, `swap` y `/home`), sin usar el particionado automático.

| Partición | Tamaño | Por qué |
|---|---|---|
| `/` | 13.67 GB | Contiene el sistema operativo completo, el entorno gráfico KDE Plasma y los paquetes instalados, dejando margen para actualizaciones. |
| `swap` | 2 GB | Memoria de intercambio equivalente a la RAM asignada a la VM para respaldar el sistema si se agota la memoria física. |
| `/home` | 9.33 GB | Separa los archivos personales, configuraciones y capturas del usuario respecto a los archivos del sistema. |

**Navegadores y editores instalados:** Firefox y Brave; Vim y nano.

**Comandos ejecutados:** `date`, `lsblk`, `df -h`, `cat /etc/fstab`

**Captura 1: Editor de particiones manual durante la instalación de Kubuntu**
<img width="512" height="288" alt="image" src="https://github.com/user-attachments/assets/cd43c9ed-9c66-4a82-b5f7-23c27194fda4" />


**Captura 2: Salida de `lsblk`, `df -h` y `cat /etc/fstab` con el prompt `nicolas@g01-grafica` y `date` visible**
<img width="512" height="320" alt="image" src="https://github.com/user-attachments/assets/e90ec29c-391d-4435-a4af-8dcf36531b7c" />


**Captura 3: Los dos navegadores y los dos editores abiertos en Kubuntu**
<img width="512" height="320" alt="image" src="https://github.com/user-attachments/assets/c55443bf-aa6a-458c-85aa-d6befd5b39eb" />

