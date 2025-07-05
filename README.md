# Predicción de Cancelación de Clientes – Model Fitness

## Descripción del Proyecto

Este proyecto fue desarrollado como parte del Sprint 13 del bootcamp de análisis de datos de TripleTen. El objetivo es ayudar a la cadena de gimnasios **Model Fitness** a identificar clientes con riesgo de cancelación, entender los factores que influyen en su permanencia y segmentar a los usuarios para diseñar estrategias de retención más efectivas.

---

## Etapas del Proyecto

### 1. Análisis Exploratorio de Datos (EDA)

**Dataset utilizado:** `gym_churn_us.csv`

- Revisión de valores ausentes y tipos de datos.
- Análisis estadístico de variables numéricas y categóricas.
- Comparación de métricas entre clientes que cancelaron y los que permanecieron.
- Visualización de distribuciones y correlaciones.

---

### 2. Modelado Predictivo

**Objetivo:** Predecir si un cliente cancelará su membresía el próximo mes.

- División del dataset en entrenamiento y validación.
- Entrenamiento de dos modelos:
  - Regresión logística
  - Bosque aleatorio (Random Forest)
- Evaluación de desempeño con métricas: accuracy, precision, recall.
- Comparación de modelos para seleccionar el más efectivo.

---

### 3. Segmentación de Clientes (Clustering)

- Estandarización de variables numéricas.
- Análisis jerárquico con dendrograma para estimar número de clústeres.
- Aplicación de K-means con n=5.
- Análisis de características promedio por clúster.
- Cálculo de tasa de cancelación por grupo.

---

## Resultados

- El modelo de bosque aleatorio mostró mejor desempeño predictivo.
- Se identificaron clústeres con alta propensión a cancelar, caracterizados por baja frecuencia de visitas, contratos cortos y poca interacción con servicios adicionales.
- Los clientes más leales tienden a tener contratos largos, asistir a clases grupales y gastar más en servicios adicionales.

---

## Recomendaciones

- **Segmentación personalizada:** Enfocar campañas de retención en clústeres con alta tasa de cancelación.
- **Incentivos por permanencia:** Ofrecer beneficios por renovar contratos largos.
- **Promoción de clases grupales:** Fomentar la participación en actividades colectivas para aumentar el compromiso.
- **Upselling de servicios adicionales:** Promover productos y servicios complementarios para aumentar el valor percibido.

---

## Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Scipy (linkage, clustering)  
- Jupyter Notebook

---

## 📫 Contacto

Paz Emmanuel Balderas Cerezo  
📧 pazemmanuel24032005@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/paz-emmanuel-balderas-cerezo-dataanalyst)
