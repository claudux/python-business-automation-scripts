# Python Business Automation Scripts

Scripts en Python para automatizar tareas operativas, transformar datos de Excel y resolver necesidades prácticas en entornos TI.

## Objetivo
Desarrollar soluciones útiles y reutilizables para reducir trabajo manual, acelerar el procesamiento de información y automatizar tareas operativas en distintas áreas.

## Contexto
Este repositorio reúne casos de automatización desarrollados en Python para resolver tareas repetitivas relacionadas con procesamiento de datos, transformación de archivos Excel y automatización de configuraciones en equipos Windows.

## Casos incluidos
- Procesamiento de datos bancarios para el área de finanzas
- Transformación de marcaciones para gestión de personas
- Rotador de fondos institucionales para equipos Windows

## Solución desarrollada
Se implementaron scripts orientados a:
- lectura de archivos Excel
- agrupación y consolidación de datos
- suma de valores por criterios definidos
- transformación de archivos a formatos requeridos por jefatura o áreas usuarias
- automatización de configuraciones en equipos Windows
- reducción de tareas manuales repetitivas

## Tecnologías utilizadas
- Python
- Pandas
- Excel
- Windows
- Automatización de archivos y sistema

## Flujo general

```mermaid
flowchart LR
    A[Archivo o recurso de entrada] --> B[Lectura y validacion]
    B --> C[Procesamiento segun reglas de negocio]
    C --> D[Transformacion o automatizacion]
    D --> E[Resultado de salida]
    E --> F[Uso por area o equipo solicitante]
```

## Casos de automatización

### 1. Finanzas
Script para leer un archivo Excel con datos bancarios, agrupar la información por columnas específicas y calcular sumas de valores para facilitar el análisis y procesamiento del área.

```mermaid
flowchart LR
    A[Excel con datos bancarios] --> B[Lectura del archivo]
    B --> C[Agrupacion por columnas especificas]
    C --> D[Suma de valores]
    D --> E[Archivo o resultado consolidado]
    E --> F[Uso por area de Finanzas]
```

### 2. Gestión de personas
Script para transformar un archivo Excel de marcaciones al formato solicitado por jefatura, estandarizando la salida y reduciendo trabajo manual.

```mermaid
flowchart LR
    A[Excel de marcaciones] --> B[Lectura del archivo]
    B --> C[Transformacion de estructura]
    C --> D[Adaptacion al formato solicitado]
    D --> E[Archivo de salida estandarizado]
    E --> F[Uso por jefatura]
```

### 3. Rotador de fondos institucionales
Script ejecutado en segundo plano para descargar imágenes desde un servidor y configurar automáticamente el fondo de pantalla de Windows en modo carrusel, permitiendo mantener fondos institucionales actualizados en los equipos.

```mermaid
flowchart LR
    A[Script en segundo plano] --> B[Consulta imagenes en servidor]
    B --> C[Descarga archivos]
    C --> D[Actualiza fondo de pantalla en Windows]
    D --> E[Rotacion tipo carrusel]
    E --> F[Equipo mantiene fondos institucionales actualizados]
```

## Documentación adicional
- [Contexto de negocio](docs/business-context.md)
- [Casos de uso](docs/use-cases.md)
- [Impacto y resultados](docs/impact-and-results.md)


## Consideraciones
Este repositorio presenta versiones adaptadas de casos reales, sin exponer datos sensibles ni información interna.

## Contacto
Si quieres conocer más sobre este proyecto o mi trabajo en automatización y análisis de datos, puedes escribirme a:  
[claudio.duran.m@gmail.com](mailto:claudio.duran.m@gmail.com)
