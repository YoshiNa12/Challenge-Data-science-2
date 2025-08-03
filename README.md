# 📊 Challenge DS2 - TelecomX

Este proyecto tiene como objetivo identificar y analizar los factores que influyen en la **evasión de clientes** en una empresa de telecomunicaciones ficticia llamada **TelecomX**. El análisis se enfoca en **limpieza de datos, exploración visual y descubrimiento de patrones relevantes** para mejorar la retención de clientes y servir de base para un análisis predictivo posterior.

---

## 🎯 Objetivo del Proyecto

El proyecto busca responder a la pregunta:  
> **¿Qué factores están asociados a que un cliente cancele su servicio (Churn)?**

Se pretende **entender el comportamiento de los clientes** y establecer los primeros pasos hacia un **modelo predictivo de evasión**, comenzando con una limpieza y análisis exploratorio de datos exhaustivo.

---

## 🧾 Estructura del Proyecto

El proyecto contiene los siguientes archivos y componentes:

- **`TelecomX_Data.json`**: archivo principal de datos con información de clientes y servicios.
- **`TelecomX_diccionario.md`**: glosario con la descripción de las variables contenidas en el dataset.
- **Notebook `TelecomX_YCZ.ipynb`**: archivo principal que contiene todo el análisis de datos, visualizaciones y comentarios explicativos.
- **Este archivo `README.md`**: documentación completa del proyecto.

---

## 🧪 Herramientas Utilizadas

- Python 3.x
- Google Colab 
- Bibliotecas:
  - `pandas` para manipulación de datos
  - `matplotlib` y `seaborn` para visualización
  - `numpy` para operaciones numéricas

---

## 📊 Análisis Exploratorio de Datos

### 1. 📥 Carga y Exploración Inicial
- Montaje de Google Drive.
- Carga del archivo JSON en un DataFrame.
- Exploración de columnas y tipos de datos.
- Revisión del diccionario para entender las variables.

### 2. 🧹 Limpieza y Tratamiento de Datos
- Eliminación de nulos en `charges.total`.
- Eliminación de duplicados por ID de cliente.
- Estandarización de nombres de columnas.
- Traducción de valores categóricos (Sí/No, Male/Female, etc.).
- Conversión de variables binarias a 1 y 0.
- Creación de nueva columna: `Cuentas_Diarias`.

### 3. 📈 Visualizaciones y Hallazgos

#### Distribución de Evasión
- Gráficos de barras y pastel para mostrar proporción entre evadidos y suscritos.
- Etiquetas en español y conteo visible en cada barra.

#### Análisis de Variables Categóricas
- Gráficos agrupados para: Género, Contrato, Internet, Seguridad, Soporte, entre otros.
- Gráficas traducidas con porcentajes y etiquetas claras.
- Subgráfica final con todos los gráficos categóricos juntos.

#### Análisis de Variables Numéricas
- `Cargos Totales`, `Cargos Mensuales` y `Meses Contratados` según condición de churn.
- Gráficos: histogramas, violin plots y boxplots con cuartiles anotados.

---

## 📌 Principales Hallazgos

- Mayor evasión en clientes con **contratos mensuales** y **pago electrónico**.
- Clientes con **menor tiempo contratado** y **mayores gastos mensuales** tienen más riesgo de cancelar.
- **Servicios de soporte técnico y seguridad en línea** se asocian a menor evasión.
- No hay diferencias relevantes entre **géneros** o número de líneas.

---

## ✅ Recomendaciones Estratégicas

1. Ofrecer **descuentos o beneficios** por contratos anuales.
2. Incentivar el uso de **servicios de soporte y seguridad digital**.
3. Evaluar la experiencia de usuarios con pagos electrónicos.
4. Dirigir campañas de retención a clientes de **alto gasto mensual**.
5. Continuar con el desarrollo de un modelo **predictivo de churn**.

---

## ✍️ Autor

- **Yosua Corella**  
  Técnico en Ciencia de Datos | Estudiante de Ingeniería Química  
  _“Transformar datos en decisiones estratégicas.”_

---

## ▶️ Instrucciones para Ejecutar el Proyecto

1. Clona este repositorio o descarga los archivos localmente.
2. Abre el archivo `TelecomX_EDA.ipynb` en Google Colab o Jupyter Notebook.
3. Asegúrate de tener disponibles:
   - `TelecomX_Data.json`
   - `diccionario.md`
4. Instala las bibliotecas necesarias si corrés localmente:
```bash
 - `pip install pandas matplotlib seaborn numpy`




