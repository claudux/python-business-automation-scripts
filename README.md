# 🐍 Python Business Automation Scripts

> Colección de scripts desarrollados en Python para automatizar tareas operativas, transformar datos estructurados (Excel) y resolver necesidades prácticas en entornos TI y administrativos.

## 📝 Objetivo
Desarrollar soluciones informáticas útiles, modulares y reutilizables para reducir la carga de trabajo manual, acelerar el procesamiento de información crítica y automatizar tareas operativas repetitivas en distintas áreas de la institución.

## 📖 Contexto
Este repositorio reúne casos prácticos de automatización desarrollados íntegramente en Python. Los scripts fueron diseñados para resolver ineficiencias y tareas repetitivas relacionadas con el procesamiento masivo de datos, la transformación de archivos Excel para cumplir con formatos específicos y la automatización de configuraciones corporativas en equipos Windows.

## 💼 Casos Incluidos
- **Finanzas:** Procesamiento de datos y conciliación bancaria.
- **Gestión de Personas (RRHH):** Transformación de reportes de marcaciones biométricas.
- **Soporte TI:** Rotador automático de fondos de pantalla institucionales para equipos Windows.

## 💡 Solución Desarrollada
Se implementaron scripts orientados a:
- Lectura masiva y rápida de archivos Excel complejos.
- Agrupación, limpieza y consolidación de datos (ETL).
- Cálculo automático y suma de valores bajo criterios de negocio definidos.
- Transformación estructural de archivos para cumplir con los formatos exigidos por las jefaturas o áreas usuarias.
- Ejecución de comandos del sistema operativo para la automatización de configuraciones en equipos de la red Windows.
- Reducción drástica de horas-hombre en tareas manuales propensas a errores.

## 🛠️ Tecnologías Utilizadas
- **Lenguaje Base:** Python (Scripts `.py`).
- **Manipulación de Datos:** Librería `pandas`, `openpyxl`.
- **Interacción con Sistema:** Librería `os`, `ctypes`, `time`, automatización de archivos en red.
- **Entorno de Ejecución:** Windows / Tareas Programadas (Task Scheduler).

## 🔄 Flujo General de los Scripts

```mermaid
flowchart LR
    A["Archivo / Recurso de Entrada"] --> B["Lectura y Validación"]
    B --> C["Procesamiento (Reglas de Negocio)"]
    C --> D["Transformación / Automatización"]
    D --> E["Resultado (Salida)"]
    E --> F["Uso por Área Solicitante"]
```

## 🚀 Casos de Automatización Detallados

### 💰 1. Área de Finanzas (Procesamiento Bancario)
Script diseñado para leer archivos Excel pesados con datos bancarios crudos, agrupar la información según columnas clave y calcular las sumas de valores correspondientes. Facilita el análisis financiero y reduce los tiempos de cierre del área.

```mermaid
flowchart LR
    A["Excel con Datos Bancarios"] --> B["Lectura del Archivo (Pandas)"]
    B --> C["Agrupación por Columnas Clave"]
    C --> D["Suma y Consolidación"]
    D --> E["Archivo de Salida Procesado"]
    E --> F["Análisis en Finanzas"]
```

### 👥 2. Gestión de Personas (Control de Asistencia)
Script encargado de transformar la salida (export) en crudo de los sistemas de marcación biométrica a un formato estandarizado y legible, estructurando los datos exactamente como la jefatura los solicita.

```mermaid
flowchart LR
    A["Export Crudo de Marcaciones"] --> B["Lectura del Archivo"]
    B --> C["Transformación de Estructura"]
    C --> D["Adaptación al Formato Requerido"]
    D --> E["Excel Estandarizado (Output)"]
    E --> F["Revisión por Jefatura"]
```

### 🖥️ 3. Soporte TI (Rotador de Fondos Institucionales)
Script que se ejecuta de forma silenciosa (en segundo plano). Se conecta a un servidor local o repositorio en red, descarga las imágenes corporativas más recientes y modifica el fondo de pantalla de Windows (`Desktop Wallpaper`) en modo carrusel.

```mermaid
flowchart LR
    A["Script en Segundo Plano"] --> B["Consulta Imágenes en Servidor"]
    B --> C["Descarga de Archivos (.jpg/.png)"]
    C --> D["Actualización del Registro (Windows)"]
    D --> E["Rotación Tipo Carrusel"]
    E --> F["Equipos Corporativos Actualizados"]
```

## 📚 Documentación Adicional
- 🏢 [Contexto de negocio](docs/business-context.md)
- ⚙️ [Casos de uso y guías de ejecución](docs/use-cases.md)
- 📈 [Impacto en horas-hombre y resultados](docs/impact-and-results.md)

## ⚠️ Consideraciones
Este repositorio presenta **versiones adaptadas de los scripts reales**. Los datos de prueba incluidos son ficticios y las rutas de red a servidores o carpetas compartidas institucionales han sido modificadas para no exponer información sensible ni la topología de la red interna.

## 📫 Contacto
Si quieres conocer más sobre mis scripts de automatización con Python o conversar sobre cómo digitalizar procesos, contáctame:
- 📧 **Email:** [claudio.duran.m@gmail.com](mailto:claudio.duran.m@gmail.com)
- 💼 **LinkedIn:** [Claudio Durán Molina](https://www.linkedin.com/in/claudio-duran-molina-41580677)
