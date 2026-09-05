# Editor-launcherPvPGN

Herramienta de utilidades para el cliente de mapas de Warcraft III sobre PvPGN.                              
![Python](https://img.shields.io/badge/powered%20by-Python-3776AB)
![JSON](https://img.shields.io/badge/config-JSON-lightgrey)
![REG](https://img.shields.io/badge/Regedit-Config-orange)

## Contenido
- **`Release/w3g.exe`** — Cliente/loader principal.
- **`Release/zlib1.dll`** — Dependencia de compresión requerida por el ejecutable.
- **`patch_ip.exe`** — Utilidad con interfaz gráfica para editar el dominio/IP del servidor embebido en un ejecutable compilado, sin necesidad de recompilar el código fuente.

## Uso de patch_ip.exe

1. Ejecutar `patch_ip.exe`.
2. Click en **Buscar...** y seleccionar el `w3g.exe` que traer este repositorio modificado.
3. La herramienta escanea el binario y muestra automáticamente el dominio/IP detectado (solo lectura).
4. Escribir el nuevo dominio/IP en el campo correspondiente.
   - Debe tener **igual o menor cantidad de caracteres** que el original (el exceso no cabe sin corromper el binario).
5. Click en **Parchear ejecutable**.
6. Se genera automáticamente un backup (`.bak`) del archivo original antes de aplicar el cambio.

## Archivos que se agregaran directamente a la carpeta:

- w3g.exe (fixeado con nueva ip/dominio)
- zlib1.dll

<img width="398" height="295" alt="image" src="https://github.com/user-attachments/assets/3676dd46-79d0-4430-92bc-47f7b20469e2" />

