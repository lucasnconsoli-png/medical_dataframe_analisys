Aqui ire anotando las cosas que voy aprendiendo
    1. Entorno virtual
        Esto se utiliza para aislar versiones de distintos programas
        asi un directorio usa una version de tal libreria y otro usa otra
        version

        Comando para crear (se debe estar en el directorio) el entorno virtual: 
            @; python -m venv .venv
        
        Para activar el entorno virtual
            @; .venv/Script/activate

    2. Instalacion librerias en python
        Para instalar librerias se utiliza el comando:
            @; pip install ..... (las librerias que se quieran instalar)
    
    3. Pandas
        Lo primero que se aprende es a como importar la libreria pandas a tu archivo .py o en este caso .ipynb que es un notebook donde se ejecuta codigo por celdas.
        Pandas se importa de la siguiente manera
            @; import pandas as pd
        
        Luego tenemos la primera funcion que es read_csv, read_xlsx, read_dataFrame:
            df = pd.read_csv("archivo.csv")

        Tendremos las siguientes funciones:
            df.head(): muestra las 5 primeras filas, si pones 25, muestra las 25 primeras filas
            df.tail(): lo mismo que head pero las 5 ultimas filas
            df.info(): muestra informacion general del dataFrame como tipos de variables, numero de rows y columns
            df.describe(): muestra informacion estadistica general como la media, maximo, minimo, desviacion tipica, etc
            df.columns(): muestra el nombre de las columnas

