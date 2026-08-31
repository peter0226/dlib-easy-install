# Instalación de la librería dlib sin CMake

Este repositorio contiene los archivos **.whl** precompilados de **dlib** para Windows y Python 3.7 - 3.12 en arquitecturas x64, permitiendo su instalación sin necesidad de compilar desde el código fuente ni instalar **CMake**.

## Requisitos previos
- **Python** (versiones 3.7 a 3.13)
- **pip** actualizado:  
  ```sh
  python -m pip install --upgrade pip
  ```

## Instalación
1. Descarga el archivo **.whl** correspondiente a tu versión de Python desde este repositorio.
2. Abre una terminal en la ubicación donde descargaste el archivo.
3. Ejecuta el siguiente comando, reemplazando `nombre_del_archivo.whl` con el nombre del archivo descargado:
   ```sh
   pip install nombre_del_archivo.whl
   ```

---
**Licencia:** Este repositorio distribuye los binarios bajo la [Boost Software License 1.0](LICENSE).




---

## ⚠️ ¿Tuviste problemas con la instalación?

Si alguno de los comandos anteriores **falló**, no puedes importar alguna librería o estás utilizando **Windows con Python 3.13**, consulta la guía de solución de problemas antes de continuar.

Encontrarás soluciones para errores como:

- ❌ Problemas al instalar `dlib`.
- ❌ `No matching distribution found`.
- ❌ Errores con `face_recognition_models`.
- ❌ `No module named 'pkg_resources'`.
- ❌ `Please install face_recognition_models` aunque ya esté instalado.
- ❌ `Failed building wheel`.
- ❌ Problemas con el caché o rutas temporales de `pip`.
- ❌ Problemas de conexión con `pypi.org`.
- ❌ Librerías instaladas que Python no puede encontrar.
- ❌ Problemas de compatibilidad encontrados en Windows con Python 3.13.

### 🛠️ Guía de solución de problemas

👉 **[Consulta aquí la guía de solución de problemas en Windows](https://github.com/peter0226/face-recognition-opencv/blob/main/docs/troubleshooting-windows.md)**

> **Importante:** No realices todas las soluciones de la guía. Identifica primero el mensaje de error que aparece en tu equipo y sigue únicamente el apartado correspondiente.

---

