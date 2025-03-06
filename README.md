# Funciones de Activación en Python

Este repositorio contiene la implementación de diversas funciones de activación utilizadas en redes neuronales.  
El código está estructurado de manera modular, con cada función definida en archivos separados dentro de la carpeta `src/`.  

## 💁 Estructura del Repositorio

```
📆 funciones_de_activacion
👉 📂 src
    👉 relu.py
    👉 tanh.py
    👉 escalo.py
    👉 gaussiana.py
    👉 identidad.py
    👉 lineal_a_tramos.py
    👉 sigmoide.py
    👉 sinusoidal.py
👉 main.py
👉 requirements.txt
👉 .gitignore
👉 README.md
```

## 🚀 Ejecución

Para ejecutar el programa, asegúrate de tener Python instalado y sigue estos pasos:

1. **Clonar el repositorio**  
   ```bash
   git clone https://github.com/tu_usuario/funciones_de_activacion.git
   cd funciones_de_activacion
   ```

2. **Crear y activar un entorno virtual**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Mac/Linux
   venv\Scripts\activate     # En Windows
   ```

3. **Instalar las dependencias**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Ejecutar el programa**  
   ```bash
   python main.py
   ```

## 🧠 Funciones Implementadas

Cada función de activación se encuentra en la carpeta `src/` y puede ser importada en `main.py`.  

| Función               | Archivo              | Descripción |
|-----------------------|----------------------|-------------|
| ReLU                 | `relu.py`             | Rectified Linear Unit (ReLU) |
| Tangente Hiperbólica | `tanh.py`             | Función tangente hiperbólica |
| Escalo               | `escalo.py`           | Función de escalón |
| Gaussiana            | `gaussiana.py`        | Función de activación Gaussiana |
| Identidad            | `identidad.py`        | Función identidad (f(x) = x) |
| Lineal a Tramos      | `lineal_a_tramos.py`  | Función de activación por tramos |
| Sigmoide             | `sigmoid.py`          | Función sigmoide estándar |
| Sinusoidal           | `sinusoidal.py`       | Función de activación sinusoidal |

## 📌 Notas

- Asegúrate de usar un entorno virtual (`venv`) para evitar conflictos con otras bibliotecas de Python.  
- Modifica `main.py` si deseas probar diferentes combinaciones de funciones de activación.  

## 📝 Licencia

Este proyecto es de código abierto y puedes utilizarlo libremente.  

---

¡Si encuentras útil este repositorio, no olvides darle ⭐ en GitHub! 🚀
