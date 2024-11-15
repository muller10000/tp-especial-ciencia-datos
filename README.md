enlace del informe (drive): https://docs.google.com/document/d/1IfxvnDEw9_l7GducagKu1rRcrczAEOIv0D-9IM5qX2U/edit?usp=sharing

instrucciones de ejecución:

YO USE PYTHON 3.12.2

1) Abre una terminal o consola.
2) Ejecuta el comando git clone <URL_DEL_REPOSITORIO>, reemplazando <URL_DEL_REPOSITORIO> con el enlace de tu repositorio en GitHub. Esto descargará todos los archivos en una carpeta local.
3) En la terminal, navega a la carpeta donde clonaste el repositorio usando cd <NOMBRE_DEL_PROYECTO>, reemplazando <NOMBRE_DEL_PROYECTO> por el nombre de la carpeta
4) Crea un nuevo entorno virtual ejecutando: python -m venv practicoespecialvenv
5) activar el entorno virtual. En Windows, usa .\practicoespecialvenv\Scripts\activate
6) Para instalar una versión empaquetada de un venv, tenés que correr: pip install -r requirements.txt
7) 2 maneras de instalar librerias:
- primera opcion: En la terminal haces un pip install pandas matplotlib numpy fancyimpute scikit-learn scipy seaborn
- segunda opcion: Abre Jupyter Notebook. Dentro del jupyter notebook haces un (en mi caso tuve que usar % pero sino funciona poner un !) %pip install pandas matplotlib numpy fancyimpute scikit-learn scipy seaborn
Ambas maneras funcionan, ya que el uso de %pip install en una celda de Jupyter es útil cuando necesitas instalar una librería adicional mientras trabajas en el notebook o si quieres asegurarte de que otros usuarios que ejecuten el notebook desde cero instalen automáticamente las dependencias al abrir el archivo.
8) Abre Jupyter Notebook ejecutando jupyter notebook
9) Navega al archivo .ipynb del proyecto y ábrelo para ejecutar las celdas y ver el análisis (podes ejecutar todo seleccionando RUN ALL)
10) Usaremos ";" como separador en el CSV --> pd.read_csv("Calidad_de_agua_2022.csv", sep =";")
