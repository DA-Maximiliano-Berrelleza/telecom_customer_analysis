# Análisis de clientes de ConnectaTel

## Objetivo del proyecto

Analizar la información de **4,000 clientes** y **40,000 registros de llamadas y mensajes** de ConnectaTel correspondientes a 2024, con el propósito de evaluar la calidad de los datos, identificar patrones de uso y valores atípicos, construir segmentos de clientes y generar conclusiones útiles para el negocio.

## Datasets utilizados

| Archivo | Contenido |
|---|---|
| `plans.csv` | Características, beneficios, precios y cargos adicionales de los planes Básico y Premium. |
| `users_latam.csv` | Información demográfica, ciudad, fecha de registro, plan contratado y fecha de cancelación de los clientes. |
| `usage.csv` | Registros de llamadas y mensajes, incluyendo fecha, duración y longitud. |

Los archivos CSV no se incluyen en el repositorio. Para ejecutar el análisis deben cargarse manualmente en Google Colab con los nombres indicados.

## Etapas del análisis

1. Carga y exploración inicial de los datasets.
2. Evaluación de valores nulos, sentinels y fechas inconsistentes.
3. Limpieza y validación de las variables afectadas.
4. Construcción del perfil histórico de uso por cliente.
5. Análisis de distribuciones y valores atípicos.
6. Segmentación de clientes por edad y nivel de uso.
7. Cruces complementarios entre edad, uso, plan y cancelaciones registradas.
8. Elaboración de conclusiones y recomendaciones para el negocio.

## Cómo abrir y ejecutar el notebook

1. Abre [Google Colab](https://colab.research.google.com/).
2. Selecciona **Archivo → Abrir cuaderno → GitHub**.
3. Ingresa la URL de este repositorio:

   ```text
   https://github.com/DA-Maximiliano-Berrelleza/telecom_customer_analysis
   ```

4. Selecciona `telecom_customer_analysis.ipynb`.
5. Carga `plans.csv`, `users_latam.csv` y `usage.csv` en el directorio principal de la sesión.
6. Selecciona **Entorno de ejecución → Ejecutar todo**.
7. Verifica que todas las celdas se ejecuten en orden y sin errores.

## Guía breve de reproducción

- Utilizar Python 3 con `pandas`, `numpy`, `matplotlib` y `seaborn`. Estas librerías ya están disponibles en Google Colab.
- Mantener los nombres originales de los tres archivos CSV.
- Colocar los datasets en el mismo directorio desde el que se ejecuta el notebook.
- Ejecutar las celdas desde la primera hasta la última para reproducir la limpieza, las visualizaciones, la segmentación y el análisis ejecutivo.
