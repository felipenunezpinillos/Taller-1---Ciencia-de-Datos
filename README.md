# Taller-1---Ciencia-de-Datos

## Integrantes del Equipo:
Felipe Nuñez - 
Juan Manuel Pérez - 202021827

## Objetivo
El objetivo del análisis es identificar los factores que influyen en la cancelación de reservas y en la ocupación efectiva de los hoteles, con el fin de proporcionar insumos basados en datos que permitan a la cadena hotelera diseñar estrategias que reduzcan la tasa de cancelación, optimicen la demanda en temporadas bajas y mejoren la gestión de ingresos.

## Alcance
El análisis se realizará a partir del dataset proporcionado, que contiene información de más de 58 mil reservas en dos tipos de hoteles (City Hotel y Resort Hotel). Se estudiarán variables clave como el tipo de hotel, tipo de habitación, lead_time, estacionalidad de la demanda, tipo de depósito, historial de cancelaciones y recurrencia de clientes. El trabajo contempla análisis exploratorio descriptivo, pruebas de hipótesis e inferencia estadística aplicadas a preguntas específicas de negocio,

## Conclusiones (insights)

## 1. Cancelación por tipo de hotel
- **City Hotel**: ~70% de cancelaciones.  
- **Resort Hotel**: ~28% de cancelaciones.  
-  **Acción**: aplicar políticas de **depósito más estrictas** en City Hotel, controlar **cupos en OTAs**, e incentivar reservas confirmadas con **descuentos o fidelización**.

## 2. Incumplimiento en asignación de habitación
- El incumplimiento en la asignación (cuando no se entrega el cuarto reservado) **no incrementa significativamente la cancelación**.  
-  **Acción**: mantener protocolos de **compensación** (upgrades, desayunos) y monitorear **satisfacción/NPS** en estos casos.

## 3. City Hotel – cancelación por tipo de habitación
- Alta cancelación en la mayoría de las habitaciones, excepto en **B y K** (baja cancelación).  
-  **Acción**: promover **upgrades hacia B/K** en baja demanda y revisar **pricing/stock** en los tipos con mayor riesgo.

## 4. Resort Hotel – cancelación distribuida
- Cancelación más repartida; destacan **A, G, H, P y L** con mayor riesgo.  
-  **Acción**: auditar estos tipos de habitación, ajustar **tarifas/depósitos** y revisar **cupos por canal**.

## 5. Estacionalidad – City Hotel
- Mayor demanda: **agosto, septiembre, octubre**.  
- Baja demanda: **enero, febrero, noviembre, diciembre**.  
- ➡**Acción**: implementar **eventos temáticos** (Navidad, fin de año) y **promociones especiales** en meses débiles.

## 6. Estacionalidad – Resort Hotel
- Mayor demanda: **meses de verano**.  
- Baja demanda: **noviembre, diciembre, enero**.  
- **Acción**: reforzar **actividades para familias y grupos** en temporada baja.

## 7. Influencia del Lead Time
- Las reservas con **mayor anticipación** muestran una **probabilidad más alta de cancelación**.  
- **Acción**: definir **políticas de depósito según tramos de lead time** (ej. >90 días = depósito parcial, >180 días = no reembolsable con beneficio).

## Instrucciones de ejecución y dependencias.
 - pandas
- numpy
- matplotlib
- scipy
- statsmodels
- ydata-profiling

También necesitas el entorno de notebooks:

jupyterlab (o notebook)
