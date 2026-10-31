## M03- SEGUIDOR DE LINEA

César Ortega Martínez - A00585262 Michelle Corona Martínez - A00575178 Diego Adiel Flores Navarro - A00573953

## IDEA

Un seguidor de linea a velocidad constante y queremos que no pierda la línea

## SCAMPER

- Sustituir: Cambiar la matriz de 8 QTR por otra que contenga más sensores.

- Adapatar: Calibrar los QTR con objetos más blancos o negros para dejar más claro el umbral de los valores para los QTR.

- Modificar: Modificar la posición de los QTR para que estén más cerca del resto del seguidor y no equivocarse al tener falsos positivos debido a su largo

## OPCIONES DADAS POR LA IA

- 1. Sustituir: el arreglo de sensores completo por solo los 4 sensores centrales de la matriz, leídos con mayor resolución

- Idea: dejar de procesar los 8 canales y usar solo los 4 del centro, promediando varias muestras de cada uno. Así se reduce la información, pero se obtiene una lectura más limpia y más rápida de la zona donde está la línea.

- Ventaja: menos canales que leer y menos ruido por sensor, lo que da una posición más estable cuando el robot va cerca de la línea.

- Riesgo: con solo 4 sensores se reduce el rango de detección, y si la línea se sale de esa zona el robot la pierde antes.

- Requisito: que el ancho de la línea y la separación entre sensores permitan cubrirla con los 4 centrales, y medir cuánto tarda el ciclo con 4 canales contra 8.

- Validación: salidas por vuelta en la misma pista, comparando 8 sensores contra 4 centrales con promedio de muestras.

2. Adaptar: las ruedas de goma a otro material o diámetro para mejorar la tracción

- Idea: probar ruedas con otro compuesto de goma o un diámetro distinto, o agregar una banda de goma a las ruedas actuales.

- Ventaja: menos derrape en curvas sin tocar el código.

- Riesgo: un diámetro distinto cambia la velocidad real del robot y puede rozar la carcasa.

- Requisito: ruedas compatibles con el eje de sus motores y espacio en la carcasa.

- Validación: salidas por vuelta en curvas con las ruedas actuales contra las nuevas, en la misma pista.


- 3. Modificar: la separación física entre los cables de los sensores y los de los motores

- Idea: reacomodar el cableado (cables más cortos, separados y trenzados, con la alimentación de la matriz alejada de la del driver) para que el ruido de los motores no altere las lecturas analógicas de los 8 sensores.

- Ventaja: lecturas más estables sin tocar el código, así que el robot no se desvía por falsas lecturas.

- Riesgo: un cableado más corto o recogido puede aflojar conexiones de los jumpers o dificultar el mantenimiento.

- Requisito: poder mover la matriz y el driver dentro de la carcasa, y tener jumpers de la longitud adecuada.

- Validación: variación de las lecturas de los 8 sensores con los motores encendidos contra apagados, antes y después del cambio, y salidas por vuelta en la misma pista.

## PROPUESTA FINAL

- Se trata del cambio de los cables y su reacomodo para quedar más cortos y separados para eliminar el posible ruido causado tanto por la longitud y distancia que hay entre la placa y la matriz de sensores, como por la calidad de los cables.

- La idea sería, en vez de usar cables jumpers que, por la posición de la matriz, quedan muy estirados por la parte de arriba, usar un cable directamente soldado de la placa a la matriz. Gracias a esto, también estaría más ajustado a las dimensiones finales del seguidor de línea. También podemos hacer uso de conectores, como los JST o cables de cinta, para facilitar el reacomodo, pero sin sacrificar seguridad.

- Se espera que gracias a este cambio las falsos positivos que existen durante la calibración y las pruebas del seguidor de línea disminuyan de una manera considerable

- La viabilidad se ve alterada un poco por cómo se probaría de manera correcta, pues lo mejor sería usar una nueva placa para probar todo correctamente, pero sería gastar en más componentes, por lo que sería probar con los jumpers, quitarlos y agregar el cable.

- El riesgo sería que algún cable no quede bien soldado y empeore la calibración.

- Y la prueba sería hacer varias calibraciones para ver cuál nos termina dando mejores resultados, además de utilizar el multimetrp para verificar continuidad y asi tener un poco más de certeza de que la corriente esta llegando a su destino.

## REFLEXIÓN

César: La IA fue una herramienta importante durante este reto, pues nos dio una lista de posibles tareas, que sin duda nos ayudaron a organizar nuestro desarrollo del producto, nos ayudo a darle forma a la idea y a la organización.

Tambien nos aportó ideas, algunas de ellas ya la habias identificado un poco durante el desarrollo del proyecto (como los posibles falsos de los cables) y otras ideas fueron totalmente nuevas (como la radical idea de usar menos sensores). Estas ideas nos dan una nueva rama de pensamiento para desarrolloar las propias o reafirma las que ya teniamos, dandonos un buen impulso para emepzar el desarrollo.

Michelle: La Inteligencia Artíficial nos ayudó como herramienta para replantear el problema más allá de lo que veíamos (principalmente el software), ya que nos permitió preguntarnos sobre la estabilidad del hardware y sugerir diferentes soluciones. Aunque propuso cosas que nos parecieron descabelladas, al final del día las decisiones las tomamos nosotros priorizando una mejora real sobre el desempeño y las lecturas que presentaba el seguidor de línea.

Diego: La IA puede funcionar muy bien para generar alguna idea de manera rápida y ver qué tan factible es, claramente, no se debe tomar únicamente lo que la Ia diga como ley. Por lo que en este trabajo es una buena idea usarlo para cosas como el SCAMPER para ver varias propuestas, soluciones que sean medianamente factibles, pero al final del día se tiene que verificar por una persona, además de investigarse más a fondo, discutirlas y tomar las partes que pueden funcionar y descartar las que no se puedan aplicar.
