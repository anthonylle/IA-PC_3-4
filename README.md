# Inteligencia Artificial - Proyecto Corto 3 & 4
Modelo de predicción: Árboles de decisión. Explicado utilizando Jupyter Notebook

### Enlace de GitHub
Para visitar el repositorio de GitHub de este Notebook, visite este [enlace](https://github.com/anthonylle/IA-PC_3-4)

#### Prerequisitos
  - Tener previamente instalado una versión de Python (3.6 ó 2.7)
  - Tener el administrador de paquetes de Python (pip)
  - En caso contrario, consultar [cómo instalar pip](https://recursospython.com/guias-y-manuales/instalacion-y-utilizacion-de-pip-en-windows-linux-y-os-x/)
#### Proceso de instalación

  - Abrir una terminal en su computadora
  - Ingresar los siguientes comandos:
    - Para versiones 3.+ de Python
      - python3 -m pip install --upgrade pip
      - python3 -m pip install jupyter
    
    - Para la versión 2.7:
      - python -m pip install --upgrade pip
      - python -m pip install jupyter

 ### Ejecutando Jupyter Notebook
 Jupyter notebook permite administrar un proyecto a traves del navegador, para ello se debe realizar lo siguiente:
 1. Abrir una terminal.
 2. Dirigirse al directorio raíz del proyecto Jupyter Notebook.
 3. Escribir el siguiente comando: jupyter notebook
 
 Inmediatmente se levantará el servidor del poryecto, seguido se abrirá una pestaña en el navegador con el Notebook Dashboard.
 En caso no querer que esta acción se realice por defecto, hacer lo siguiente:
 
 1. Abrir una terminal.
 2. Dirigirse al directorio raíz del proyecto Jupyter Notebook.
 3. Escribir el siguiente comando: jupyter notebook --no-browser
 4. Abrir el navegador de su preferencia.
 5. En una nueva pestaña pegar lo siguiente: http://localhost:8888/
 6. Listo el Notebook Dashboard queda listo para usar.
 
 Para más detalles acerca de la ejecución puede consultar el siguiente link: [Corriendo Notebook](https://jupyter.readthedocs.io/en/latest/running.html#running)
 
 ### Paquetes implementados
  - pydotplus
  - pandas
  - sklearn
  - collections
  - iPython
  - graphviz
  - seaborn
  - pillow
  
 
 #### Instalación de paquetes
Jupyter permite dentro de sus bloques de código ejecutar scripts de instalación de paquetes, para este caso basta con escribir al inicio del codigo los paquetes que requiere,
como se muestra a continuacion:

```python
import sys
!{sys.executable} -m pip install pydotplus
!{sys.executable} -m pip install pandas
!{sys.executable} -m pip install sklearn
!{sys.executable} -m pip install collections
!{sys.executable} -m pip install IPython
!{sys.executable} -m pip install graphviz
!{sys.executable} -m pip install seaborn
!{sys.executable} -m pip install pillow
```

Si ya cuenta con alguno de estos paquetes y no desea que pip realice una reinstalación de los mismos, puede elegir entre los cuáles no cuenta e instalarlos: 
```python
import sys
!{sys.executable} -m pip install <package-name>
...
```