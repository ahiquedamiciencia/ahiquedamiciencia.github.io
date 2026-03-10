---
layout: post
title: "Cuando una tabla parece convincente, pero el análisis no responde del todo a la pregunta"
date: 2026-03-10 10:00:00 +0100
categories:
  - metodologia
  - lectura-critica
tags:
  - ensayo-clinico
  - peer-review
  - estadistica
  - medidas-repetidas
  - placebo
  - interpretacion
  - calidad-de-vida
  - dolor
  - reiki
  - pediatria-oncologica
---

A veces, al leer un ensayo clínico, uno tiene la sensación de que todo encaja. Hay varios grupos, aparecen comparaciones antes y después, se acumulan valores de p y las tablas transmiten una impresión inmediata de solidez. Sin embargo, esa primera impresión no siempre coincide con lo que el análisis permite concluir de verdad.

Eso es precisamente lo que convierte algunos artículos en material docente excelente.

El estudio que comento aquí evaluó el efecto del Reiki en niños con leucemia mediante un ensayo con tres brazos: Reiki, pseudo-Reiki y control. A primera vista, el trabajo ofrece una arquitectura que puede resultar convincente: grupo placebo, grupo control, varios días de seguimiento, análisis pre y post, y una cantidad considerable de contrastes estadísticos. Pero cuando uno baja de la conclusión general a las tablas concretas, aparece una cuestión metodológica mucho más interesante: no siempre basta con que un análisis parezca completo; lo importante es si realmente responde a la pregunta de investigación.

## Cuando mejorar dentro de un grupo no basta

Esta es, probablemente, la primera gran lección que se puede extraer del manuscrito.

En buena parte del texto interpretativo, la atención se dirige a los cambios antes-después dentro de cada grupo. Ese tipo de análisis puede ser útil para describir una evolución. El problema aparece cuando se utiliza como si demostrara, por sí mismo, que la intervención fue superior a las demás condiciones.

No es lo mismo.

Un ejemplo muy claro aparece en la Tabla 2, dedicada a signos vitales. En el tercer día, la frecuencia respiratoria disminuye de forma significativa en el grupo Reiki, con `z = -3.076; p = 0.002`. Leído aisladamente, el dato puede parecer sugestivo. Sin embargo, el grupo placebo también muestra una disminución significativa, con `z = -2.537; p = 0.011`. Y cuando se observa la comparación entre grupos en ese mismo momento, el resultado deja de sostener una superioridad clara: antes de la intervención `H = 2.595; p = 0.273`, y después `H = 1.189; p = 0.552`.

Este punto merece insistencia docente, porque es una de las confusiones más frecuentes en la lectura de ensayos:

que un grupo mejore respecto a sí mismo no demuestra, por sí solo, que haya mejorado más que los demás.

Para sostener una afirmación de superioridad, no basta con enseñar que Reiki cambia. Hay que mostrar que cambia más que el placebo y más que el control. Y eso exige comparar explícitamente las trayectorias o los cambios entre grupos, no solo comprobar si cada grupo se aparta de su propio punto de partida.

Dicho de manera muy sencilla:

**significativo dentro de un grupo no significa diferente entre grupos.**

## Las medidas "pre" de los días sucesivos no son una línea base nueva

Otro aspecto muy útil para la docencia aparece en las tablas de dolor.

En los estudios con varias sesiones o mediciones repetidas, es fácil caer en una lectura automática: asumir que toda medida registrada "antes de la intervención" funciona como una nueva línea base. Pero eso no siempre es verdad. De hecho, en muchos casos es metodológicamente engañoso.

En la Tabla 4, correspondiente a la evaluación materna del dolor, antes de la intervención del segundo día ya aparece una diferencia entre grupos: el grupo Reiki presenta una mediana de `2 (0–10)` frente a `5 (2–8)` en el control, con `H = 7.482; p = 0.024`, y el post hoc indica `r < c`. En el tercer día, la situación se repite: Reiki `2 (0–9)` frente a control `5 (2–9)`, con `H = 12.862; p = 0.002`.

Esto no es un detalle menor. Indica que la medida "pre" del segundo o tercer día ya no representa un punto de partida neutral e independiente. Puede estar reflejando el efecto acumulado de sesiones previas, la evolución natural del cuadro, la adaptación del niño, cambios contextuales o simplemente la dinámica longitudinal del proceso.

Por tanto, conviene dejar muy clara una idea metodológica importante:

**en un diseño con medidas repetidas, las medidas previas de días sucesivos no equivalen a una línea base inicial limpia.**

Y esto importa porque cambia la forma en que interpretamos la comparación pre-post de cada jornada. Si la medida previa ya viene condicionada por lo ocurrido antes, esa comparación deja de ser una "mini línea base contra mini intervención" tan simple como a veces se presenta.

## La multiplicidad de pruebas obliga a leer con más cautela

Un tercer aprendizaje importante del caso tiene que ver con la cantidad de pruebas estadísticas realizadas.

Aquí no estamos ante un único desenlace, un único momento y una única comparación. El manuscrito analiza varios grupos, varios días, múltiples subescalas, comparaciones entre grupos, comparaciones dentro de cada grupo y análisis post hoc. Eso multiplica el número de contrastes y, con ello, aumenta también la probabilidad de que aparezcan resultados estadísticamente significativos por puro azar.

Esto no significa que haya que descartar todos los hallazgos. Significa algo más sensato: que no todos los valores de p por debajo de 0.05 merecen el mismo grado de confianza interpretativa.

Las Tablas 5 y 6, centradas en calidad de vida, ilustran muy bien este problema. Se analiza la puntuación total y, además, una batería de subescalas: dolor, náusea, ansiedad procedimental, ansiedad al tratamiento, preocupación, problemas cognitivos, apariencia física y comunicación. En este contexto, los hallazgos muy consistentes merecen más atención que aquellos que aparecen de manera más marginal o menos replicada.

Por ejemplo, en la Tabla 5, la subescala `Procedural Anxiety` presenta `p = 0.031`, `Treatment Anxiety` `p = 0.032` y `Worry` `p = 0.008`. Sin embargo, en la Tabla 6, `Procedural Anxiety` mantiene una diferencia con `p = 0.025`, mientras que `Treatment Anxiety` pasa a `p = 0.189` y `Worry` a `p = 0.525`. Es decir, algunos hallazgos aparecen en una fuente de evaluación y se diluyen en la otra.

Eso no obliga a llamarlos falsos, pero sí aconseja tratarlos como resultados más frágiles. Muy distinto es el caso de desenlaces como la puntuación total o la subescala `Pain and Hurt`, donde la señal es más intensa y además se reproduce en ambas tablas.

La enseñanza metodológica aquí es especialmente útil para estudiantes:

**cuando se hacen muchas pruebas, los hallazgos marginales deben interpretarse con más prudencia que los hallazgos robustos y repetidos.**

## Que el placebo también mejore cambia la conversación

Una de las cosas más interesantes del estudio es que el grupo placebo no se comporta como un grupo inmóvil. Y eso, metodológicamente, es mucho más relevante de lo que a veces se reconoce.

En la Tabla 3, sobre dolor según la evaluación del niño, el grupo placebo mejora de forma significativa del pre al post en los tres días:

- Día 1: `z = -4.000; p < 0.001`
- Día 2: `z = -3.500; p < 0.001`
- Día 3: `z = -2.507; p = 0.012`

En la Tabla 4, según la evaluación materna, ocurre algo semejante:

- Día 1: `p < 0.001`
- Día 2: `p = 0.003`
- Día 3: `p < 0.001`

También en calidad de vida el placebo muestra mejorías. En la Tabla 5, por ejemplo, la `Total Scale Score` del grupo placebo mejora con `z = -2.956; p = 0.003`, y en la Tabla 6 vuelve a mejorar con `z = -3.444; p = 0.001`.

Desde una lectura metodológica, esto obliga a matizar mucho más la interpretación. Porque entonces ya no basta con decir que la intervención mejora ciertos desenlaces. La cuestión pasa a ser cuánto de esa mejoría es atribuible a un efecto específico del Reiki y cuánto podría explicarse por atención recibida, contacto terapéutico, expectativas, regresión a la media o evolución natural del cuadro.

Ese es un punto muy fértil para la docencia, porque enseña a no tratar el placebo como un simple "estorbo", sino como una herramienta para pensar mejor.

La lección sería esta:

**si el placebo también mejora, la interpretación no puede quedarse en que la intervención "funciona"; tiene que preguntarse cuán específico es realmente ese efecto.**

## Hay señales favorables, pero no una mejora uniforme en todo

Otra idea que conviene enseñar con este caso es que varios resultados favorables no autorizan automáticamente una conclusión global sin matices.

En este manuscrito sí hay señales relativamente consistentes en algunos dominios. En la Tabla 5, por ejemplo, la `Total Scale Score` del grupo Reiki pasa de `53.85` a `76.92`, mientras que el placebo queda en `57.69` y el control en `52.88`, con `H = 25.693; p < 0.001`, y el post hoc indica `r > pr` y `r > c`. En la subescala `Pain and Hurt`, el grupo Reiki alcanza una mediana post de `100 (50–100)`, frente a `50 (0–100)` en placebo y `50 (0–100)` en control, con `H = 35.671; p < 0.001`. En `Nausea`, Reiki llega a `95 (50–100)`, mientras los otros dos grupos permanecen en `50`, con `H = 33.693; p < 0.001`.

Ese mismo patrón reaparece en la Tabla 6, en la evaluación parental:

- `Total Scale Score` post: Reiki `71.15`, placebo `55.77`, control `55.77`, `p = 0.001`
- `Pain and Hurt` post: Reiki `93.75`, placebo `50`, control `50`, `p < 0.001`
- `Nausea` post: Reiki `75`, placebo `50`, control `50`, `p = 0.001`

Sería un error no reconocer que esos resultados existen y que, dentro del propio estudio, destacan por su consistencia. Pero también sería un error extender ese patrón a todos los dominios analizados.

Porque no ocurre lo mismo con todo.

En la Tabla 5, `Cognitive Problems` no muestra diferencias entre grupos tras la intervención (`p = 0.923`), ni `Perceived Physical Appearance` (`p = 0.624`) ni `Communication` (`p = 0.460`). En la Tabla 6, tampoco aparecen diferencias post en `Treatment Anxiety` (`p = 0.189`), `Worry` (`p = 0.525`), `Cognitive Problems` (`p = 0.472`), `Perceived Physical Appearance` (`p = 0.326`) o `Communication` (`p = 0.827`).

La conclusión docente es bastante clara:

**un estudio puede mostrar beneficios convincentes en algunos desenlaces y, al mismo tiempo, no justificar una afirmación global sobre todos los aspectos de la calidad de vida.**

No todos los desenlaces cuentan la misma historia. Y una buena discusión debe resistirse a la tentación de homogeneizarlos artificialmente.

## La pregunta central pedía un análisis más integrador

Llegados a este punto, probablemente la cuestión metodológica más importante sea esta: el estudio ofrece muchas comparaciones, pero no termina de proporcionar la prueba analítica más alineada con su pregunta principal.

Lo que se presenta son, sobre todo, comparaciones entre grupos en momentos concretos y comparaciones pre-post dentro de cada grupo. Eso aporta información, sin duda. Pero la pregunta fuerte del ensayo no era simplemente si el grupo Reiki tenía una mediana mejor en un momento dado, ni solo si mejoraba respecto a sí mismo.

La pregunta fuerte era otra:

**¿la evolución del grupo Reiki fue diferente de la evolución del grupo placebo y del grupo control a lo largo del tiempo?**

Para responder bien a esa pregunta, lo más convincente habría sido analizar directamente el cambio entre grupos o utilizar un modelo longitudinal con interacción `grupo × tiempo`. Ese tipo de análisis integra formalmente las dos dimensiones que aquí aparecen algo fragmentadas: la evolución temporal y la comparación entre condiciones.

Sin ese paso, el lector recibe muchas piezas del rompecabezas, pero no siempre la demostración más sólida de la hipótesis principal.

Y esa situación, precisamente, es la que vuelve este caso tan útil en docencia. No se trata de un estudio obviamente desastroso. Se trata de algo mucho más frecuente: un estudio con resultados llamativos y potencialmente interesantes, pero cuya interpretación exige bastante más rigor del que su presentación inicial podría sugerir.

## Qué puede aprender un estudiante de este caso

Si tuviera que resumir el valor docente de este artículo, lo haría así.

Primero, enseña que una mejoría intragrupo no demuestra superioridad frente a otros grupos.

Segundo, recuerda que en diseños con medidas repetidas las medidas "pre" de días sucesivos no equivalen a una línea base nueva e independiente.

Tercero, muestra que la multiplicidad de pruebas obliga a diferenciar entre hallazgos robustos y resultados más frágiles.

Cuarto, subraya que la mejoría del placebo no invalida el estudio, pero sí obliga a pensar en efectos inespecíficos y en la verdadera especificidad del efecto atribuido a la intervención.

Y quinto, recuerda que cuando los distintos desenlaces no cuentan exactamente la misma historia, la conclusión debe ser proporcionada y no expansiva.

## Cierre

Una tabla llena de asteriscos puede impresionar. Es normal. Pero la buena metodología no consiste en contar asteriscos, sino en plantear una pregunta más incómoda y bastante más útil: si el análisis realmente responde a la pregunta que el estudio decía querer contestar.

En este caso, las tablas sugieren una señal favorable en algunos desenlaces importantes, especialmente dolor, náusea y puntuación total de calidad de vida. Pero, desde una perspectiva docente, quizá enseñan algo aún más valioso: cómo distinguir entre un patrón prometedor y una demostración metodológicamente sólida.

Y esa diferencia, aunque a veces pase desapercibida, es exactamente una de las cosas que más merece la pena enseñar.

## Referencia del artículo

Demir D, Mutlu B, Türkkan E. *The effect of Reiki therapy performed on children with leukemia between the ages of 5-7 years on pain, vital signs and quality of life: A randomized controlled study*. **European Journal of Oncology Nursing**. 2025;81:103082. doi:10.1016/j.ejon.2025.103082.

- PMID: 41793784
- PubMed: https://pubmed.ncbi.nlm.nih.gov/41793784/
- DOI: https://doi.org/10.1016/j.ejon.2025.103082
