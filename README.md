# Taller evaluado ELSOC

Compendio reproducible del curso Reproducibilidad y Comunicacion de Resultados (UDP 2026).

## Como reproducir este informe

1. Instale R (este proyecto se hizo con R 4.4.1) y RStudio.
2. Descomprima el ZIP y abra `TallerELSOC.Rproj`.
3. En la consola, ejecute `renv::restore()`: instala los paquetes con las versiones de `renv.lock`.
4. Abra `informe.qmd` y presione **Render**.

## Datos

`_data/elsoc_long.RData`: ELSOC (COES), olas 2016 a 2019, formato largo.
Se bajo de <https://github.com/elsoc-coes/elsoc_ggplot/tree/master/1_input/data>.

## Estructura

- `informe.qmd` e `informe.html`: el informe y su version renderizada.
- `_data/`: la base de datos, tal como se bajo.
- `_outputs/`: la tabla del informe, `tabla.csv`.
- `_figures/`: el grafico del informe, `grafico.png`.
- `_doc/`: `entorno.txt`, con el sistema operativo, la version de R y el idioma.
- `DESCRIPTION`, `renv.lock`, `renv/` y `.Rprofile`: paquetes, versiones y su activacion.
