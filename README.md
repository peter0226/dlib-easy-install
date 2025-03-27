# Instalación de la librería dlib sin CMake

Este repositorio contiene los archivos **.whl** precompilados de **dlib** para Windows y Python 3.7 - 3.12 en arquitecturas x64, permitiendo su instalación sin necesidad de compilar desde el código fuente ni instalar **CMake**.

## Requisitos previos
- **Python** (versiones 3.7 a 3.12)
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


