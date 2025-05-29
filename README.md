# SUNrise 4.2.5
Registro Integrado para el Sistema Electrónico de SUNAT

![Logo SUNrise]([assets/sunrise.png](https://github.com/hL-piero/SUNrise-Release/blob/main/sunrise.png))


Aplicación para procesar documentos electrónicos (XML, ZIP, PDF) de SUNAT, con generación de reportes.

## 📥 Descarga e Instalación

1. **Descarga los archivos divididos**:
   - [SUNrise.zip.001](enlace_a_001)
   - [SUNrise.zip.002](enlace_a_002)
   - [SUNrise.zip.003](enlace_a_003)

2. **Une los archivos**:
   - Usa [7-Zip](https://www.7-zip.org/) o similar.
   - Coloca los 3 archivos en la misma carpeta.
   - Extrae `SUNrise.zip.001` (se unirán automáticamente).

3. **Contenido del ZIP**:
SUNrise/
├── SUNrise 4.2.5.exe # Ejecutable principal
├── assets/ # Recursos visuales (íconos, imágenes)
├── LICENSE.txt # Licencias de terceros (LGPL 3.0 + MIT)
└── NOTICE.txt # Información legal adicional


## 🚀 Uso Básico
1. Ejecuta `SUNrise.exe` (Windows 10/11).
2. Arrastra archivos (XML/ZIP/PDF) a la ventana o usa el botón "+ Añadir archivos".
3. Genera reportes con el botón inferior.

![Captura de pantalla](assets/sunrise_ui.png) *(Ejemplo: Reemplaza con tu propia captura)*

## 📋 Requisitos
- Windows 10 o superior.
- .NET Framework 4.8 (usualmente incluido en Windows).

## 📜 Licencia
- Código de la aplicación: **MIT**.
- Dependencias:
- PySide6 ([LGPL 3.0](https://www.gnu.org/licenses/lgpl-3.0.html))
- pdfplumber/openpyxl ([MIT](https://opensource.org/licenses/MIT)).

Ver detalles en [LICENSE.txt](LICENSE.txt).

## ⚠️ Notas Importantes
- Mantén la carpeta `assets` junto al ejecutable.
- Los archivos PDF deben ser válidos (emitidos por SUNAT).

## 🛠 Soporte
¿Problemas? Abre un [issue](https://github.com/tu-usuario/SUNrise/issues) en GitHub.

---
© 2025 [Piero Herrera Larrea](https://github.com/tu-usuario) | [Iconos por Freepik](https://www.flaticon.com) *(opcional)*
