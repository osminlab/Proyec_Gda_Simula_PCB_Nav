# Hardware, Subsistema de Navegación ⚙

Se ilustra el dimensionamiento, a continuación: 

<br>
<p align="middle">
  <img width="900" src="../document/figures/04_PCB v1_3D.png">
</p>
<br>

Si se desea saber lo perteneciendo a esto por favor leer el documento, y el capítulo 4 del trabajo de graduación. Ver PDF del trabajo de graduación [[aquí](https://github.com/osminlab/Proyec_Gda_Simula_PCB_Nav/blob/main/document/TrabajoGraduacion_2023_OsminLarreynaga.pdf)]  o en la presente carpeta en archivo `/document/TrabajoGraduacion.pdf`. 
<br>
<br>

## Detalles Subsistema de Navegación:

Debido a que es un dimensionamiento lo siguiente puede variar, pero se recomienda en carecidamente tenerlas en cuenta:
- Placa de circuito impreso, en los archivos gerber comprimidos, listos para realizar pruebas con los módulos. Si las pruebas son exitosas, puede fabricarse utilizando FR4 estándar para prototipos e Isola FR408HR para vuelo.
- Se utilizaron los siguientes modulos/sensores: como GNSS ([Neo-M9N SparkFun](https://www.sparkfun.com/products/17285)), como registro de vuelo ([Open Log](https://www.sparkfun.com/products/13712)), como sensor barométrico ([MS5611-01BA03](https://www.te.com/commerce/DocumentDelivery/DDEController?Action=showdoc&DocId=Data+Sheet%7FMS5611-01BA03%7FB3%7Fpdf%7FEnglish%7FENG_DS_MS5611-01BA03_B3.pdf%7FCAT-BLPS0036)), como sensor inercial/IMU ([LSM9DS1](https://www.adafruit.com/product/4634)).  Los siguientes pueden ser opcionales: sensor de temperatura (PT1000) y computadora de vuelo (Arduino Nano o STM32 NUCLEO-L432KC).

<br>

## Recomendación

Lo mostrado en este trabajo fue una propuesta en base a la bibliografía consultada, no se realizaron ninguna tipo de pruebas ni de funcionamiento ni de las condiciones atmosféricas. Tomar estra propuesta con el respectivo cuidado y de retomarse hacer las pruebas pertinentes.

Si se desea retomar este trabajo por favor realizar pruebas de funcionamientos con los módulos presentados.


## Licencia 

En carpeta `./hardware` bajo licencia [ CERN-OHL-P-2.0](https://ohwr.org/cern_ohl_p_v2.txt).
