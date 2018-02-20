# tradingmotionsdk-portfolio
Herramienta para analizar portfolios a través de estrategias TradingMotion SDK.

La interfaz es un [Jupyter Notebook](http://jupyter.org/) que contiene el código Python para cargar múltiples informes de backtests simulados con la herramienta TradingMotion SDK toolkit, y poder visualizar los datos combinados del portfolio de sistemas.

![Jupyter Notebook TradingMotion Portfolio](screenshot.png?raw=true "TradingMotion Portfolio")

Esta utilidad ha sido creada para ayudar a los participantes de la categoría TradingMotion dentro del concurso de trading algorítmico [Robotrader](http://www.gaps.ssr.upm.es/es/eventos/robotrader).


## Instalación

### 1) Instalar entorno python

Recomiendo instalar el gestor de paquetes conda, versión [Miniconda 3.6](https://conda.io/miniconda.html).

### 2) Crear entorno virtual e instalar dependencias

Una vez clonado este repositorio, desde una consola ejecutamos los siguientes comandos:

```bash
# Creamos virtualenv python3 llamado tradingmotion
$ conda create -n tradingmotion python=3
# Activamos el recién creado virtualenv
$ source activate tradingmotion
# Instalamos las dependencias del proyecto
$ pip install -r requirements.txt
# Creamos un kernel para usar jupyter en el virtualenv tradingmotion
$ python -m ipykernel install --user --name tradingmotion --display-name "Python3 (tradingmotion)"
```

## Uso

```bash
# Ejecutamos el notebook para analizar portfolios
$ jupyter notebook 
```

En este momento se abrirá una ventana del navegador con la interfaz web de Jupyter Notebook. 

Cagamos el notebook **TradingMotion-Portfolios.ipynb** y seguimos las instrucciones

