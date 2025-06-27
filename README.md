# python-final

### 1. Abrir la terminal de Git Bash o terminal en Linux

- Debe ser como administrador en Windows

### 2. Creamos una carpeta o directorio:

```bash
mkdir python-final
```

### 3. Entramos en ella:

```bash
cd python-final
```

### 4. Iniciamos el repositorio:

```bash
git init
```

### 5. Creamos un archivo:

```bash
touch finales.py
```

### 6. Abrimos VSC:

```bash
code .
```

### 7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

```bash
python -V
python3 -V
```

### 8. Creamos el entorno virtual en Python:

```bash
python3 -m venv venv  # Creamos el entorno virtual
```

### 9. Activamos el entorno virtual:

```bash
source venv/bin/activate  # Activamos el entorno virtual en Linux

venv/scripts/activate  # En Windows
```

### 10. Hacemos actualización del pip de Python:

```bash
python3 -m pip install --upgrade pip  # Actualizamos el pip
```

### 11. Investigar ¿Qué es el pip y por qué lo actualizamos?

**¿Qué es pip?**

- **pip** (Pip Installs Packages) es el sistema de gestión de paquetes estándar para Python
- Permite instalar, actualizar y desinstalar paquetes de Python desde el Python Package Index (PyPI)
- Es una herramienta esencial para manejar dependencias en proyectos Python

**¿Por qué actualizamos pip?**

- **Seguridad**: Las versiones más recientes corrigen vulnerabilidades de seguridad
- **Compatibilidad**: Mejora la compatibilidad con nuevos paquetes y versiones de Python
- **Rendimiento**: Las actualizaciones incluyen optimizaciones y mejoras de velocidad
- **Nuevas características**: Acceso a nuevas funcionalidades y comandos
- **Resolución de bugs**: Corrige errores conocidos de versiones anteriores
