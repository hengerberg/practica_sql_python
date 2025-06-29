# 🛍️ Análisis de Ventas - Tienda Online  
**Mini proyecto personal de práctica con PostgreSQL, Python y SQL**

---

### 📌 Descripción

Este proyecto consiste en la **carga, limpieza, modelado e inserción de datos de ventas** desde un archivo CSV a una base de datos PostgreSQL. Luego se realizan consultas SQL relevantes para el análisis de negocio y se exportan los resultados a un archivo Excel con múltiples hojas.

Fue desarrollado de forma autodidacta como parte de mi preparación para trabajar como analista de datos.

---

### 🧰 Tecnologías utilizadas

- Python 3
- Pandas
- SQLAlchemy
- PostgreSQL
- SQL
- OpenPyXL

---

### 🔄 Flujo de trabajo

1. **Carga del CSV**
   - Lectura del archivo `sales_data_sample.csv` con pandas.

2. **Normalización de datos**
   - Separación en 4 tablas: `customers`, `products`, `orders`, `order_items`.

3. **Limpieza y transformación**
   - Renombrado de columnas al estilo `snake_case`.
   - Eliminación de duplicados.
   - Conversión de fechas.

4. **Inserción en PostgreSQL**
   - Conexión segura con SQLAlchemy.
   - Uso de transacción `engine.begin()` para rollback automático en caso de error.

5. **Consultas SQL**
   - Análisis de ventas, clientes, productos, ingresos, etc. (12 preguntas clave).

6. **Exportación**
   - Resultados exportados a un archivo Excel con múltiples hojas y preguntas en la fila superior.

---

### ⚙️ Instalación

Sigue estos pasos para clonar y ejecutar este proyecto en tu máquina local:

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
```

2. **Clonar el repositorio**
```bash
pip install -r requirements.txt
```
3. **Ejecutar el script principal**
```bash
python analisis_tienda.py
```
---
### 📈 Objetivos de aprendizaje alcanzados

- Conexión y manipulación de datos en PostgreSQL desde Python
- Modelado de datos relacional a partir de un CSV
- Uso de SQL para consultas analíticas
- Inserciones seguras con control de errores
- Generación de reportes automatizados en Excel

- ---
### ✅ Estado del proyecto
Finalizado – versión inicial completa

Será mejorado en futuras versiones incorporando claves foráneas más robustas (customer_id) y una arquitectura modular del código.

---
### ✍️ Autor
Hengerberg Alexander Vegas Gudiño

📍 Madrid

📧 vegashengerberg@gmail.com

🔗 Buscando mi primera oportunidad en el área de análisis de datos
