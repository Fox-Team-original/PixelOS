# 🎨 PixelOS v0.1

Esta es la primera versión experimental de **PixelOS**, un sistema operativo que no usa imágenes tradicionales,  
sino que construye toda su interfaz con **píxeles coloreados**.

---

## 🚀 Novedades en v0.1
- Imagen básica funcional (`PixelOS.zip`).
- Interfaz inicial basada en píxeles coloreados.
- Compatible con máquinas virtuales (QEMU, VirtualBox).
- Soporte para ejecución en bare-metal (hardware real).

---

## 📥 Instalación

### 🔹 En máquina virtual
1. Descarga el archivo `PixelOS.zip` y descomprímelo.
2. Monta el archivo `.img` incluido en tu máquina virtual favorita.
3. ¡Explora PixelOS!

### 🔹 En bare-metal
1. Descomprime `PixelOS.zip` y obtén el archivo `.img`.
2. Graba la imagen en una memoria USB con **Rufus**, **balenaEtcher** o `dd` en Linux:
   ```bash
   sudo dd if=pixelos.img of=/dev/sdX bs=4M status=progress

