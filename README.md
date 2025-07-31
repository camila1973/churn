# Proyecto de Ciencia de Datos en AWS – Predicción de Churn

Este proyecto busca construir un pipeline de ciencia de datos completo utilizando servicios de AWS como S3, Glue, Athena, SageMaker y otros. El objetivo final es predecir si un cliente abandonará un servicio (churn) a partir de datos históricos.

---

## 🚀 Fases del Proyecto

1. **Ingesta de Datos**  
   Subida de archivos a S3 y acceso desde Pandas.

2. **Transformación y Limpieza**  
   Uso de Pandas y PySpark para preparar los datos.

3. **Almacenamiento y Consulta**  
   Uso de Athena y Redshift para consultar datos transformados.

4. **Análisis Exploratorio (EDA)**  
   Visualización con Pandas y QuickSight.

5. **Modelado**  
   Entrenamiento de modelos de ML con SageMaker.

6. **Despliegue**  
   Exposición de modelos mediante endpoints en SageMaker.

7. **Orquestación**  
   Automatización con Airflow o AWS Step Functions.

8. **Infraestructura como Código**  
   Uso de Terraform para definir toda la infraestructura en AWS.

---

## 🧰 Herramientas y Tecnologías

- Python, Pandas, PySpark
- Amazon S3, Athena, Glue, Redshift
- Amazon SageMaker
- Apache Airflow
- Terraform

---

## 📁 Estructura del Proyecto