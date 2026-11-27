
# Kernix OS

Sistema operativo portable x86_64 de diagnóstico y compatibilidad de hardware.

## Descargar y ejecutar (sin compilar)

1. Ve a la sección **Releases** (a la derecha) y descarga **`kernix.iso`**.
2. Elige una opción:
   - **En PC real (USB):** Graba `kernix.iso` en una memoria USB con **Rufus** (eligiendo **Modo Imagen DD**) o **balenaEtcher**. Si tu equipo tiene **Secure Boot** activo, desactívalo en BIOS/UEFI y arranca desde la USB (`F9`, `F12`, `F8` o `Esc`).
   - **En Máquina Virtual:** Abre **VirtualBox** o **VMware**, crea una VM de 64 bits (512 MB - 1 GB RAM) y carga `kernix.iso` como CD/DVD.

> Kernix OS se ejecuta solo en memoria RAM y no modifica ni borra tu disco duro.
