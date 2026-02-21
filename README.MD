# Dependencias
## Instalación de dependencias

Para ejecutar este proyecto es necesario tener Python 3 instalado junto con las siguientes dependencias utilizadas en el análisis de datos:

- pandas
- matplotlib
- jupyter

Instalación mediante pip:

```bash
pip install pandas matplotlib jupyter
```


# Análisis de TelecomX

## Descripción
En esta etapa del proyecto se realizó un análisis exploratorio enfocado en la relación entre variables numéricas y la evasión de clientes (Churn)

Este análisis continúa el proceso de limpieza, transformación y exploración


## Proceso Realizado
1. Uso del dataset previamente limpiado y normalizado desde JSON a DataFrame.
2. Verificación de tipos de datos en columnas numéricas.
3. Segmentación de los datos según la variable objetivo Churn.
4. Generación de visualizaciones para comparar distribuciones entre clientes que cancelaron y los que no.

## Visualizaciones Generadas
Se crearon dos gráficos principales:

### 1. Tipo de Contrato vs Churn
Se analizó la distribución del contrato de los clientes en función de si abandonaron o no la compañía.

### 2. Tenure vs Churn
Se visualizó la relación entre el tiempo de permanencia del cliente y la evasión.  
Esto ayuda a identificar si los clientes con menor antigüedad presentan mayor probabilidad de cancelar el servicio.

## Principales Hallazgos
- Los clientes que abandonan la compañía tienden a tener contrato a menor tiempo (Meses)
- El total gastado suele ser menor en clientes que presentan churn.
- Los clientes con mayor antigüedad muestran una menor tasa de cancelación.
- Existe una relación clara entre permanencia del cliente y retención.

## Conclusión
El análisis de variables numéricas evidenció que el tiempo de contrato y el gasto total son factores relevantes en la evasión de clientes.  
Estos resultados aportan información clave para futuras etapas del proyecto, como la construcción de modelos predictivos de churn y el diseño de estrategias de retención basadas en el comportamiento del cliente.