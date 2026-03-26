
# Python Business Automation Scripts

Scripts en Python para automatizar tareas operativas y transformar datos de Excel.

## Objetivo
Desarrollar soluciones simples y útiles para reducir trabajo manual, acelerar el procesamiento de información y estandarizar salidas requeridas por distintas áreas.

## Contexto
Este repositorio reúne casos de automatización desarrollados en Python para resolver tareas repetitivas relacionadas con procesamiento de datos y transformación de archivos Excel en contextos administrativos y operativos.

## Casos incluidos
- Procesamiento de datos bancarios para el área de finanzas
- Transformación de marcaciones para gestión de personas
- Rotador de fondos institucionales

## Solución desarrollada
Se implementaron scripts orientados a:
- lectura de archivos Excel
- agrupación y consolidación de datos
- suma de valores por criterios definidos
- transformación de archivos a formatos requeridos por jefatura o áreas usuarias
- reducción de tareas manuales repetitivas
- carga de imagenes de servidor
- configuración de fondo de pantalla de windows

## Tecnologías utilizadas
- Python
- Pandas
- Excel

## Flujo general

```mermaid
flowchart LR
    A[Archivo Excel de entrada] --> B[Lectura y validacion de datos]
    B --> C[Procesamiento segun reglas de negocio]
    C --> D[Transformacion o agrupacion]
    D --> E[Archivo de salida]
    E --> F[Uso por area solicitante]
```

## Casos de automatización

### 1. Finanzas
Script para leer un archivo Excel con datos bancarios, agrupar la información por columnas específicas y calcular sumas de valores para facilitar el análisis y procesamiento del área.

### 2. Gestión de personas
Script para transformar un archivo Excel de marcaciones al formato solicitado por jefatura, estandarizando la salida y reduciendo trabajo manual.

## Documentación adicional
- [Contexto de negocio](docs/business-context.md)
- [Casos de uso](docs/use-cases.md)
- [Impacto y resultados](docs/impact-and-results.md)

## Consideraciones
Este repositorio presenta versiones adaptadas de casos reales, sin exponer datos sensibles ni información interna.
