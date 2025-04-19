# 📦 Análisis de Desempeño de Producto

Este proyecto tiene como finalidad analizar el **desempeño de productos** en distintos puntos de venta con base en una serie de datos estructurados. El análisis busca brindar información clave para la mejora continua del negocio.

## 🎯 Objetivo del análisis

Obtener **métricas detalladas y comparativas** para responder preguntas como:

- ¿Cuál es el producto más vendido?
- ¿Qué categorías tienen mayor aceptación?
- ¿Cuál es el promedio de satisfacción por producto?
- ¿Cómo varía el costo logístico entre productos?
- ¿Qué tiendas tienen mejor rendimiento por categoría?

Con esta información se pueden generar **recomendaciones estratégicas** para ventas, marketing y logística.

---

## 📁 Estructura del proyecto

```
product-performance-analysis/
├── data/
│   ├── tienda_a.csv
│   ├── tienda_b.csv
│   ├── tienda_c.csv
├── main_analysis.py
├── requirements.txt
├── .gitignore
└── README.md
```

- `data/*.csv`: Contienen la información de ventas por tienda.
- `main_analysis.py`: Script principal que analiza los datos.
- `requirements.txt`: Requisitos de Python para ejecutar el proyecto.
- `README.md`: Este archivo.

---

## 📊 Ejemplo de resultados

```
📈 Resultados Tienda A:
- Producto más vendido: Laptop X
- Categoría más rentable: Electrónica
- Calificación media: 4.2
- Costo logístico promedio: 18.90

📈 Resultados Tienda B:
- Producto más vendido: Smartphone Z
- Categoría más rentable: Accesorios
- Calificación media: 3.9
- Costo logístico promedio: 21.45
```

```
🏆 Comparativas:
- Mejor calificación promedio: Tienda A
- Menor costo logístico: Tienda C
- Producto líder en ventas general: Laptop X
```

---

## ⚙️ Cómo ejecutar el proyecto

### 📌 Requisitos

- Python 3.8+
- pandas

### 🛠️ Pasos para ejecutar

1. Clona o descarga el repositorio.
2. Asegúrate de tener los archivos `.csv` dentro de la carpeta `data`.
3. Ejecuta el script:

```bash
python main_analysis.py
```

Este script procesará todos los archivos y generará los resultados del análisis directamente en consola.

---

## 📬 Contacto

Si tienes sugerencias, mejoras o deseas colaborar, ¡no dudes en escribirme! ✉️  
Tu feedback es muy valioso para seguir mejorando este proyecto 🚀
