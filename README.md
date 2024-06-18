# ClasesComputacionCientifica
Aquí estaré agregando las notas/notebooks de la clase de Computación Científica (Intersemestral 2024).

# Primeros pasos (Instalación):

## Julia + conda :

1. Instalar Julia:
  a. Ir a [la página de descargas oficial de Julia](https://julialang.org/downloads/). Detecta sistema operativo y usualmente las primeras instrucciones son las correctas. Más abajo hay más detalles para otras versiones/instalación manual. Es suficiente hacer la instalación recomendada.
  b. Después de instalar es necesario poner el path de Julia en source (usualmente hay instrucciones de como hacer esto para cada sistema operativo después de terminar la instalación).
2. Instalar conda:
  a. Puede ser [instalando Anaconda](https://www.anaconda.com/download): Es más completo, recomendado para uso de paquetería de Machine learning.
  b. Instalando [mini-conda](https://docs.anaconda.com/miniconda/miniconda-install/): Es lo necesario para este curso.
3. Empezar un ambiente con conda:
    ```
    conda create -n JuliaEnv2 pip
    ```
4. Abrir una notebook en Julia:
 a. Instalar IJulia desde Julia (para tener Julia notebooks):
    i. Una vez dentro de la notebook usar:
     1. `using Pkg`
     2. `Pkg.add("IJulia")`
     3. `using IJulia`
     4. `notebook()`
   ii. Debería abrir una instancia de libreta en el navegador, después de la instalación de IJulia solo es necesario usar 3 y 4 en sesiones posteriores.
  b. Después de la instalación también se puede abrir una libreta desde Anaconda Navigator al abrir una Jupyter notebook y escoger la versión de Julia instalada.
