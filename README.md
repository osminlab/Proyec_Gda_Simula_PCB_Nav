<!-- Para mejorar la estructura de mi README.md hice uso de la siguiente web y criterios personales:
    	                https://www.makeareadme.com/
 -->

# **Proyecto de Graduación:** "Simulación de trayectoria de un globo sonda para dimensionamiento de subsistema de navegación para misiones a la estratosfera" 🎈

**ESTADO: Finalizado Junio/2023 (CERRADO).**

El presente es una simulación de trayectoria ascendete y descendete de un globo-sonda hasta los 30 Km en el cual se  analizaron diferentes parámetros que se consideron clave a lo largo de su recorrido, se elaboró un análisis exploratorio (EDA) en los datos generados en la simulación  que finalizó con una propuesta de dimensionamiento a subsistema de navegación Low-cost, desarrollando su respectivo esquemático del circuito y layout de la PCB para una posible fabricación.  

Este es un proyecto de graduación, realizado en la [Universidad Don Bosco (UDB)](https://www.udb.edu.sv/udb/) por Osmin Larreynaga con asesoria de Msc. Napoleón Cornejo. Este microproyecto (trabajo de graduación) forma parte del macroproyecto "Diseño de una misión  globo de gran altitud - StratoBallon" realizado con una dependencia de la universidad llamada [Observatorio Micro Macro (OMM)](http://omm.udb.edu.sv/omm/public/) 

## Indice: 
- [Generalidades del Trabajo](#Generalidades-trabajo)
- [Estructura del repositorio (sub-carpetas)](#estructura-del-repositorio--sub-carpetas)
  * [Carpeta code](#estructura-del-repositorio--sub-carpetas)
  * [Carpeta document](#estructura-del-repositorio--sub-carpetas)
  * [Carpeta hardware](#estructura-del-repositorio--sub-carpetas)
- [Puntos destacados](#puntos-destacados)
- [Licencia](#licencia)

<h2> 
    <a name="Generalidades-trabajo"> </a>
    Generalidaddes del Trabajo ⚙️💡
</h2>  

Este repositorio incluye  como producto final lo siguiente:

* **Simulación:** Código fuente escrito en Python de la "Simulacion de trayectoria del Globo de Gran Altitud" haciendo usos de Jupyter Notebooks. [Ver código](https://github.com/osmin-lab/Proyec_Gda_Simula-PCB_Nav/tree/main/code) o revisar en la sigiente ruta `./code/src`.
* **Documento:**  Escrito final del proyecto de graduación desarrollado en $\LaTeX$, se registra académicamente en detalle y de forma formal en que consiste el presente trabajo. Puede ver el documento en PDF si desconoce sobre $\LaTeX$ click [aquí](https://github.com/osminlab/Proyec_Gda_Simula_PCB_Nav/blob/main/document/TrabajoGraduacion_2023_OsminLarreynaga.pdf) o en la siguietne ruta `./document/TrabajoGraduacion.pdf`.
* **Dimensionamiento subsistema de Navegación:** Se presentan el esquema circuito, layout y vista 3D en Fusion360, además se exportan a Eagle para mayor compatibilidad. [Ver propuesta](https://github.com/osmin-lab/Proyec_Gda_Simula-PCB_Nav/tree/main/hardware) o revisar en la sigiente ruta `./hardware`.

Todo lo anterior, fue divido en el actual directorio en sub-carpetas. Cada una continene el relativo producto final, revisesé según necesidad de consulta.

<h2> 
    <a name="estructura-del-repositorio--sub-carpetas"></a>
    Estructura del repositorio (sub-carpetas) 📂🗃️
</h2>  

La estructura del proyecto es la siguiente:

    ├── code            ◄---- Sub-carpeta. Códigos
    ├── document        ◄---- Sub-carpeta. Documentación de trabajo de graduación
    ├── hardware        ◄---- Sub-carpeta. Archivos de placa PCB.
    ├── .gitignore      ◄---- Archivo. Ignora archivos no vitales en el repositorio. 
    ├── LICENSES        ◄---- Sub-carpeta. Licencias del trabajo.
    └── README.md       ◄---- Archivo actual.

A continuación se detalla de forma breve el contenido de cada subcarpeta.

* **Carpeta code**: En el folder  `./code`  se encuentran todo lo relacionado con el simulador  y sus codigos respectivos en Python.

* **Carpeta document**: En `./document` se concentran todos los archivos relativos al documento final del trabajo que cualquier **${\LaTeX}$ editor** puede usar para mostrar el trabajo presente. El archivo principal esta localizado en `document/main_TrabajoGraduacion.tex`, este llama a todo los demás archivos relativos del documento incluyendo tablas, imagenes, capítulos, portada, etc.

    > **NOTA:** [main_TrabajoGraduacion.tex](https://github.com/osmin-lab/Proyec_Gda_Simula-PCB_Nav/blob/main/document/main_TrabajoGraduacion.tex) es el archivo principal del documento. El PDF final se puede encontrar [Aquí](https://github.com/osminlab/Proyec_Gda_Simula_PCB_Nav/blob/main/document/TrabajoGraduacion_2023_OsminLarreynaga.pdf). Este archivo es el responsable que el compilador de  $\LaTeX$ genere el documento. Sin embargo, para mantenener una código limpio, las secciones principales están localizadas en carpeta [sections](https://github.com/osmin-lab/Proyec_Gda_Simula-PCB_Nav/tree/main/document/sections).

* **Carpeta hardware**: En el folder  `./hardware`  se encuentran el dimensionamiento de subsistema de navegación. 

<h2> 
    <a name="puntos-destacados"></a>
    Puntos destacados 📝
</h2> 

Son detalles relevantes y generales  en  el trabajo podrían ser: 

* Se logró describir la trayectoria de un globo-sonda temporal y espacialmente, obteniendo gran cantidad de datos sobre parámetros que afecta la simulación. El simulador es preliminar, sin embargo, da buenas ideas del comportamiento de su recorrido.

* Se hizo una aproximación de forma introductoria a un subsistema de navegación para misiones Near-Space.

<h2> 
    <a name="licencia"></a>
    Licencia ®️
</h2> 

En general se pone a disposición de lo que tome como conveniente de licencia la [Universidad Don Bosco (UDB)](https://www.udb.edu.sv/udb/) en trabajos de este tipo. 
<br>

Sin embargo, de no decir lo anterior se tiene que:
- **Documento:** el documento de este trabajo como lo relativo al documento [`TrabajoGraduacion_2023_OsminLarreynaga.pdf`](https://github.com/osminlab/Proyec_Gda_Simula_PCB_Nav/blob/main/document/TrabajoGraduacion_2023_OsminLarreynaga.pdf) ubicado en carpeta `./document`, todo esta bajo licencia [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode). 

- **Hardware:** hablese de dimensionamiento de subsistema de navegación en carpeta `./hardware` bajo licencia [ CERN-OHL-P-2.0](https://ohwr.org/cern_ohl_p_v2.txt).

- **Software:** es decir códigos en python en carpeta `./code` bajo licencia [GNU LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.en.html#license-text).

En carpeta `LICENSES` se tiene un compendio donde se puede leer cada una de las licencias utilizadas en este trabajo.

