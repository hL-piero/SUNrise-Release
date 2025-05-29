# SUNrise 4.2.5
Registro Integrado para el Sistema Electrónico de SUNAT

![Logo SUNrise](https://github.com/hL-piero/SUNrise-Release/blob/main/sunrise.png)

Aplicación para procesar documentos electrónicos (XML, ZIP, PDF) de SUNAT, con generación de reportes.

## 📥 Descarga e Instalación

1. **Descarga los archivos divididos**:
   - [SUNrise.zip.001](https://github.com/hL-piero/SUNrise-Release/blob/main/SUNrise.zip.001)
   - [SUNrise.zip.002](https://github.com/hL-piero/SUNrise-Release/blob/main/SUNrise.zip.002)
   - [SUNrise.zip.003](https://github.com/hL-piero/SUNrise-Release/blob/main/SUNrise.zip.003)

2. **Une los archivos**:
   - Usa [7-Zip](https://www.7-zip.org/) o similar.
   - Coloca los 3 archivos en la misma carpeta.
   - Extrae `SUNrise.zip.001` (se unirán automáticamente).

3. **Contenido del ZIP**:
SUNrise/
- SUNrise 4.2.5.exe # Ejecutable principal
- assets/ # Recursos visuales (íconos, imágenes)
- LICENSE.txt # Licencias de terceros (LGPL 3.0 + MIT)
- NOTICE.txt # Información legal adicional

## 🚀 Uso Básico
1. Ejecuta `SUNrise 4.2.5.exe` (Windows 10/11).
2. Arrastra archivos (XML/ZIP/PDF) a la ventana o usa el botón "+ Añadir archivos".
3. Genera reportes con el botón inferior.
4. El botón de configuraciones mostrará un menú para modificar características del reporte a generar y para cambiar parámetros de funcionamiento.
5. Botón de limpieza completa de la tabla

![Captura de pantalla](https://github.com/hL-piero/SUNrise-Release/blob/main/screenshot.png)

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
¿Problemas? Abre un [issue](https://github.com/hL-piero/SUNrise/issues) en GitHub.

---
© 2025 [Piero Herrera Larrea](https://github.com/hL-piero/)
