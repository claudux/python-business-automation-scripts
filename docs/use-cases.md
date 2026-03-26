# Casos de uso

## 1. Finanzas
Se desarrolló un script para procesar un archivo Excel con datos bancarios. La solución permite leer la información, agrupar registros por columnas específicas y calcular sumas de valores, facilitando el trabajo analítico y operativo del área de finanzas.

## 2. Gestión de personas
Se desarrolló un script para transformar un archivo Excel de marcaciones al formato requerido por jefatura. La automatización permite estandarizar la estructura de salida y reducir la intervención manual en la preparación del archivo final.

## 3. Rotador de fondos institucionales
Se desarrolló un script para ejecutarse en segundo plano en equipos Windows, descargar imágenes desde un servidor y actualizar automáticamente el fondo de pantalla en formato carrusel. La solución permite mantener imágenes institucionales actualizadas de manera centralizada y sin intervención manual del usuario.

```mermaid
flowchart LR
    A[Script en segundo plano] --> B[Consulta imagenes en servidor]
    B --> C[Descarga archivos]
    C --> D[Actualiza fondo de pantalla en Windows]
    D --> E[Rotacion tipo carrusel]
    E --> F[Equipo mantiene fondos institucionales actualizados]
```
