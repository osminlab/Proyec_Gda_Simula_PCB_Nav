# Documentación  del Trabajo de Graduación

Se recoge todo lo necesario con lo que se redactó el trabajo graduación en la Universidad Don Bosco de El Salvador.

Si se usa como plantilla no es oficial debido a que la Universiad no tiene una de forma unanime se hizo en base a "lo que un trabajo debe de tener". Sin embargo, cambiado y añadido información en pos ayudar podría facilitar su uso y desarrollo de un trabajo de graduación.

La estructura del directorio es la siguiente:

    .
    ├── README.md                           ◄---- Archivo actual. 
    |
    ├── annexes                             ◄---- Directorio con pdf's para anexos
    │   ├── PCB_layout.pdf
    │   ├── esquematico.pdf
    │   └── seleccion_hardware.pdf
    |
    ├── figures                             ◄---- Sub-carpeta con imagenes del documento
    │   ├── 01_componentes del globo.jpeg
    │   ├── 01_etapas de la mision.png
    │   └── (...)
    |
    ├── include                             ◄---- Directorio con la definiciónes y configuraciones
    │   ├── Portada.tex
    │   ├── Preambulo.tex
    │   └── (...)
    |
    ├── main_TrabajoGraduacion.tex          ◄---- Archivo principal LaTeX.
    |
    ├── plan-trabajo                    
    │   ├── GanttDiagram.tex
    │   └── plan-de-trabajo.tex
    |
    ├── sections                            ◄---- Sub-carpeta con los capitulos del documento
    │   ├── 00_Resumen.tex
    │   ├── 01_Introduccion.tex
    │   └── (...)
    |
    └── table                               ◄---- Directorio con las tablas.
        ├── 02_constantes_ISA.tex
        ├── 02_datos_iniciales.tex
        └── (...)                   

En **Documento principal o archivo principal de $\LaTeX{}$** en el que se incluyen, mediante las sentencias "input", la portada y todas las secciones definidas en "secciones", así como la información del alumno y todos los paquetes. 

## Comentarios:

En cualquier caso, son los autores   involucrados en un trabajo de graduación quienes indicarán  la estructura del trabajo de graduación ha desarrollar.

    Se es libre de editar según las necesidades.

## Licencia 

En carpeta `./document`, todo esta bajo licencia [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode), ver carpeta `LICENSES`.
