# Cosas aprendidas

## Métodos de DataFrames

* df.info(): sumariza la información
* df.describe(): sumariza los atributos numéricos
* df.value_counts(): cuenta "categorías"
  * df["nombre_columna"].value_counts()

## Gráficas

* En el capítulo 2 hay una función para guardar gráficas como archivos: save_fig()

* df.hist(bins, figsize, layout): histogramas; <https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.hist.html>