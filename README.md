# 📘 Documentación del Servidor – Guía de trabajo con MkDocs

Este proyecto utiliza **MkDocs + Material** para generar la documentación del servidor.  
Para mantener el sistema seguro sin romper dependencias de Ubuntu, se utiliza un **entorno virtual de Python (venv)**.

---

## 🧱 1. Activar el entorno virtual (OBLIGATORIO antes de editar la documentación)

Antes de agregar o modificar la documentación, activar el entorno virtual:

````bash
source ~/mkdocs-venv/bin/activate

Cuando esté activo, el prompt mostrará:

(mkdocs-venv)

🛠 2. Ejecutar el servidor local de documentación

Para ver la documentación en tiempo real mientras editás:

```bash
mkdocs serve

Luego abrir en el navegador:

http://localhost:8000

📦 3. Instalar nuevas extensiones o plugins de MkDocs

Siempre con el entorno virtual activado:

```bash
pip install nombre-del-plugin

⏹ 4. Desactivar el entorno virtual

Cuando termines de trabajar:

```bash
deactivate

🚀 5. Compilar documentación para producción (si algún día la publicás)

```bash
mkdocs build

El sitio generado queda en la carpeta:

site/

🧩 Ubicación de archivos importantes
 • Configuración de MkDocs: mkdocs.yml
 • Contenido de la documentación: carpeta docs/
 • Entorno virtual: ~/mkdocs-venv/

⸻

💡 Recordatorio importante

Si intentás ejecutar mkdocs serve sin activar el entorno virtual, MkDocs no estará disponible y la terminal devolverá command not found.
````
