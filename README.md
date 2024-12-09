# pdc_unal_reto5
Repositorio para desarrollar el reto 4 de la materia programación de computadores.

# 6. Consultar qué es y cómo funciona *pip* en python.


**pip** (Python Package Installer) es la herramienta oficial de Python para instalar y gestionar paquetes.  
Permite acceder, instalar y actualizar bibliotecas y módulos desde el repositorio [Python Package Index (PyPI)](https://pypi.org/project/pip/).

### 🔧 **¿Cómo funciona?**

- **Instalación de paquetes:**  
  Utiliza `pip install <nombre_del_paquete>` para descargar e instalar paquetes desde PyPI.
  
 ```
 pip install numpy
 ```

  Actualización de paquetes:
  Usa  `pip install --upgrade <nombre_del_paquete> ` para obtener la última versión de un paquete.

 ```
 pip install --upgrade pandas
```

- **Desinstalación de paquetes**:
Con  `pip uninstall <nombre_del_paquete> `, puedes eliminar un paquete instalado.

```
pip uninstall matplotlib
```

Listar paquetes instalados:
Ejecuta pip list para ver todos los paquetes instalados en tu entorno.
```
    pip list
```

### 📚 **Ventajas de usar pip**

Gestión centralizada: Simplifica la instalación de dependencias necesarias para un proyecto.
Amplia compatibilidad: Compatible con entornos virtuales como venv o virtualenv.
Automatización: Permite instalar múltiples paquetes desde un archivo requirements.txt:

```
    pip install -r requirements.txt
```

### 📌 **Recursos adicionales**

[Documentación oficial de pip](https://pypi.org/project/pip/).

[Repositorio de PyPI](https://github.com/pypa/pip).

# 7. Hacer un listado de módulos populares para python que se puedan instalar com *pip* y consultar cómo instalarlos.

Módulos populares para Python que se pueden instalar con *pip* y cómo instalarlos

A continuación, se presentan algunos de los módulos más utilizados en Python, junto con ejemplos de cómo instalarlos utilizando **pip**.

### 📦 **Listado de módulos populares**

1. **NumPy**  
   Librería fundamental para computación numérica y operaciones con arrays en Python.  
   - Instalación:
     ```bash
     pip install numpy
     ```

2. **Matplotlib**  
   Biblioteca para crear gráficos estáticos, animados e interactivos en Python.  
   - Instalación:
     ```bash
     pip install matplotlib
     ```

3. **Seaborn**  
   Extensión de Matplotlib que simplifica la creación de gráficos estadísticos con un diseño atractivo.  
   - Instalación:
     ```bash
     pip install seaborn
     ```

4. **SciPy**  
   Proporciona herramientas avanzadas para matemáticas, ciencia e ingeniería.  
   - Instalación:
     ```bash
     pip install scipy
     ```

5. **Keras**  
   API de alto nivel para el desarrollo de modelos de Deep Learning, compatible con TensorFlow.  
   - Instalación:
     ```bash
     pip install keras
     ```

6. **TensorFlow**  
   Framework de Machine Learning y Deep Learning ampliamente utilizado para desarrollar e implementar modelos de IA.  
   - Instalación:
     ```bash
     pip install tensorflow
     ```

### 🔧 **¿Cómo instalarlos?**

En conclusión, para instalar cualquier modulo se ejecuta `pip install <nombre_del_paquete>` en la terminal o entorno de desarrollo.  

Para instalar múltiples paquetes al mismo tiempo basta con ejecutar:  
```bash
pip install numpy matplotlib seaborn scipy keras tensorflow
```
