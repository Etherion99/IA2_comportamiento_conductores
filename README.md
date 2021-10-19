# Clasificación del comportamiento de conductores
<img src="banner.jpg">

Un conductor está expuesto a muchas distracciones, las cuales pueden llevar a accidentes en la carretera. Estas distracciones pueden ser identificadas por medio de las acciones del conductor, como hablar por celular o ver hacia otros lados. En este proyecto se desarrolla una red convolucional que identifique el comportamiento del conductor respecto a si se encuentra distraído o no por medio de la captura de imágenes del mismo. Los resultados de la clasificación obtenida presentaron buenas métricas, alcanzando un 98% de clasificación para las imágenes de prueba, por otro lado, la aplicación a video presentó resultados coherentes.

<b>Autores</b><br>
Juan Sebastian Estupiñan Cobos 2180056<br>
Sebastian Rivera León 2180033<br>
Juan Sebastian Trujillo - 2160602

<b>Objetivo</b><br>
El proyecto nace con el objetivo de brindar una base que permita monitorear el comportamiento de los conductores,
esta motivación surge al observar la vida cotidiana, en donde gran variedad de conductores están expuestos a muchas distracciones
que desafortunadamente pueden terminar en accidentes, por lo que, tener un constante conocimiento de lo que sucede en el puesto
de conductor puede ayudar a evitar estas situaciones y brindar mayor seguridad al conductor y a los pasajeros de cualquier vehiculo.

<b>Dataset</b><br>
Se cuenta con un conjunto de datos que presenta multiples imagenes de conductores clasificadas según sus tipos de comportamiento, de las cuales se usarán las 5 primeras carpetas, que corresponden a comportamientos con el celular https://www.kaggle.com/mikoaro/distracteddriver

<b>Modelos</b><br>
Modelo VGG16 pre-entrenado con las últimas 2 capas descongeladas y conectado a 2 capas densas de 256 y 128 ambas con activación relu, optimizador Adam.

<b>Enlaces</b><br>
<a href="https://github.com/Etherion99/IA2_comportamiento_conductores">(code)</a> <a href="https://www.youtube.com/watch?v=hc4-Ou34ukk">(video)</a> <a href="https://github.com/Etherion99/IA2_comportamiento_conductores/blob/main/presentaci%C3%B3n.pptx">(+info)</a>
