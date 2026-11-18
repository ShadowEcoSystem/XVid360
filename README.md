# XVid360

Cliente homebrew para Xbox 360 (RGH), escrito en C con [XSDK](https://github.com/xenosworks/xsdk).

**Estado:** Alpha 0.1, en desarrollo.

## Objetivo
- Interfaz oscura estilo dashboard de Xbox 360 / Metro a 1280x720
- Navegación con el mando
- Catálogo, búsqueda y miniaturas (pendiente)

## Compilación
Se compila con CMake y XSDK mediante GitHub Actions. El resultado es `XVid360.xex`.

## Pruebas
Se prueban en una consola física con RGH. El programa escribe `XVid360.log` junto al `.xex`.
