# 📊 Challenge DS2 - TelecomX

Este proyecto tiene como objetivo identificar y analizar los factores que influyen en la **evasión de clientes** en una empresa de telecomunicaciones ficticia llamada **TelecomX**. El análisis se enfoca en **limpieza de datos, exploración visual y descubrimiento de patrones relevantes** para mejorar la retención de clientes y servir de base para un análisis predictivo posterior.

---

## 🎯 Objetivo del Proyecto

El proyecto busca responder a la pregunta:  
> **¿Qué factores están asociados a que un cliente cancele su servicio (Churn)?**

Se pretende **entender el comportamiento de los clientes** y establecer los primeros pasos hacia un **modelo predictivo de evasión**, comenzando con una limpieza y análisis exploratorio de datos exhaustivo.

---

## 🧪 Herramientas Utilizadas

- Python 3.x
- Google Colab / Jupyter Notebook
- Bibliotecas:
  - `pandas` para manipulación de datos
  - `matplotlib` y `seaborn` para visualización
  - `numpy` para operaciones numéricas

---

## 🔍 Etapas del Proyecto

### 1. 📥 Carga y Exploración Inicial
- Montaje de Google Drive.
- Carga del archivo JSON en un DataFrame de `pandas`.
- Exploración de las columnas y tipos de datos.
- Consulta del diccionario para entender cada variable.

### 2. 🧹 Limpieza y Tratamiento de Datos
- Manejo de valores nulos (`charges.total` tenía 11).
- Eliminación de duplicados según el identificador de cliente.
- Estandarización de nombres de columnas y valores.
- Conversión de columnas binarias (`Sí/No`) a `1/0` cuando fue necesario.
- Creación de nueva variable: `Cuentas_Diarias`.

### 3. 📊 Análisis Exploratorio de Datos (EDA)
#### Análisis Descriptivo
- Estadísticas de tendencia central y dispersión para variables numéricas.
  
#### Distribución del Churn
- Gráficos de barras y pastel mostrando proporción de evasión vs suscripción.
- Etiquetas traducidas a español.

#### Variables Categóricas
- Análisis visual de variables como:
  - Género
  - Tipo de contrato
  - Método de pago
  - Tipo de internet
  - Soporte técnico
  - Seguridad en línea
  - Líneas múltiples
- Todos los gráficos traducidos al español con porcentajes sobre cada barra.
- Subgráfica combinada de todos los análisis categóricos.

#### Variables Numéricas
- Boxplots y violín plots para variables como `Total Gastado`, `Meses Contratados`, `Cargos Mensuales`.
- Anotaciones de cuartiles y ajuste de ejes para mejorar la legibilidad.


---

## ✍️ Autor

- **Yosua Corella**  
  Técnico en Ciencia de Datos | Estudiante de Ingeniería Química  
  _“Transformar datos en decisiones estratégicas.”_

---

