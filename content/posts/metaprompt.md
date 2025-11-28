---
title: "Metaprompt, ¿La solución definitiva?"
date: 2025-10-20T15:49:00-05:00
draft: false
---


Partimos del hecho de que podemos hablar en lenguaje natural con un LLM, español, francés o inglés, parece que nos entienden y contestan de forma muy coherente. Incluso usamos términos humanos para referirnos a estos modelos y sus aplicaciones: neuronas, inteligencia, aprendizaje, contexto, alucinación, memoria. Esto puede inducirnos erróneamente a creer que estamos tratando con una entidad consciente, a pesar de esto, lo inteligente es tratarlos como una persona, solo así vamos a poder explotar toda su capacidad.

Desde hace un par de años la red está plagada de prompts, *los 10 mejores prompts para esto*, *el prompt definitivo para esto otro*, *las mejores prácticas para prompts*, *técnicas avanzadas de prompts*, e incluso (y algo inquietante para los ingenieros reales) “*ingeniería de prompts*”. ¿Porqué tanta parafernalia si las IA hablan español? puedo preguntarles y ya, ¿cuál es el problema?

Pues resulta que si, las IA hablan en lenguaje natural, pero necesitan un contexto, en nuestra vida normal nos comunicamos con personas que nos conocen y con las que ya hemos hablado, yo no llego todos los días a mi oficina a decir mi nombre y mi ocupación a todos mis compañeros. De hecho también tenemos contexto con personas que no conocemos, cuando me subo al metro todos sabemos de donde viene, hacia donde se dirige, que estaciones recoge, cuáles son las reglas básicas de uso, incluso sabemos que clima ha estado haciendo o si las estaciones se llenan más o menos a determinada hora.

Ya tenemos entonces una primera regla para entendernos con la IA, debemos darle contexto, quienes somos, que hacemos, que antecedentes tiene nuestra petición. Los proveedores de IA notaron esto y han construido todo un ecosistema de funcionalidades que van almacenando nuestra interacción, gpt’s, espacios, proyectos, gems, shortcuts, memorias, system prompts. Un consejo ampliamente aceptado cuando se usa un entorno como el de ChatGPT es usarlo para todo, desde que me levanto hasta que me acuesto, cosas personales y laborales, para que cada vez me “conozca” más, de esta forma cada vez va a tener más contexto sobre mi y la experiencia de comunicación se acercará más a una interacción humana.

Pero hay una cuestión, en nuestras relaciones con familiares, amigos y colegas ¿la comunicación siempre funciona? ¿nunca hay malentendidos? yo creo que si los hay, y muchas veces tienen que ver con el contexto, el punto de vista, la información que posee cada participante de la comunicación, esperamos de la IA comportamientos que incluso a nosotros se nos dificultan.

¿Y que pasa si hablamos con una persona de otra región del pais? ¿de otro pais? ¿de otra cultura? ¿en otro idioma? ¿de otra generación? posiblemente el lenguaje sea diferente, algunos términos varíen incluso en el mismo idioma, o incluso la profesión, una conversación sobre COVID puede ser muy diferente entre dos médicos y dos personas del común, incluso dos epidemiólogos tratarían el tema diferente que dos médicos internistas.

Entonces tenemos otro aspecto a tener en cuenta, el léxico, el hecho de que la IA tenga datos de entrenamiento de todas las áreas de conocimiento y en muchos idiomas (no digo todos porque sabemos que algunas lenguas nativas no están incluídas) quiere decir que no habla como nuestro vecino (ni como nosotros). Esto implica que tenemos que ser muy asertivos en la comunicación para expresar correctamente lo que queremos y así obtener respuestas útiles.

Hay otro elemento importante a tener en cuenta, pensemos en esto, la IA lo sabe todo sobre todo (o eso piensa ella), y si le preguntamos sobre algo que ignora, o aún más probable, no le preguntamos bien y dejamos espacio para diferentes interpretaciones, puede ocurrir que obtengamos una respuesta totalmente fuera de lugar, entonces decimos que está alucinando, esencialmente nos engaña (decir esto último no es precisamente correcto pero así se siente cuando la IA alucina). ¿Qué ocurrió? sin adentrarnos en las características internas de un modelo de IA y teniendo en cuenta que las alucinaciones no tienen una explicación muy clara, yo creo que parte de la responsabilidad es nuestra por no preguntar bien, así se simple.

Voy a intentar ilustrar estos tres puntos con un ejemplo de mi experiencia con la IA, hace diez años tengo una gata que enfermó recientemente y fue necesario someterla a numerosos exámenes y a un tratamiento muy largo con antibióticos, simultáneamente llegó a nuestro hogar un nuevo gatico, esto causó muchas situaciones particulares de cada uno y situaciones entre ambos, el veterinario nos daba su punto de vista y le hicimos preguntas generales sobre la situación. 

Ahora vamos a una situación puntual, el gatico se intenta acercar a la gata con actitud juguetona y la gata lo ataca, Le hago esta pregunta a ChatGPT: "¿Qué hacer si un gato ataca a otro?" obtengo una respuesta larga, genérica, con muchos consejos que se podrían aplicar a muchas situaciones de gatos, al final me hace algunas preguntas intentando llegar a una mejor respuesta. Entre otras cosas menciona los cuidados que debo tener al separarlos y algunas medidas posteriores recomendadas. Una técnica muy popular para redactar prompts es la impersonación, osea decirle a la IA quién es ella y quién soy yo, entonces podría mejorar mi pregunta con algo como "Eres un veterinario experto en gatos y yo soy el dueño novato de dos gatos, ¿qué debo hacer si un gato ataca a otro?" La IA me da una respuesta casi idéntica a la primera, ¿entonces esa técnica no funciona? pues la verdad es que a medida que se liberan al mercado nuevos modelos y nuevas interfases las IA's están más adiestradas para intentar determinar el contexto, por lo tanto ya en mi primera pregunta la IA sabía que no debía responder como un ingeniero.

De nuevo voy con la misma IA y hago una consulta más elaborada:

"Rol: Eres un etólogo felino especializado en educación y modificación de conducta, y en el vínculo humano-animal. Tienes experiencia profesional en el análisis del comportamiento de gatos domésticos y en el diseño de estrategias de convivencia. El usuario es tutor de dos gatos:

* Gata de 10 años, adoptada desde bebé, personalidad temerosa y desconfiada . Actualmente se recupera de una infección bacteriana intestinal. Duerme en la cama pero mantiene distancia.

* Gato de 2 meses, vive desde su nacimiento con el tutor, personalidad energética y confiada, muy sociable, duerme cerca del humano. Intenta constantemente acercarse a la gata mayor, quien responde con agresividad.

Situación: la gata ataca al gato cuando intenga jugar

Consulta: qué actitud tomar ante esta situación y como manejar su relación?"

La respuesta ya no es genérica, esta vez sentí como si hubiera llevado a los gatos donde el psicólogo, obtuve una respuesta personalizada con la explicación del comportamiento de cada gato desde su proceso particular, esto contestó:

"Perfecto, gracias por la descripción tan clara — eso ayuda mucho a ajustar las recomendaciones.
Tienes una situación muy típica pero sensible: una gata adulta con un carácter inseguro que debe adaptarse a un cachorro energético y curioso. Vamos paso a paso para proteger el bienestar emocional de ambos y favorecer un vínculo equilibrado.

1. Entender la dinámica actual: (Explicación de la situación desde el proceso de cada gato)
2. Manejo ambiental: (Consejos prácticos de manejo de espacios, intercambio de olores y uso de feromonas sintéticas)
3. Interacciones progresivas: (Proceso en tres etapas detalladas para mejorar la situación)
4. Actitud del tutor: (Cómo debo comportarme yo)
5. Señales de progreso
6. Señales de alerta para consultar un profesional"

Para no alargar el relato, no incluí acá todos los detalles de la respuesta, la información entre paréntesis la agregué para indicar lo que la IA desarrolló en esa sección, pero es muy fácil ir con una IA, copiar y pegar el mismo prompt que usé y obtener una respuesta completa.

Incluso la sección final en la que la IA me ofrece ir más allá luce mucho más profesional.

¿Entonces acá si funcionó la impersonación? Bueno, eso y el contexto, además están claras las secciones, rol, contexto, situación y consulta específica. En definitiva es un prompt más elaborado. Acá vienen entonces las técnicas para "convencer" a la IA de que nos diga lo que necesitamos: dar un ejemplo, establecer los pasos de la respuesta, especificar un razonamiento específico, son entre muchas otras, algunas técnicas que se usan para mejorar los prompts. ¿Entonces que hacer? Ahora ya si comienza a parecer una ingeniería (obvio no :D), pero la realidad es que es un campo tan vasto que algo que al principio algunos comenzamos a usar para ayudarnos a realizar esas contrucciones gramaticales super detalladas se fue consolidando, y es que la intuición nos decía "¿Quién va a saber hablarle a una IA mejor que otra IA?”,  pedirle a una IA que redacte un prompt se volvió una práctica popular y tomó el nombre de metaprompt.

Esto ahora si parece la solución definitiva, ni siquiera tengo que entender cómo debo comunicarme con la IA, o como funciona, sólo voy con una IA y le digo "ayúdame a redactar un prompt para solicitarle esto a esta otra IA" y plum! aparece un texto largo que parece redactado por un experto, hagamos la prueba:

"Necesito que diseñes un prompt para hacer consultas a ChatGPT sobre comportamiento de gatos"

Y obtengo estas primeras líneas:

"Prompt general para consultas sobre comportamiento felino:

PROMPT:
Actúa como un experto en comportamiento felino con formación en etología y experiencia clínica con gatos domésticos.

Tu tarea es ayudarme a entender y resolver problemas relacionados con el comportamiento de mi gato, usando explicaciones basadas en ciencia y buenas prácticas de bienestar animal.

Cuando respondas:

Usa un tono empático, claro y sin juicios.
Explica el por qué del comportamiento felino de manera sencilla.
Propón soluciones prácticas y seguras, indicando cuándo es recomendable acudir a un veterinario o etólogo.
Si es necesario, formula preguntas para comprender mejor el caso.
Consulta: [Aquí escribes tu pregunta o describes la situación con tu gato]"

Al final añade algunos ejemplos y unas variantes de tono para afinar las respuestas.

En principio parece funcionar, no me esforcé mucho y obtuve un prompt profesional, usé entonces ese prompt para agregar mi consulta:

"Consulta: que hacer cuando uno de mis gatos ataca a otro"

Obtengo una respuesta parecida a del prompt que yo diseñé pero con muchas más opciones porque en realidad no está clara la causa del comportamiento, sin embargo me pregunta esto (tal como se lo solicitamos en la petición):

"Para ayudarte mejor, necesito saber:

¿Desde cuándo ocurre este comportamiento?
¿Qué gato inicia el ataque (sexo, edad, relación previa)?
¿Qué pasa justo antes del ataque (ruidos, juego, alimentación, contacto visual, etc.)?
¿Cómo reacciona el gato agredido (se esconde, responde, vocaliza, etc.)?
¿Han tenido peleas físicas con heridas o solo amenazas (bufidos, persecuciones)?"

Puedo utilizar algo que usamos todo el tiempo sin pensar en el hecho de que es una técnica de ingeniería de prompts: la iteración, puedo ir contestando las preguntas e iré obteniendo una solución más adecuada a mi situación particular.

Bueno, hasta acá llega este artículo sobre la gran utilidad del metaprompt.

Mentí (diría que aluciné para estar dentro del contexto), no es el final, ¿y qué pasa si te digo que no es tan maravilloso? ¿qué problema puede tener algo que parece funcionar muy bien sin mucho esfuerzo? veamos.

La verdad es que el metaprompt si es una técnica muy útil, a partir de preguntas muy básicas podemos obtener instrucciones muy elaboradas y, a primera vista, con todo lo que podríamos necesitar. Hay incluso corrientes entre los que sostienen que tal o cuál IA escriben mejores prompts para las otras o cosas como que en la solicitud hay que indicar la IA de destino para obtener mejores resultados. Como todo en la IA cada uno lo hace de la manera que parece funcionarle en su caso.

Hay varios sesgos cognitivos que nos impedirían juzgar de manera crítica el resultado, pero creo que en la mayoría de los casos se podría hablar del sesgo de autoridad, que ocurre cuando aceptamos el resultado de la IA  porque percibimos que es "experta" o más competente que nosotros en el tema. Creemos que leer rápidamente es verificar y más allá de ajustes estéticos, no cuestionamos el resultado con lo que básicamente estamos delegando la decisión a la IA. Y este para mi sería el segundo problema, se supone que tenemos una herramienta cognitiva muy poderosa, a la que podemos pedir casi cualquier cosa, lo único que tenemos que hacer es precismente eso, pedirlo, pero también queremos que eso lo haga ella misma, con la deuda cognitiva que esto conlleva para nosotros. 

Vamos a ver un poco más en profundidad ambos puntos, en una entrevista con la revista Wired Japon el historiador Yuval Noah Harari comenta “Personas que ni siquiera confían en otros seres humanos, de alguna manera creen que pueden confiar en esta IA alienígena” y agrega “Creo que es un grave error asumir que se puede confiar en la IA cuando no se confía entre nosotros”, ¿porqué confiamos tanto en lo que nos dice la IA? la consecuencia no deseada de esto es que asumimos que la respuesta es correcta, y cuando se trata de un tema que no dominamos, incluso carecemos de la capacidad para validarla. Es decir, para comunicarnos con la IA debemos estructurar nuestra petición, pero en lugar de eso le decimos a la IA que nos ayude a preguntarle a ella misma (así sean IAs diferentes) y luego confiamos ciegamente en lo que obtenemos. Y esos resultados los utilizamos para estudiar, para el trabajo, en nuestras decisiones del hogar, de nuestra vida. El metaprompt agudiza este efecto porque nos hace pensar que este paso intermedio de asistirnos con la IA para diseñar un prompt profesional anula las posibles imprecisiones que podría tener la respuesta.

El segundo punto es menos palpable en el corto plazo pero creo que es más preocupante, es bien sabido que cuando emergen nuevas tecnologías se pueden perder algunas habilidades, pero también emergen otras, un contador que ya no necesita gastar horas usando una calculadora puede ahorrar ese tiempo con una hoja de cálculo e invertir el tiempo restante en análisis que antes no podía hacer. Veámoslo de otra manera, digamos que vamos al gimnasio y conseguimos una máquina que levante pesas, o le pagamos a alguien para que levante pesas por nosotros, evidentemente no recibiremos los beneficios de hacer ejercicio, es lo mismo, cuando delegamos en la IA tareas básicas que deberíamos hacer nosotros, nuestra mente no se ejercita adecuadamente. Mariano Sigman y Santiago Bilinkis en su libro “Artificial” desarrollan el concepto de “sedentarismo cognitivo” que advierte sobre las potenciales consecuencias de delegar funciones mentales esenciales a herramientas digitales, cada vez que evitamos construir un prompt por nosotros mismos estamos aumentando esa “deuda cognitiva” con nuestra mente.

¿Significa esto que el metaprompting sea una mala práctica? por supuesto que no, en realidad es una herramienta muy poderosa para mejorar nuestra comunicación con la IA. Volviendo a nuestro tema inicial de la comunicación imaginemos este escenario expuesto en el libro “El cerebro del niño” de Dan J. Siegel y Tina Payne:

- **El padre dice**: "Vamos al consultorio, debes estar quieto, no puedes correr, debes hacer lo que te diga el doctor, será rápido y luego iremos a casa".
- **Lo que el niño escucha**:  se queda solo con la palabra más atractiva (“jugar”, “correr”) o con la última instrucción, porque su cerebro aún no procesa bien frases largas ni varias órdenes simultáneas.

Una situación así podría desencadenar en un problema mayor, y ninguno de los dos va a entender al final lo que pasó, pero digamos que este padre usa *metaprompt* para saber cómo expresar lo que quiere y usa este libro (que en nuestro sería como preguntarle a otra IA) para saber cuál es la mejor forma en que se puede comunicar con su hijo y habrá encontrado la mejor forma de expresarle su intención:

- **La solución**: frases cortas, concretas y una sola instrucción por vez ("Ahora nos sentamos quietos").

Al final el mensaje era el mismo, pero la forma en que cada uno lo entiende es diferente. El metaprompt es una técnica que se enfoca en afinar la estructura de las peticiones, y se puede usar de forma automatizada para encontrar los patrones más eficientes que se pueden usar para un objetivo específico. Pero de forma individual se usa para que la IA misma nos ayude a mejorar nuestros prompts con esos patrones ya identificados, los modelos de IA en su entrenamiento tienen información sobre técnicas de prompt que funcionan bien, entonces esto hace que sea posible preguntarles sobre eso.

En consultas que vamos a usar de forma repetitiva es especialmente valioso dedicar un tiempo adecuado a pensar y estructurar lo que vamos a pedirle a la IA intentando pensar por nosotros mismos lo que queremos que haga por nosotros. Hacer las consultas por nosotros mismos primero y luego afinarlas usando la IA es una muy buena estrategia para cubrir los dos riesgos que hemos mencionado, nos estamos asegurando de ejercitar nuestra mente y al tiempo nos comunicaremos de forma muy eficiente con la IA, una técnica rápida para este segundo consejo es usar un prompt como este que sugiere Diego Vega de Platzi:

*“Nunca debes asumir nada no dicho por el usuario. 
Si falta información, vuelve a preguntar de forma eficiente.* 
*Hazme todas las preguntas que necesites saber de mi para hacer un mejor diseño.*
*Preguntame una por una.*
*Espera que responda cada pregunta antes de hacerme la siguiente pregunta.*
*No te limites en el número de preguntas.*
*Solo responde a mi petición cuando me hayas hecho todas las preguntas que necesites.”*

Entonces, ¿cuál es el verdadero valor del metaprompting? No está en evitar pensar, sino en pensar mejor. No es un atajo hacia la pereza cognitiva, sino una invitación a la precisión. Así como aprendimos a comunicarnos con otros seres humanos a través de años de ensayo y error, el metaprompting es simplemente eso: una herramienta que acelera nuestro aprendizaje sobre cómo comunicarnos con una inteligencia diferente a la nuestra. Y en ese proceso, lo que realmente ejercitamos no es la delegación, sino la maestría. Porque al final, la IA no piensa por nosotros; nos enseña a pensar diferente. La diferencia es sutil, y esa decisión, esa responsabilidad, sigue siendo enteramente nuestra.
