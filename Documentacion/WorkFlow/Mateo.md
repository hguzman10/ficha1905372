# ***Workflow***

 <>![](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRzkELPeOPDGhgbUijqVTKvYdGt2BapQVGKCq-T_h-onbtSpX_q&usqp=CAU)

1. ***¿Qué es?:***    
<br> *Un workflow es la automatización de los procesos de trabajo que desarrolla una empresa en su día a día, de tal forma que las tareas a realizar y la información pasen de un trabajador a otro siguiendo una jerarquía determinada y siguiendo unas reglas o patrones preestablecidos con anterioridad. Esta definición es bastante previsible y lógica, dado que ya simplemente con su traducción al castellano, que es literalmente: flujo de trabajo, nos podemos hacer una idea general de lo que engloba. Eso sí, como bien imaginarás, una descripción tan escueta no logra abarcar todos los matices que implica este término, por lo que se hace necesario entrar en más detalles. En teoría, esta gestión se puede organizar de forma manual, pero actualmente la mayor parte del workflow se sistematiza en el contexto de la tecnología de la información, más conocido como sistemas de TI.*
![](https://cdn.semrush.com/blog/static/media/f4/51/f451ec75492ea3f68932e8c6ea97ae0e/resize/885x-/que-es-un-workflow.webp)
------------
2. ***¿Cómo mejora los procesos de negocio?:***
<br><br> *Son un conjunto de herramientas que cuando se observan bajo un punto de vista macroambiental, forman un puente entre las eventuales unidades de producción y la oficina de una empresa determinada. Mientras tanto, si se analiza a nivel microambiental, esta tecnología conecta los sistemas de TI a la cultura de las propias empresas y por lo tanto termina conectando a los empleados con los procesos de negocio propiamente dichos. En general, la tecnología workflow no sólo asegura la comunicación e intercambio de información entre los diferentes departamentos implicados en el mismo proceso de negocio, sino que asegura que todas las tareas sean ejecutadas por el empleado a quien fueron destinadas.*
------
3. ***¿Cómo hacer un flujo de trabajo?:***
<br>***Encontramos tres categorías:***

|***Categoría*** | ***Definición***                   |
|---------------|-------------------------------------|
|***Workflow Ad hoc***|*Las reglas y normas de este sistema de trabajo no son rígidas, sino todo lo contrario.Pueden ser modificadas durante el proceso de trabajo en función de las necesidades que vayan surgiendo.*|
|***Workflow de producción***| *Al contrario que en el anterior sistema, su flexibilidad es muy limitada.En este caso, sigue una dirección preestablecida y ampliamente conocida por todos los trabajadores.*|
|***Workflow administrativo***|*Este tercer sistema se encuentra a caballo entre el ad hoc y el de producción.Suele implementarse para la realización de tareas sin estructura definida, repetitivas, previsibles y con reglas de coordinación relativamente simples.*|
--------
4. ***Pasos para crear el workflow***

* ***Definir los objetivos:*** *En primer lugar, has de tener claro cuáles son los objetivos a conseguir.
Esta será la piedra sobre la que comiences a construir tu sistema de automatización de procesos, por lo que deberás ser lo más preciso y concreto posible.Para ello, has de valorar toda la información de la que dispongas.En el futuro, tener bien definidos los objetivos te ayudará en la medición y valoración de los resultados que se obtengan.*

* ***Diseñar:*** *La mejor forma de realizar este paso es mediante un apoyo visual.Elabora un dibujo o un esquema en el que queden plasmados los pasos que se deben seguir y las posibles variaciones en la ruta, de tal forma que el flujo de trabajo de la empresa quede bien definido. Es fundamental que no quede ningún escenario por contemplar, ya que eso provocaría que todo el proceso careciera de sentido.*

* ***Implementar:*** *Durante esta fase pondrás a prueba lo realizado en las dos anteriores.Primero has de realizar pruebas con un usuario ficticio y, posteriormente, debes pasar a hacerlas con una pequeña muestra de usuarios. De esta forma, evitarás que se produzcan errores masivos que podrían dañar la imagen de la empresa e incluso provocar una crisis reputacional.*

* ***Medir los resultados:*** *Si quedaron definidos correctamente los objetivos en la primera fase, ahora podrás evaluar el rendimiento obtenido mediante algunas métricas relevantes. Es muy importante tener todo claro, porque si los objetivos no quedan bien planteados significaría un retroceso.*

![](https://www.heflo.com/es/wp-content/uploads/sites/6/2017/12/workflow-management-1-1280x720.jpg)

----

5. ***Beneficios de utilizar el workflow***

* *Mejora la eficiencia de las empresas en los desarrollos ya que disminuye los tiempos de trabajo.*

* *Los procesos son más organizados, porque se controla todas las actividades.*

* *Mejor atención y servicio al cliente; un incremento en la coherencia de los procesos da lugar a una mayor previsibilidad en los niveles de respuesta a los clientes.*

* *Mejora en los procesos; mayor flexibilidad de acuerdo con las necesidades empresariales.* 

* *Optimización de la circulación de información interna con clientes y proveedores.*

* *Los procesos empresariales van llevados de la mano por los tecnológicos.*

------

6. ***Git workflow***

<br>*Git-flow es un conjunto de extensiones para Git, basado en el modelo de ramificaciones de Vincent Driessen, que nos facilita el trabajo con nuestros repositorios. Básicamente, git-flow agrega comandos de alto nivel que, por detrás, usan los comandos tradicionales de Git. El trabajo se distribuye en dos ramas **master** y **develop***

***Organización:***
* ***Rama master:*** *la rama que contiene el código que está en producción. A esta rama, sólo debe llegar código que está en o está listo para estar en producción.*

* ***Rama develop:*** *la rama que contiene las features a incluir en una próxima salida a producción (pasando por test previamente). Todos los desarrollos que hagamos nuevos módulos, refactorings, etc. se guardarán en Develop, a la espera de salir a producción.*

*Cada vez que se incorpora código a master, tenemos una nueva versión.*
*Además de estas dos ramas, Se proponen las siguientes ramas auxiliares:*
1. *Feature:*
* *Se originan a partir de la rama develop*
* *Se incorporan siempre a la rama develop*
* *Nombre: cualquiera que no sea master, develop, hotfix o release*

![](/Documentacion/Imagenes/feature_branches.png)

2. *Realease:*
* *Se originan a partir de la rama develop*
* *Se incorporan a master y develop*
* *Nombre: release-*

*Estas ramas se utilizan para preparar el siguiente código en producción. En estas ramas se hacen los últimos ajustes y se corrigen los últimos bugs antes de pasar el código a producción incorporándolo a la rama master.*

3. *Hotfix:*
* *Se origina a partir de la rama master*
* *Se incorporan a la master y develop*
* *Nombre: hotfix-*

*Estas se crean para correjir errores y bugs del codigo de producción a difirencia de la rama realease estas no se planifican*

![](/Documentacion/Imagenes/hotfix.png)

**Git-Flow:**

![](https://image.slidesharecdn.com/letsyourcollaboratorsmorehappywithgitflow-161102040705/95/lets-your-collaborators-more-happy-with-git-flow-1-638.jpg?cb=1478059844)



