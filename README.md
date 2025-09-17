# ✈️ Análisis de Clientes de un Programa de Lealtad Aérea

Este proyecto corresponde al **ejercicio de evaluación final del Módulo 3 de Data Analytics**.  
El objetivo es realizar un análisis exploratorio, limpieza, visualización y evaluación estadística sobre los datos de clientes de un programa de lealtad de una aerolínea.

---

## Datos utilizados

Se han proporcionado dos archivos CSV:

- **Customer Flight Analysis.csv**  
  Contiene información sobre la actividad de vuelo de los clientes:
  - Identificador de cliente.
  - Número de vuelos reservados.
  - Vuelos con acompañantes.
  - Distancia volada.
  - Puntos acumulados y redimidos.
  - Coste en dólares de los puntos redimidos.

- **Customer Loyalty History.csv**  
  Incluye datos demográficos y de membresía:
  - Identificador de cliente.
  - País, provincia, ciudad y código postal.
  - Género, nivel educativo, salario y estado civil.
  - Tipo de tarjeta de lealtad y valor total estimado que el cliente aporta a la empresa (CLV).
  - Tipo de inscripción en el programa de lealtad.
  - Año y mes de inscripción y cancelación, en el caso de que se produzca.

---

## Metodología

El trabajo se ha estructurado en tres fases:

### Fase 1. Exploración y Limpieza
- Revisión inicial de los datos con `pandas`.
- Detección y tratamiento de valores nulos.
- Conversión de tipos de datos y unificación de los dos conjuntos en un único DataFrame.

### Fase 2. Visualización
Creación de gráficas con `matplotlib` y `seaborn` para responder a las siguientes preguntas:
- Distribución de vuelos reservados por mes durante el año.
- Relación entre distancia de los vuelos y los puntos acumulados por el cliente.
- Distribución de clientes por provincia o estado.
- Comparación del salario promedio según nivel educativo de los clientes.
- Proporción de clientes por tipo de tarjeta de fidelidad.
- Distribución de clientes según su estado civil y género.

### Fase 3. Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo (Bonus)
- Evaluar si existen diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes. 
---

## Tecnologías utilizadas
- Python 3  
- Pandas  
- Matplotlib  
- Seaborn  
- Numpy  
- Scipy (para pruebas estadísticas)

---

## Objetivo del proyecto
El ejercicio tiene como finalidad aplicar técnicas de análisis exploratorio, limpieza y visualización de datos en un contexto realista, así como desarrollar competencias en estadística descriptiva e inferencial.  

---

## Mejoras en un futuro
- Finalizar la fase 3 y ampliar el estudio estadístico. 
- Optimizar el tratamiento de outliers mediante métodos más robustos.
- Aplicar técnicas de clustering para identificar perfiles de clientes y patrones de comportamiento.

---

## Autora
María de Magdala Pérez Nimo. 
