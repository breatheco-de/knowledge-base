# Dominio de los conocimientos técnicos

## Resumen

En la actualidad, los métodos de enseñanza tradicionales para lograr el dominio y la competencia técnica se centran principalmente en los fundamentos y los aspectos teóricos, **olvidando la importancia de la experiencia práctica y real, así como la motivación y el compromiso en el proceso de aprendizaje**. El sistema funciona hasta cierto punto, pero sigue sufriendo el aumento de las tasas de abandono y la disminución de las tasas de matriculación, al tiempo que se tarda varios años en graduar a los estudiantes en habilidades y tecnologías que evolucionan drásticamente año tras año.

Los bootcamps de entrenamiento y otras aplicaciones o sitios web han surgido como una posible solución con entornos de aprendizaje más rápidos, atractivos, prácticos e interactivos, pero a menudo **carecen de un enfoque o marco científico para optimizar la eficacia del aprendizaje**. Es posible que no cuenten con la experiencia necesaria para diseñar y aplicar planes de estudios basados en pruebas y de eficacia probada. 

Al no ofrecer un método completo y rápido para el aprendizaje de habilidades técnicas, acabamos teniendo una mano de obra que no está totalmente preparada, instituciones que luchan por retener a los estudiantes y empresas que dudan a la hora de contratar. La brecha entre desarrolladores junior y senior también se ensancha, creando un cuello de botella en el mercado. 

Lo que se necesita es un enfoque holístico que aborde tanto la **motivación** como la **eficiencia del tiempo**, y ponga en práctica una solución rentable que se amplíe a miles de usuarios sin dejar de ser accesible para todos.

En este artículo, proponemos un marco que incorpora una serie de 4 métricas para puntuar matemáticamente los entornos con mayor eficacia de aprendizaje y tiempo: [Retención de la memoria](#Retención-de-la-Memoria), [Calidad de la retroalimentación](#Calidad-y-Frecuencia-de-la-retroalimentación), [Dominio del aprendizaje](#Aprendizaje-incremental-o-Aprendizaje-maestro) y [Motivación](#Motivación). Nuestra solución propuesta aprovecha la tecnología de vanguardia y una intervención humana mínima para crear un enfoque rentable de la educación que puede medirse en tiempo real utilizando estas 4 métricas.

## Eficacia del aprendizaje de entorno

> ⚠️ En lugar de centrarnos en evaluar la capacidad de aprendizaje del alumno, nos centramos en evaluar el potencial de aprendizaje del entorno.

Definimos la eficacia del entorno de aprendizaje como la efectividad de una institución educativa a la hora de proporcionar un entorno, un plan de estudios y unas herramientas que conduzcan a una alta eficacia del aprendizaje y, en última instancia, a la competencia técnica del estudiante.

![Learning Efficacy Formula (1).png](https://github.com/breatheco-de/knowledge-base/blob/main/images/learning-efficacy-formula.png?raw=true)

> 📖 Un entorno de aprendizaje altamente eficaz conduce a resultados de aprendizaje ideales.

## Retención de la memoria

$$
R(t) = I \times e^{-\frac{t}{S \times n}}
$$

> *Cuanto más tiempo pase sin practicar, menos retendrá tu cerebro.*

Tras recibir información nueva, el lóbulo temporal medial del cerebro puede guardarla en la memoria durante unos días o semanas. Pero, si no se utilizan métodos como la repetición espaciada o el recuerdo activo, el cerebro no puede almacenar esa memoria durante mucho tiempo debido a la decadencia e interferencia del rastro de memoria, un proceso más comúnmente conocido como "olvido."

![ebbinghaus-curva-del-olvido.jpg](https://github.com/breatheco-de/knowledge-base/blob/main/images/ebbinghaus-forgetting-curve.jpg?raw=true)

[Curva del olvido²](#Referencias)

| Nombre | Descripción |
| --- | --- |
| `I` representa la tasa de retención inicial | ¿Qué tan fácil fue de entender al principio? |
| `S` es el "factor de estabilidad" | Está influido por factores internos como la carga cognitiva, los conocimientos previos, el estado emocional, y factores externos como la complejidad de los materiales, el formato y el estilo de presentación, las aplicaciones prácticas, etc. |
| `n` es cuántas veces durante la ventana de tiempo | Cuántas veces se repetirá y practicará el material de contenido durante la ventana de tiempo. Por ejemplo: n=3 serán 3 veces en el transcurso de 1 semana. |
| `t` es la ventana de tiempo, | La ventana de tiempo tiene que ser consistente, si puede ser semanas o meses, etc. Por ejemplo: t=1 podría significar "a lo largo de una semana". Cuanto mayor sea t, más rápido decaerá tu memoria, a menos que aumentes la estabilidad y/o la repetición. |

En un bootcamp de programación en el que los alumnos practican a diario con ejercicios y proyectos autocalificados pero no tienen exámenes, puedes aplicar esta fórmula para elaborar estrategias de refuerzo del aprendizaje.

### **Ejemplo práctico:**

### Supuestos:

1. Sea `I=1` (o 100%), suponiendo que los estudiantes entienden completamente un nuevo concepto de programación cuando lo aprenden por primera vez.
2. Sea *`S*=0,7` , suponiendo que la estabilidad y la calidad del material son del 70%.
3. Sea *`n*=3`, suponiendo que un estudiante repite el concepto 3 veces después del aprendizaje inicial (quizás en futuros proyectos o ejercicios) durante el periodo `t`.

### Aplicación:

Para mantener la tasa de retención por encima de un cierto umbral, digamos el 80%, se puede encontrar el tiempo *`t`* en el que *`R*(*t*)` cae por debajo de ese umbral y programar prácticas o repasos adicionales en ese momento o antes.

$$
\text{Solve for } t \text{ in } 0.8 = e^{-\frac{t}{0.7 \times 3}}.
$$

Resolviendo esta ecuación se obtiene:

$$
t \approx 1.65 \text{ días}
$$

Con estos parámetros, deberías programar ejercicios adicionales de práctica o repaso en torno al segundo día después del evento de aprendizaje inicial para mantener una tasa de retención superior al 80%.

De este modo, el bootcamp puede alinear su plan de estudios para contrarrestar de forma proactiva los efectos de la curva del olvido, garantizando que los conceptos cruciales se refuercen antes de que sea probable que los estudiantes los hayan olvidado.

### Factor de estabilidad (calidad) en el aprendizaje de competencias técnicas

En el ejemplo práctico anterior, asumimos una Estabilidad del `80%`. Deberíamos centrarnos en conseguir una estabilidad superior al 80% para proporcionar el mejor entorno de aprendizaje posible.

En el contexto del aprendizaje de la programación, el factor de estabilidad *`S`* en un modelo de curva de olvido puede verse influido por varios elementos. Estos elementos pueden clasificarse a grandes rasgos en factores internos relacionados con el alumno y factores externos asociados con el entorno de aprendizaje o el contenido.

**Factores internos**

1. **Conocimientos previos** Un alumno con una sólida comprensión básica de los conceptos de programación podría tener un factor de estabilidad más alto para la información nueva y relacionada.
2. **Carga cognitiva**: El código que es más fácil de entender y está dentro de la capacidad cognitiva del alumno puede retenerse durante más tiempo, lo que lleva a una mayor *`S`*.
3. **Estado emocional**: El estrés, la fatiga o la ansiedad pueden influir negativamente en el factor de estabilidad.

**Factores externos**

1. **Complejidad del material**: Un código más complejo o abstracto podría tener un factor de estabilidad más bajo, ya que es más difícil de retener.
2. **Estilo de presentación**: Un código bien organizado y claramente explicado podría tener un factor de estabilidad más alto.
3. **Aplicación práctica**: El código que se aplica inmediatamente en un proyecto práctico puede retenerse mejor.
4. **Espaciamiento y repetición**: Emplear técnicas de repetición espaciada cuando se aprende código podría aumentar *`S`*.
5. **Aprendizaje comunitario y colaborativo**: Interactuar con otras personas para resolver problemas de programación puede reforzar la memoria y aumentar la *`S`*.

Estos no son los únicos factores, y su impacto puede estar interrelacionado. Por ejemplo, los conocimientos previos pueden interactuar con la complejidad del material y afectar a la *`S`*. Del mismo modo, el formato del material puede influir en la carga cognitiva. Aunque es difícil cuantificar estos factores en un único factor de estabilidad *`S`* de forma precisa, proporcionan una pauta general de lo que podría influir en la rapidez o lentitud con que decae el conocimiento de programación con el tiempo.

### Cómo aumenta la estabilidad el recuerdo activo

> 📖 El recuerdo activo consiste en repasar los materiales de forma activa y autodirigida.

Los materiales de aprendizaje tradicionales desalientan principalmente la autodirección.

Los estudiantes necesitan un alto nivel de autodirección [para lograr mayores niveles de dopamina, confianza y motivación³](#Referencias).

Reducción de la carga cognitiva y mejora del estado emocional del alumno (factores muy influyentes en la estabilidad). 

Además, el recuerdo activo mejora el estilo de presentación de los materiales y una vía de aprendizaje más práctica, lo que también influye mucho en la estabilidad del aprendizaje.

![Active Recall (1).png](https://github.com/breatheco-de/knowledge-base/blob/main/images/active-recall.png?raw=true)

El aprendizaje activo, que implica la participación de los alumnos en actividades como el trabajo en grupo, la resolución de problemas y el debate, [puede aumentar la motivación y la eficacia del aprendizaje⁴](#Referencias) en comparación con formas de aprendizaje más pasivas como las lecturas.

El recuerdo activo permite una forma de retroalimentación continua y autogenerada. A medida que los alumnos repasan el material, evalúan su comprensión y su rendimiento, lo que sirve de base para su proceso de aprendizaje. Este bucle de autorretroalimentación puede ser increíblemente poderoso cuando se combina con la retroalimentación externa, haciendo que cada ronda de retroalimentación externa sea más impactante.

### Uso de la repetición espaciada para aumentar la retención de la memoria

> 📖 La repetición espaciada se refiere a la práctica de repetir y recordar información en intervalos de tiempo específicos.

Los ejercicios ideales contienen **alta frecuencia** con un enfoque muy **activo** y **autodirigido**.

Como segunda prioridad, también se recomiendan los ejercicios de frecuencia media pero muy autodirigidos.

Por último, también se recomiendan los ejercicios con cierto grado de interacción social, ya que [aumentan los niveles de dopamina**¹**](#Referencias),

![Repetición espaciada](https://github.com/breatheco-de/knowledge-base/blob/main/images/spaced-repetition.png?raw=true)

## Calidad y frecuencia del feedback

La retroalimentación de alta calidad debe ser frecuente, clara, personalizada y relevante (relacionada con los retos actuales que está teniendo el estudiante); Proporcionar información procesable que pueda ser utilizada por el alumno para mejorar su rendimiento o comprensión.

| Frecuencia | Proporcionar feedback varias veces al día. |
| --- | --- |
| Relevancia | En el momento en que el alumno tiene problemas, hace preguntas o entrega tareas. |
| Claridad | Formatos y sintaxis accesibles y atractivos que el estudiante pueda entender, abordando temas específicos, ejercicios, tareas, líneas de código, etc. |
| Personalizado | Dirigido a los problemas específicos del alumno, en el momento concreto en que lo necesita. 

Mediante la implementación adecuada de "micro-feedbacks" frecuentes podemos abordar la frecuencia, la personalización y la relevancia a la vez, dejando que la Claridad sea el factor más desafiante. Describimos mejor el concepto de micro-feedbacks en la siguiente sección.

### Microfeedbacks

> 🔥 Dar feedback muy a menudo logra personalización, relevancia y frecuencia a la vez.

Las micro-retroalimentaciones son respuestas breves e inmediatas que se dan a los alumnos para ofrecer correcciones rápidas, afirmaciones o consejos. Al ser inmediatas y frecuentes, permiten altos niveles de personalización.

Si la implementación de micro-retroalimentaciones **garantiza un nivel constante de alta personalización**, entonces es razonable tratar la personalización como una constante y eliminarla de la ecuación de calidad. Bajo este supuesto, la naturaleza personalizada del proceso de aprendizaje está integrada en las micro-retroalimentaciones, lo que hace que un término separado para la personalización sea redundante.

> Con las microrretroalimentaciones, dar retroalimentación relevante y personalizada ya no es una preocupación. 

Es un hecho.

La naturaleza en tiempo real de la micro-retroalimentación permite un enfoque granular en tareas individuales o líneas de código, **haciéndola altamente relevante** para lo que el estudiante está trabajando en un momento dado. Puede guiar al alumno hacia las mejores prácticas y corregir malentendidos o errores que, de otro modo, podrían propagarse a problemas mayores.

$$
S = \text{Claridad} \times \log(1 + n(t))
$$

La fórmula pretende cuantificar la estabilidad del nivel de comprensión o destreza de un alumno en función de dos factores clave: la claridad de la información que recibe y la frecuencia de sus interacciones con el sistema de aprendizaje.

- **Claridad**: Es una medida del grado de comprensión de los comentarios por parte del alumno. Puede oscilar entre 0 y 1, siendo 1 una respuesta perfectamente clara.
- **`Log(1+*n*(*t*))`**: Este término da cuenta de la frecuencia de interacciones que incluyen retroalimentación *`n*(*t*)`*, en un tiempo dado *`t`*. El logaritmo ayuda a amortiguar el efecto de las frecuencias muy altas y hace que la relación no sea lineal.

### **Ejemplo práctico en un Bootcamp de Programación:**

Consideremos un Bootcamp de Programación que utiliza sistemas automatizados para proporcionar información inmediata sobre los ejercicios de programación. Los estudiantes realizan tareas de programación a diario y el sistema comprueba automáticamente sus envíos.

- **Claridad**: El campamento ha invertido en la generación de comentarios automatizados de alta calidad. Tras evaluarlo, decidimos que su puntuación de Claridad es de 0,9.
- **Interacciones *`n*(*t*)`**: Durante la primera semana, un estudiante en particular envía código para su comprobación automatizada 15 veces.

Utilizando la fórmula:

$$
S = \text{Claridad} \times \log(1 + n(t))
$$

$$
S = 0.9 \times \log(1 + 15) = 0.9 \times \log(16) = 0.9 \times 1.204 = 1.084
$$

Este valor sugiere que la combinación de una retroalimentación clara y una interacción frecuente ha conducido a una comprensión relativamente estable del material por parte de este alumno. En este contexto de bootcamp, una puntuación de estabilidad tan alta implica que es probable que el alumno retenga bien el material, suponiendo que la retroalimentación sea eficaz y relevante para las tareas.

## Aprendizaje incremental o de dominio

El aprendizaje de maestría se basa fundamentalmente en ciclos de instrucción y retroalimentación, centrándose en asegurar que cada alumno alcance una comprensión completa antes de progresar.

> 💡 El aprendizaje de dominio implementa evaluaciones frecuentes, pero hemos decidido utilizar la retroalimentación como sustituto de las evaluaciones, ya que evita escenarios en los que los estudiantes pueden desanimarse por los resultados de las evaluaciones.

El concepto de "dominio" en el contexto del aprendizaje de maestría no suele definirse estrictamente por el porcentaje de material retenido. En su lugar, el dominio suele referirse a la capacidad de aplicar conocimientos o destrezas de forma coherente, precisa e independiente en contextos relevantes. Se trata de competencia funcional y comprensión profunda más que solamente retención de información.

En nuestra versión del aprendizaje de dominio, la retroalimentación frecuente se utiliza para identificar las áreas en las que un estudiante aún no ha alcanzado el dominio, de modo que pueda centrarse en esas áreas en ciclos posteriores de instrucción y práctica. El recuerdo activo autodirigido puede aumentar este proceso ayudando a los alumnos a identificar las lagunas en su comprensión.

## Motivación

La motivación del alumno puede definirse como el grado de voluntad, impulso e interés que tiene una persona para participar y persistir en las actividades de aprendizaje.

![Motivación (1).png](https://github.com/breatheco-de/knowledge-base/blob/main/images/motivation.png?raw=true)


## Referencias

1. "Interpersonal relationships and learning: the influence of social structure on attitudes, behaviors, and learning outcomes" por Johnson y Johnson (en Advances in Learning and Behavioral Disabilities, 1994)
2. Curva del olvido, de [Hermann Ebbinghaus.](https://es.wikipedia.org/wiki/Hermann_Ebbinghaus)
3.  "The Relationship Between Self-Directed Learning and Employment and Life Satisfaction Among Undergraduates, Graduates, and Alumni" de Reio y Callahan, 2004.
4. "El aprendizaje activo aumenta el rendimiento de los estudiantes en ciencias, ingeniería y matemáticas. Proceedings of the National Academy of Sciences", de Freeman, S., Eddy, S. L., McDonough, M., Smith, M. K., Okoroafor, N., Jordt, H. y Wenderoth, M. P. (2014).