# README

## Descripción del Proyecto

Este repositorio contiene la solución a la práctica del módulo “Programación Python (avanzado)”, donde se desarrolló un algoritmo para generar un conjunto de datos (Dataset) que consiste en nombres de servidores (hostnames) aleatorios. El objetivo es aplicar los conocimientos adquiridos en los módulos de "Fundamentos de Python" y "Python Avanzado".

## Estructura del Repositorio

- `main`: Contiene el archivo Jupyter Notebook con la implementación de la práctica.
- `data/`: Carpeta donde se almacenará el archivo CSV generado (`hosts.csv`).

## Requisitos

Para ejecutar este proyecto, necesitarás tener instaladas las siguientes bibliotecas de Python:

- pandas
- matplotlib


## Instrucciones de Uso

1. **Clonar el Repositorio**

   Clona este repositorio en tu máquina local:

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. **Navegar al Directorio**

   Entra en el directorio del proyecto:

   ```bash
   cd <NOMBRE_DEL_REPOSITORIO>
   ```

3. **Ejecutar el Notebook**

   Abre el archivo Jupyter Notebook en el archivo `main`:

   ```bash
   jupyter notebook main.ipynb
   ```

4. **Generar el Dataset**

   Ejecuta las celdas del notebook para generar el Dataset y los gráficos. Asegúrate de seguir las instrucciones en el notebook para cada punto de la práctica.

5. **Guardar el CSV**

   El Dataset generado se guardará como `hosts.csv` en la carpeta `data/`.

## Funciones Principales

- `set_hostnames(number_of_hosts)`: Genera un conjunto de hostnames aleatorios según las reglas especificadas.
- `get_os(hostname)`: Devuelve el nombre del sistema operativo basado en el primer carácter del hostname.
- `get_environment(hostname)`: Devuelve el entorno basado en el segundo carácter del hostname.
- `get_country(hostname)`: Devuelve el país basado en los caracteres del tercer al quinto.
- `set_dataframe(count)`: Crea un DataFrame de Pandas a partir de los hostnames generados.

