# 🎨 PixelOS

Bienvenido a **PixelOS**, un sistema operativo experimental que no usa imágenes tradicionales,  
sino que construye toda su interfaz con **píxeles coloreados**. Minimalista, rápido y diferente.

---

## 🚀 Características principales
- 🖼️ **Interfaz única**: todo se renderiza con píxeles coloreados.
- ⚡ **Ligero y veloz**: pensado para ser más rápido que sistemas convencionales.
- 🧩 **Experimental**: ideal para aprender cómo funcionan los OS desde cero.
- 💻 **Versátil**: puede ejecutarse en **máquinas virtuales** (QEMU, VirtualBox) o directamente en **bare-metal**.

---

## 📥 Instalación

### 🔹 En máquina virtual
1. Descarga la última versión desde la sección de [Releases](https://github.com/Fox-Team-original/PixelOS/releases).
2. Monta el archivo `.img` en tu máquina virtual favorita.
3. ¡Explora PixelOS y su mundo de píxeles!

### 🔹 En bare-metal (hardware real)
1. Descarga la imagen `.img` desde [Releases](https://github.com/Fox-Team-original/PixelOS/releases).
2. Graba la imagen en una memoria USB con herramientas como **Rufus**, **balenaEtcher** o `dd` en Linux:
   ```bash
   sudo dd if=pixelos.img of=/dev/sdX bs=4M status=progress
