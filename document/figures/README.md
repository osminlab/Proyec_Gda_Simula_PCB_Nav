# **Imágenes:** Trabajo de Graduación.

Directorio en el que se organizan todas las imagenes que se inserten en el documento, de forma que se facilite su uso a la hora de escribir el path en los includegraphics.

Por ejemplo, en el documento de $\LaTeX{}$ sería:
```latex
\includegraphics[width=0.95\linewidth]{document/figures/02_DCL_movimiento.png}
```
O también:
```latex
\begin{figure}[h]
    \centering
    \includegraphics[scale=0.25]{document/figures/02_ECEF_coordinates.png}
    \caption{Sistema de coordenadas}
    \label{fig:crs}
\end{figure}
```

> ***Nota:** En carpeta `LICENSES` se coloca una licencia por las imágenes que no poseeian autoria propia. 