# Documentación de la Aplicación Streamlit

## Descripción

Esta documentación detalla la estructura y funcionalidades de la aplicación desarrollada con Streamlit, desplegada en la misma nube que ofrece la tecnologia. La aplicación consta de varias páginas ubicadas en la carpeta `pages`.

## Estructura del Proyecto

```plaintext

├── streamlit/
│   ├── pages/
│   │   ├── Análisis de Reviews.py
│   │   ├── Análisis Geográfico.py
│   │   ├── Estudio de Competencia.py
│   │   ├── ML.py
│   │   ├── KPIs.py
│   ├── requirements.txt
```

# Páginas de la Aplicación

Para poder interpretar correctamente  el desempeño de cada hotel, se detecto con inteligencia artificial aquellos mas similares para evaluar el desempeño en relacion a scores obtenidos por hoteles con caracteristiacas similares. Esto nos permitio ver que la mayoria de los hoteles poseen puntajes en torno a los 8 puntos, siendo los hoteles de tres y cuatro estrellas los mas frecuentes, y siendo la limpieza uno de los parametros mas determinantes.

## Análisis de Reviews

El analisis de las reviews nos permite analizar el desempeño de los hoteles para los distintos clientes, pudiendo detectar el nivel de conformidad para los distintos clientes, segun su nacionalidad, el servicio obtenido, el largo de su estadia, etc.

<p align=center><img src=files/img/workflow.jpeg><p>

## Análisis Geográfico

En analisis geografico muestra una fuerte correlacion entre la disctribucion geografica de las atracciones turisticas, la poblacion y la distribucion de los hoteles. Ademas el tipo de atraccion turistica mas popular para cada zona, es un gran indicador del tipo de turismo que se desarrolla en la zona.

<p align=center><img src=files/img/workflow.jpeg><p>

## Estudio de Competencia

La página "Estudio de Competencia" se encarga de...

<p align=center><img src=files/img/workflow.jpeg><p>

## Machine Learning (ML)

La página de "ML" incorpora...

<p align=center><img src=files/img/workflow.jpeg><p>

## KPIs

La página de "KPIs" muestra...

<p align=center><img src=files/img/workflow.jpeg><p>




### Configuración Local

Para ejecutar la aplicación localmente, sigue estos pasos:

Crea un entorno virtual:

bash
Copy code
python -m venv venv
Activa el entorno virtual:

En Windows:

bash
Copy code
.\venv\Scripts\activate
En Linux/Mac:

bash
Copy code
source venv/bin/activate
Instala las dependencias:

bash
Copy code
pip install -r requirements.txt
Ejecuta la aplicación:

bash
Copy code
streamlit run main.py
Despliegue en AWS
Para desplegar la aplicación en AWS, sigue los siguientes pasos...
