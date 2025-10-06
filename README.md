# 📊 Consolidación de Facturas Contables con IA

<div align="center">

```
   ╔══════════════════════════════════════╗
   ║     🧾  💳  📱  🤖  📈              ║
   ║                                      ║
   ║   FACTURAS + IA = AUTOMATIZACIÓN    ║
   ║                                      ║
   ╚══════════════════════════════════════╝
```

**Sistema inteligente de reconocimiento y consolidación de facturas**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Dart](https://img.shields.io/badge/Dart-3.0+-0175C2.svg)](https://dart.dev/)
[![AI](https://img.shields.io/badge/AI-Computer%20Vision-green.svg)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

---

## 👥 Equipo de Desarrollo

| Nombre | Correo | GitHub |
|--------|--------|--------|
| **José Emanuel Figueroa** | [josee.figueroas@utadeo.edu.co](mailto:josee.figueroas@utadeo.edu.co) | [@josefisa](#) |
| **Juan Esteban Correa** | [juane.correap@utadeo.edu.co](mailto:juane.correap@utadeo.edu.co) | [@juanescorreap](#) |
| **Esteban Alexander Arias** | [estebana.ariasg@utadeo.edu.co](mailto:estebana.ariasg@utadeo.edu.co) | [@EstebanArias](#) |

> 🎓 **Universidad Jorge Tadeo Lozano**  
> 📚 Programa: Ciencias de Datos - Modelado y Simulación  
> 🤖 Curso: Inteligencia Artificial  
> 📍 Bogotá D.C., Colombia | 2025

---

## 📋 Descripción del Proyecto

Este proyecto implementa un sistema inteligente para la **consolidación automática de facturas contables** utilizando técnicas de **Inteligencia Artificial** y **Visión por Computadora**. El sistema es capaz de:

- 🔍 Reconocer y extraer información de facturas escaneadas o fotografiadas
- 🧠 Procesar datos mediante algoritmos de Machine Learning
- 📊 Consolidar información contable de múltiples facturas
- 📱 Proporcionar una interfaz amigable desarrollada en Dart

---

## 🗂️ Estructura del Proyecto

```
📦 Consolidacion-Facturas-IA/
├── 📄 paper/
│   ├── consolidacion_facturas.tex      # Documento LaTeX del paper
│   └── consolidacion_facturas.pdf      # Versión PDF del paper
├── 🐍 src/
│   ├── python/
│   │   ├── image_recognition.py        # Reconocimiento de imágenes
│   │   ├── ocr_processing.py           # Procesamiento OCR
│   │   ├── data_extraction.py          # Extracción de datos
│   │   └── ml_models.py                # Modelos de ML
├── 🎯 interface/
│   ├── dart/
│   │   ├── main.dart                   # Aplicación principal
│   │   ├── ui/                         # Componentes de UI
│   │   └── services/                   # Servicios y API
├── 📊 data/
│   ├── samples/                        # Facturas de ejemplo
│   └── processed/                      # Datos procesados
├── 📚 docs/
│   └── documentacion.md                # Documentación adicional
├── 🧪 tests/
│   └── unit_tests.py                   # Pruebas unitarias
├── 📄 requirements.txt                 # Dependencias Python
├── 📄 pubspec.yaml                     # Dependencias Dart
└── 📖 README.md                        # Este archivo
```

---

## 🚀 Características Principales

### 🤖 Inteligencia Artificial
- **Reconocimiento OCR** mediante Tesseract y modelos personalizados
- **Clasificación de documentos** con redes neuronales
- **Extracción inteligente** de campos clave (fecha, monto, NIT, etc.)
- **Validación automática** de información contable

### 🐍 Backend en Python
- Procesamiento de imágenes con OpenCV
- Modelos de ML con TensorFlow/PyTorch
- API REST para integración
- Almacenamiento y gestión de datos

### 📱 Interfaz en Dart
- Aplicación multiplataforma (móvil/web)
- Diseño intuitivo y responsive
- Captura de facturas con cámara
- Visualización de resultados consolidados

---

## 🛠️ Instalación

### Requisitos Previos
- Python 3.8 o superior
- Dart SDK 3.0 o superior
- Flutter (para la interfaz)

### Instalación de Dependencias Python

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/consolidacion-facturas-ia.git
cd consolidacion-facturas-ia

# Crear entorno virtual
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt
```

### Instalación de Dependencias Dart

```bash
# Navegar a la carpeta de la interfaz
cd interface/dart

# Obtener dependencias
dart pub get

# O si usas Flutter
flutter pub get
```

---

## 💻 Uso

### Ejecutar el Sistema de Reconocimiento

```bash
# Activar entorno virtual
source venv/bin/activate

# Ejecutar reconocimiento de imagen
python src/python/image_recognition.py --input data/samples/factura.jpg
```

### Ejecutar la Interfaz

```bash
# Desde la carpeta interface/dart
flutter run
```

---

## 📄 Documentación Académica

El documento académico completo está disponible en:
- **LaTeX**: `paper/consolidacion_facturas.tex`
- **PDF**: `paper/consolidacion_facturas.pdf`

El paper incluye:
1. Introducción
2. Marco Teórico
3. Metodología
4. Resultados
5. Discusión
6. Conclusiones

---

## 🧪 Pruebas

```bash
# Ejecutar pruebas unitarias
python -m pytest tests/

# Ejecutar con cobertura
python -m pytest --cov=src tests/
```

---

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

🔒 Derechos de Autor y Uso Comercial
© 2025 José Emanuel Figueroa, Juan Esteban Correa, Esteban Alexander Arias
Todos los derechos reservados.
Este proyecto es de propiedad exclusiva de los autores y está protegido por las leyes de derechos de autor.
⚖️ Licencia Comercial

✅ Uso comercial permitido solo por los autores
❌ Prohibida la redistribución sin autorización expresa

- 📧 José Emanuel Figueroa: josee.figueroas@utadeo.edu.co
- 📧 Juan Esteban Correa: juane.correap@utadeo.edu.co
- 📧 Esteban Alexander Arias: estebana.ariasg@utadeo.edu.co

---

<div align="center">

### 🌟 ¡Gracias por tu interés en nuestro proyecto! 🌟

**Universidad Jorge Tadeo Lozano** | 2025

```
    ╔═══════════════════════════════╗
    ║  Desarrollado con ❤️ en 🇨🇴    ║
    ╚═══════════════════════════════╝
```

</div>
