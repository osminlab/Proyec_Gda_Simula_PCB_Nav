# Código Python
Se contiene todo el código fuente del trabajo de graduación. En el documento se aborta esta temática en capítulo 2 y 3.

## Estructura del Proyecto (Código) 📦

    .
    ├── README.md                       ◄---- Archivo actual.
    ├── data                            ◄---- Subcarpeta donde se guardan los 
    │   │                                     datos generados del simulados.
    │   ├── README.md
    │   ├── parameters_ascenso.csv
    │   └── parameters_descenso.csv     
    ├── requirements.txt                ◄---- Librerías necesarias para correr el proyecto.
    │
    └── src                             ◄---- Jupyter Notebooks con los códigos.
        │
        ├── 1_Simulacion_Trayectoria.ipynb
        └── 2_EDA.ipynb


## Proceso de Instalación ⚙️

1. Clona el repositorio y muevete al directorio donde lo descargaste.
``` bash
git clone <HTTPS o SSH> 
cd <directorio>
```
También se puede [descargar como archivo.zip aquí](https://github.com/osminlab/Proyec_Gda_Simula_PCB_Nav/archive/refs/heads/main.zip) y descomprimirlo. 

2. Crea y luego activa el ambiente virtual. Funciona con Windows con WSL, Linux y Mac:
``` bash
python3 -m venv env
source env/bin/activate
```

3. Instalar los módulos y dependencias contenidas en requirements.txt
``` bash
pip install -r requirements.txt
```

4. ¡Todo listo! Abre el Jupyter Notebook, módulo o código que deseas.

## Licencia

En carpeta `./code` bajo licencia [GNU LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.en.html#license-text).