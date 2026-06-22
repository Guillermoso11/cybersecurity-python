# cybersecurity-python
# Cybersecurity Python Tools 🛡️

Este repositorio contiene scripts y herramientas de automatización desarrolladas en Python enfocadas en tareas de ciberseguridad, análisis de logs y administración de redes de forma segura.

## 📁 Scripts Incluidos

### 1. Analizador de Logs de Seguridad (`log_analyzer.py`)
Un script automatizado diseñado para procesar archivos de registro (`.log`) de servidores. Su función principal es identificar ataques de fuerza bruta o escaneos automatizados mediante el rastreo de intentos de inicio de sesión fallidos.

*   **Funcionalidad:** Lee de forma eficiente el archivo de logs, extrae las direcciones IP de origen y genera una alerta de seguridad si una IP supera el umbral de 3 intentos fallidos.
*   **Conceptos aplicados:** Manejo de archivos en Python, estructuras de datos (diccionarios), lógica de filtrado de eventos y detección de incidentes.

## 🚀 Cómo ejecutarlo

1. Clona este repositorio o descarga los archivos.
2. Asegúrate de tener el archivo `server_access.log` en el mismo directorio.
3. Ejecuta el script desde tu terminal:
```bash
   python log_analyzer.py
