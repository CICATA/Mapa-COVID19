# Instituto Politécnico Nacional

##  Visualización de la Dispersión de COVID-19 en México

En sus cortes diarios, la Organización Mundial de la Salud [1] reporta el número de personas infectadas y fallecidas por COVID-19 en el mundo. Ante el escenario de pandemia, contar con información granular es crucial para la toma de decisiones que incluyen el destino de los recursos de apoyo y el retorno a la normalidad. Con la finalidad de apoyar la toma informada de decisiones, ponemos disponible para el público un mapa interactivo con datos de casos de COVID-19 desagregado por municipio, tal como lo reporta la Secretaría de Salud, en la dirección https://arcg.is/1qy1Wy</br>

Los datos son filtrados por características que incluyen aquellos pacientes confirmados, fallecidos y sospechosos. En el caso de pacientes confirmados, la prueba última de contagio a COVID-19 es el resultado en los ensayos de reacción en cadena de polimerasa de transcripción inversa en tiempo real (qRT PCR), las cuales son técnicas moleculares que consisten en obtener un gran número de copias de un fragmento de ácidos nucleicos. En principio, la amplificación permite identificar o descartar con una alta probabilidad el SARS-CoV-2 en la muestra, requiriendo en promedio 5.2 copias del marcador de proteína de la envoltura del gen E y 3.8 copias de la polimerasa del gen RdRp para una probabilidad de detección del 95% [3]. En el caso de los pacientes fallecidos, estos han sido previamente confirmados como positivos a COVID-19, mientras que los pacientes sospechosos son aquellos para los que se está en espera del resultado en la prueba molecular. Las variables sobre pacientes confirmados, fallecidos y sospechosos son sumarizadas por municipio y estado de la república. Para calcular las estadísticas por municipio importamos los datos públicos al sistema de gestión de bases de datos FileMaker, donde los datos son sumarizados.</br>

Para la representación geográfica de las estadísticas utilizamos arcGIS Online, un software para la georreferenciación de información que opera bajo el principio de capas de procesamiento de datos. En arcGIS, tenemos una capa de datos, una capa de mapa y un tablero de representación de información. Los datos suministrados son los descritos en el párrafo anterior. La capa del mapa ofrece una representación georreferenciada de los datos y permite tener opciones sobre la figura, tamaño y color con el que visualmente ocurre la visualización. Finalmente, el tablero de representación sumariza datos y combina formas gráficas con datos cuantitativos. 
Para todos los casos, hemos elegido listar todos aquellos municipios para los cuales el número de casos es mayor a 0 (cero). En el caso de aquellas personas que no tienen registrado un municipio de residencia, pero sí un estado, les asignamos geográficamente la capital respectiva de la entidad federativa. En el mapa se puede apreciar fácilmente que los municipios y estados con mayor número de casos de infección, fallecimientos y sospechas. Los datos son actualizados en nuestra representación visual, conforme las Secretaría de Salud libera nueva información. </br>


## Participantes
* Dagoberto Pulido Arias
* Mayra Candido
* Joaquín Salas


## Ligas de Interés
*[Link al mapa aquí](https://arcg.is/1qy1Wy)</br>
*[Información sobre Equipo de Protección Personal, aquí](https://github.com/CICATA/covid19)


## Mayor información:
Instituto Politécnico Nacional</br>
Cerro Blanco 141, Colinas del Cimatario</br>
Querétaro, 76090, México</br>
jsalasr@ipn.mx ó salas@ieee.org</br>
Joaquín Salas</br>

## Navegadores recomendados 
* Google Chrome
* Mozilla Firefox
* Microsoft Edge


## Referencias
[1]	World Health Organization. Coronavirus disease 2019 (COVID-19) Situation Report – 90. [Disponible aquí](https://tinyurl.com/who-covid19-situation)</br>
[2]	Secretaria de Salud, México. Información referente a casos COVID-19 en México. [Disponible aquí](https://tinyurl.com/mexico-covid)</br>
[3]	Corman V., Land O., Kaiser M., Molenkamp R., Meijer A., Chu D., Bleicker T., Brúnink S., Schneider J., Schmidt M., Detection of 2019 novel coronavirus (2019-nCoV) by real-time RT-PCR.  Eurosurveillance. 2020;25(3). [Disponible aquí](https://tinyurl.com/eu-cdc-test)</br>




 

