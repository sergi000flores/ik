![image alt](https://github.com/sergi000flores/ik/blob/546a6c1a0ae98f3604a695712a37e1154afc3ff0/Captura%20de%20pantalla%202026-06-09%20072723.png)
# File Explorer

Aplicación desarrollada en C# Windows Forms que integra múltiples herramientas para la gestión de archivos, edición de documentos, validación de datos, manejo multimedia y migración de información hacia bases de datos.

## Características principales

### Explorador de archivos

* Navegación entre carpetas y unidades
* Búsqueda de archivos y directorios
* Copiar, mover, renombrar y eliminar archivos
* Compresión y extracción ZIP
* Barra lateral de navegación rápida

### Multimedia

* Reproductor de música con:

  * Letras sincronizadas
  * Ecualizador de 10 bandas
  * Edición de metadatos
  * Portadas automáticas
* Reproductor de video
* Grabador de audio
* Cámara web integrada

### Edición de documentos

* Editor de archivos TXT, JSON, XML, CSV y Excel
* Editor de documentos Word y PDF
* Editor y visor de imágenes
* Conversión entre formatos

### Validación y procesamiento de datos

* Validación automática de registros
* Corrección de errores
* Exportación de datos
* Generación de gráficas
* Migración hacia SQL Server y MariaDB

---

# Tecnologías utilizadas

## Lenguaje

* C#

## Framework

* Windows Forms
* .NET

## Librerías principales

* NAudio
* TagLib#
* ClosedXML
* Newtonsoft.Json
* OpenCvSharp
* SharpAvi
* PdfPig
* DocumentFormat.OpenXml
* MySqlConnector

---

# Módulos del sistema

## Main Form

Ventana principal del explorador de archivos y centro de control del sistema.

## Audio Recorder Form

Grabador de audio compatible con WAV y MP3.

## Camera Form

Captura de fotografías y grabación de video mediante cámara web.

## Email Form

Envío de correos electrónicos con archivos adjuntos.

## Excel Editor Form

Editor de hojas de cálculo con soporte para fórmulas.

## File Editor Form

Editor y visor universal de archivos y documentos.

## Image Viewer Form

Visor y editor de imágenes con soporte EXIF y GPS.

## Migration Form

Migración de datos hacia SQL Server y MariaDB.

## Music Player Form

Reproductor musical con ecualizador, letras y edición de metadatos.

## Video Player Form

Reproductor multimedia integrado utilizando Windows Media Player COM API.

## Word Pdf Editor Form

Editor de documentos Word y PDF.

---

# Funciones destacadas

* Reproducción multimedia
* Letras sincronizadas
* Ecualizador de audio
* Edición de metadatos MP3
* Conversión de archivos
* Validación de datos
* Migración a bases de datos
* Manejo de imágenes con GPS
* Exportación a:

  * CSV
  * JSON
  * XML
  * Markdown
  * Excel
  * PDF

---

# APIs y servicios utilizados

* Spotify API
* LRCLib API
* OpenStreetMap
* Google Maps
* SMTP
* Windows Media Player COM API

---

# Instalación

## Clonar repositorio

```bash
git clone https://github.com/usuario/file-explorer.git
```

## Abrir proyecto

Abrir la solución en Visual Studio.

## Restaurar paquetes NuGet

```bash
Restore NuGet Packages
```

## Ejecutar proyecto

```bash
F5
```

---

# Requisitos

* Windows 10/11
* .NET Framework
* Visual Studio
* Cámara y micrófono opcionales

---

# Capturas

Agregar imágenes del sistema dentro de una carpeta `/images`.

Ejemplo:

```md
![Main Window](images/main.png)
```

---

# Estructura del proyecto

```text
FileExplorer/
│
├── Forms/
├── Helpers/
├── Controls/
├── Models/
├── Resources/
├── README.md
└── FileExplorer.sln
```

---

# Autor

Sergio Flores

---

# Licencia

Proyecto educativo desarrollado con fines académicos.
