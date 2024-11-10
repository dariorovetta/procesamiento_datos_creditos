# Análisis de Datos de Créditos Personales

Este repositorio contiene un proyecto de análisis de datos de créditos personales en Python, desarrollado para explorar y visualizar datos de clientes, evaluando sus características y su relación con la adquisición de créditos.

## Descripción

El proyecto analiza un conjunto de datos de clientes que incluye información demográfica y financiera para entender factores relevantes en la toma de decisiones de préstamos personales. Los datos se cargan desde un archivo CSV y se exploran mediante el uso de `pandas` para la manipulación de datos y `matplotlib` para la visualización.

### Columnas del Dataset

El conjunto de datos incluye las siguientes columnas:

* **ID** : Identificador único del cliente.
* **Age** : Edad del cliente.
* **Experience** : Años de experiencia laboral.
* **Income** : Ingreso anual del cliente en miles de dólares.
* **ZIP Code** : Código postal.
* **Family** : Tamaño de la familia.
* **CCAvg** : Promedio de gasto en tarjeta de crédito.
* **Education** : Nivel de educación (1 = Undergrad, 2 = Graduate, 3 = Advanced/Professional).
* **Mortgage** : Monto de la hipoteca.
* **Personal Loan** : Indica si el cliente ha adquirido un préstamo personal (0 = No, 1 = Sí).
* **Securities Account** : Indica si el cliente tiene cuenta de valores (0 = No, 1 = Sí).
* **CD Account** : Indica si el cliente tiene cuenta de depósito a plazo (0 = No, 1 = Sí).
* **Online** : Indica si el cliente está registrado en banca en línea (0 = No, 1 = Sí).
* **CreditCard** : Indica si el cliente tiene tarjeta de crédito del banco (0 = No, 1 = Sí).

## Requerimientos

* **Python 3.x**
* Librerías:
  * `pandas`: Para el manejo y análisis de datos.
  * `matplotlib`: Para la generación de gráficos.

## Uso

1. Clona este repositorio.
2. Ejecuta el código en un entorno de Jupyter Notebook o en un script Python después de instalar las dependencias necesarias.
3. Modifica el archivo CSV según sea necesario para incluir tus propios datos.

## Funcionalidades

* **Carga y Exploración de Datos** : Carga de datos desde un archivo CSV y análisis de su estructura y tipos de datos.
* **Visualización** : Generación de gráficos para observar distribuciones y correlaciones en los datos.

## Notas

El proyecto proporciona un punto de partida para analizar y explorar datos de clientes, útil en el contexto de análisis de préstamos personales y segmentación de clientes en el sector financiero.
