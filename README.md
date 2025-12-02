# AutoRecon-X

**AutoRecon-X** es una herramienta de automatización para la fase de reconocimiento (Recon) en pruebas de penetración y ejercicios de Red Teaming. Su objetivo es orquestar múltiples escáneres de seguridad para reducir el tiempo de *Information Gathering*.

## 🚀 Funcionalidades
- **Enumeración de Subdominios:** Integración con Subfinder.
- **Validación de Activos:** Filtrado de hosts vivos mediante HTTPX.
- **Detección de Vulnerabilidades:** Escaneo automatizado con Nuclei Templates.
- **Reportes Centralizados:** Generación de carpetas organizadas por fecha y objetivo.

## 📋 Requisitos
- Python 3.x
- Herramientas instaladas: `subfinder`, `httpx`, `nuclei`.
- Entorno Linux (Recomendado: Kali Linux / Parrot OS).

## 🛠️ Instalación y Uso

```bash
# 1. Clonar el repositorio
git clone https://github.com/pwned-by-xH1/autorecon-x.git

# 2. Entrar al directorio
cd autorecon-x

# 3. Ejecutar la herramienta
python3 autorecon.py target.com
