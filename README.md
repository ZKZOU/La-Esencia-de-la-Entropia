# La Esencia de la Entropía

## La Relación Matemática Entre la Primera y la Segunda Ley de la Termodinámica: Vínculo y Dinámica

Zou, Zhi Kai  

Correo electrónico: zhiyan.zou@foxmail.com 

Wuhan; China 

https://orcid.org/0009-0000-4279-1064 

Zou, Z. K. (2026). Energy Conservation as the Constraint Precondition for Monotonic Entropy Increase, The Mathematical Structure Between the First and Second Laws of Thermodynamics. Zenodo. https://doi.org/10.5281/zenodo.21861848

**Resumen:** Sobre la base del marco de entropía multiplicativa impulsada por gradientes propuesto por Zou (2025)[3], este artículo revela la estructura de restricción matemática intrínseca entre la primera y la segunda ley de la termodinámica. En este marco, la entropía de un sistema se define como S = ∏ᵢ mᵢ, donde mᵢ denota el valor de energía cuantizado portado por cada nodo discreto, sujeto a la estricta conservación de la energía total E = ∑ᵢ mᵢ. La transferencia de energía sigue una rigurosa regla impulsada por gradientes: la energía fluye exclusivamente desde nodos de mayor valor hacia nodos de menor valor (mᵢ > mᵢ + 1). Este artículo demuestra que, bajo esta formulación de entropía multiplicativa, la primera ley no es meramente un postulado independiente que coexiste con la segunda ley, sino que sirve como la precondición de restricción para el aumento monotónico de la entropía—la conservación de la energía, mediante la desigualdad de las medias aritmética y geométrica, produce directamente la cota superior de la entropía S ≤ (E / N)ᴺ, mientras que la regla impulsada por gradientes asegura que cada paso de transferencia de energía incrementa estrictamente la entropía multiplicativa. De esta manera, las dos leyes de la termodinámica se unifican en un único proceso dinámico—a saber, la evolución impulsada por gradientes bajo una restricción de conservación—en donde el aumento de entropía ya no depende de suposiciones probabilísticas o estadísticas, sino que es una consecuencia necesaria determinada conjuntamente por la conservación de la energía y la existencia de gradientes de energía.

**Palabras clave:** entropía multiplicativa; impulsada por gradientes; conservación de la energía; primera ley de la termodinámica; segunda ley de la termodinámica; entropía no probabilística; relación restricción-dinámica

## 1. Introducción

La primera ley de la termodinámica (conservación de la energía) y la segunda ley (aumento de la entropía) son dos de las leyes más fundamentales y universales de la física. Desde el establecimiento de la termodinámica en el siglo XIX, estas dos leyes han sido consideradas postulados básicos mutuamente independientes: la primera ley afirma que la energía no puede ser creada ni destruida, mientras que la segunda ley afirma que la entropía de un sistema aislado nunca disminuye. Aunque ambas leyes operan simultáneamente en los procesos físicos, la termodinámica clásica no proporciona una relación de restricción matemática precisa entre ellas.

En la mecánica estadística tradicional, la entropía se define como S = k_B ln Ω, donde Ω es el número de microestados del sistema. Esta definición ha alcanzado un gran éxito en la termodinámica macroscópica, pero también conlleva un problema epistemológico fundamental: el valor de Ω depende de cómo el observador define la frontera entre "micro" y "macro", depende de la elección de la escala de engrosamiento, y depende de qué grados de libertad se consideran "relevantes" y cuáles "despreciables". En otras palabras, el valor de la entropía estadística depende en parte del nivel de descripción del observador, en lugar de estar enteramente determinado por el estado físico del sistema mismo. Esto conduce a una pregunta profunda: ¿mide la entropía estadística el estado físico del sistema mismo, o la información faltante del observador?

Más importante aún, la definición de entropía estadística no contiene el concepto de "gradiente de energía". Nos dice que una distribución uniforme es el estado de máxima entropía, pero no nos dice cómo el sistema se aproxima paso a paso a la uniformidad, cuál es la trayectoria de cada transferencia de energía, o cuál es la magnitud del gradiente en cada paso. Estas preguntas no pueden ser respondidas directamente por la entropía estadística, porque su definición no contiene la cantidad física de "gradiente".

Sin embargo, todos los procesos dinámicos reales en la naturaleza—conducción de calor, difusión, reacciones químicas y corrientes eléctricas—están impulsados por una cantidad física unificada: el gradiente de energía. El calor fluye de alta temperatura a baja temperatura; la materia fluye de alta concentración a baja concentración; la carga fluye de alto potencial a bajo potencial; los sistemas mecánicos se mueven de alta energía potencial a baja energía potencial. En todos los procesos naturales conocidos, el flujo de energía de mayor a menor es la única fuente de irreversibilidad.

Este artículo, basado en el marco de entropía multiplicativa impulsada por gradientes propuesto por Zou (2025), tiene como objetivo responder la siguiente pregunta central: ¿Existe una relación de restricción matemática precisa entre la primera y la segunda ley de la termodinámica? Si es así, ¿cuál es la estructura específica de esta relación?

La dinámica impulsada por gradientes propuesta aquí se alinea con la formulación termodinámica del tiempo de Tuisku, Pernu y Annila (2009), quienes describen la evolución física como un proceso impulsado por la dispersión de energía.

Graham, C., & Tokieda, T. (2020). Su trabajo reveló la conexión intrínseca entre la termodinámica y la desigualdad AM-GM, que comparte parte de la estructura matemática subyacente al marco de entropía multiplicativa que propuse posteriormente.

Demostraremos que, bajo la definición de entropía multiplicativa, la primera ley (conservación de la energía) no es meramente un prerrequisito para la segunda ley (aumento de la entropía), sino que produce directamente la cota superior matemática de la entropía mediante la desigualdad de las medias aritmética y geométrica, proporcionando así una base matemática no probabilística y necesaria para el aumento monotónico de la segunda ley.

## 2. Definición de Entropía Multiplicativa y la Regla Impulsada por Gradientes

### 2.1 Configuración Básica del Sistema de Nodos Discretos

Considérese un sistema cerrado que consta de N nodos. Cada nodo porta una cierta cantidad de energía, con la energía cuantizada en unidades de la constante de Planck h:

mᵢ ∈ ℕ⁺

donde mᵢ es el valor de energía portado por el i-ésimo nodo (en unidades de h).

La energía total del sistema se conserva estrictamente:

E = ∑ᵢ mᵢ = constante

La transferencia de energía entre nodos solo se permite entre nodos adyacentes, de una unidad a la vez, y solo cuando existe un gradiente de energía:

**Condición de transferencia:**

mᵢ > mᵢ + 1

**Regla de transferencia:**

mᵢ → mᵢ − 1,  mᵢ → mᵢ + 1

Aquí "1" representa una unidad de la constante de Planck h. Estas reglas constituyen las reglas dinámicas completas del sistema—sin probabilidad, sin conjuntos estadísticos, sin aleatoriedad, sin impulsión externa y sin escala de engrosamiento elegida artificialmente. La dirección evolutiva del sistema en cada paso está enteramente determinada por la distribución actual de gradientes de energía.

### 2.2 Definición de Entropía Multiplicativa

Defínase la entropía del sistema como el producto de todos los valores de energía de los nodos:

S = ∏ᵢ mᵢ

Esta definición tiene las siguientes características:

- No depende de distribuciones de probabilidad;
- No depende de suposiciones de conjuntos estadísticos;
- No depende de operaciones de engrosamiento;
- No depende de aproximaciones logarítmicas;
- Está determinada de manera única por la distribución actual de energía;
- Es un número entero positivo.

Más importante aún, refleja directamente el resultado de la evolución impulsada por gradientes.

### 2.3 Cálculo del Cambio de Entropía

Antes y después de cada transferencia de energía, el cambio de entropía puede calcularse con precisión. Sean las energías de los dos nodos participantes antes de la transferencia a y b (con a > b + 1), y después de la transferencia se convierten en a − 1 y b + 1. La razón de los valores de entropía es:

S′ / S = (a − 1)(b + 1) / (a · b)

Expandiendo:

S′ / S = 1 + (a − b − 1) / (a · b)

Dado que la condición de transferencia es a > b + 1, es decir, a − b − 1 > 0, y a, b > 0, se tiene:

S′ / S > 1

Es decir:

S′ > S

Toda transferencia de energía legítima conduce necesariamente a un aumento estricto de la entropía multiplicativa. La magnitud del aumento de entropía está directamente relacionada con el gradiente de energía a − b antes de la transferencia—cuanto mayor es el gradiente, mayor es el aumento de entropía.

### 2.4 Relación Logarítmica con la Entropía Clásica

Tomando el logaritmo de la entropía multiplicativa:

ln S = ∑ᵢ ln mᵢ

En condiciones en las que la distribución de energía es relativamente uniforme, ln S puede relacionarse con la entropía de Boltzmann tradicional S = k_B ln Ω mediante la aproximación de Stirling u otros métodos estadísticos. Esto indica que la entropía multiplicativa puede recuperar los resultados termodinámicos clásicos en el límite macroscópico apropiado, al tiempo que proporciona una descripción más fina para sistemas discretos.

## 3. La Primera Ley como Precondición de Restricción para la Segunda Ley

### 3.1 La Cota Superior de la Entropía Multiplicativa: Aplicación de la Desigualdad AM-GM

Zou, Z. K. (2026). Energy Conservation as the Constraint Precondition for Monotonic Entropy Increase, The Mathematical Structure Between the First and Second Laws of Thermodynamics. Zenodo. https://doi.org/10.5281/zenodo.21861848

Esta sección demuestra la proposición central: la conservación de la energía produce directamente la cota superior matemática de la entropía multiplicativa.

Para N números reales positivos m₁, m₂, ..., m_N, la desigualdad de las medias aritmética y geométrica (desigualdad AM-GM) establece:

(m₁ + m₂ + ... + m_N) / N ≥ (m₁ · m₂ · ... · m_N)^(1 / N)

Es decir:

E / N ≥ S^(1 / N)

Elevando ambos lados a la N-ésima potencia:

(E / N)ᴺ ≥ ∏ᵢ mᵢ = S

Por lo tanto:

S ≤ (E / N)ᴺ

La condición de igualdad (la condición de igualdad de la desigualdad AM-GM):

m₁ = m₂ = ... = m_N = E / N

Es decir, cuando la energía del sistema alcanza una distribución perfectamente uniforme, la entropía multiplicativa alcanza su valor máximo:

S_max = (E / N)ᴺ

### 3.2 Análisis Estructural de la Relación de Restricción

La derivación anterior revela la estructura matemática precisa entre la primera y la segunda ley:

| Ley | Papel en Este Marco | Expresión Matemática |
|-----|---------------------|----------------------|
| Primera Ley (Conservación de la Energía) | Precondición de restricción: determina el espacio de estados accesibles | E = ∑ᵢ mᵢ = constante |
| Segunda Ley (Aumento de la Entropía) | Producto dinámico: determina la trayectoria evolutiva real | S = ∏ᵢ mᵢ aumenta monotónicamente |

La primera ley delimita la "superficie accesible" en el espacio de estados—todas las posibles distribuciones de energía deben satisfacer la restricción de que la energía total es E. Sobre esta superficie, la entropía multiplicativa S = ∏ᵢ mᵢ tiene una cota superior definida (E / N)ᴺ, que está determinada de manera única por la primera ley a través de la desigualdad AM-GM.

La segunda ley especifica la dirección del movimiento real sobre la superficie accesible—la regla impulsada por gradientes asegura que cada paso evoluciona hacia un aumento de entropía, aproximándose finalmente al estado de máxima entropía dado por la desigualdad AM-GM.

**Idea clave:** La primera ley no solo especifica "qué estados son accesibles", sino que también da directamente, a través de la desigualdad AM-GM, "cuál es el valor máximo de entropía entre los estados accesibles". El aumento monotónico de la segunda ley es entonces la consecuencia dinámica necesaria de la regla impulsada por gradientes bajo la restricción de la conservación de la energía.

### 3.3 Relación con la Termodinámica Clásica

En la formulación tradicional de la entropía estadística, no existe una relación derivacional matemática explícita entre la primera y la segunda ley. El estado de máxima entropía S_max = k_B ln Ω_max se obtiene generalmente mediante métodos estadísticos (como la suposición de igual probabilidad a priori), en lugar de derivarse directamente de la conservación de la energía.

En este marco, el valor máximo de entropía S_max = (E / N)ᴺ se deriva directamente de la conservación de la energía, sin requerir ninguna suposición probabilística. Esto representa una diferencia epistemológica fundamental entre las dos formulaciones de la entropía:

| Dimensión | Entropía Estadística Tradicional | Entropía Multiplicativa |
|-----------|----------------------------------|-------------------------|
| Origen del máximo de entropía | Suposiciones estadísticas (igual probabilidad a priori) | Conservación de la energía (desigualdad AM-GM) |
| Necesidad del aumento de entropía | Probabilística ("más probable") | Necesaria (garantizada por la regla impulsada por gradientes) |
| Papel de la primera ley | Postulado independiente junto a la segunda ley | Precondición de restricción para la segunda ley |
| Fundamento de la segunda ley | Suposiciones de conjuntos estadísticos | Regla impulsada por gradientes + conservación de la energía |

### 3.4 Ejemplo Numérico

Considérese un sistema con N = 4 nodos y energía total E = 12. La cota superior de la entropía multiplicativa es:

S_max = (12 / 4)⁴ = 3⁴ = 81

Cuando el sistema se encuentra en un estado no uniforme [3, 1, 5, 3]:

S = 3 × 1 × 5 × 3 = 45

Bajo la regla impulsada por gradientes, mediante transferencias sucesivas de energía, el sistema puede evolucionar al estado uniforme [3, 3, 3, 3]:

S = 3 × 3 × 3 × 3 = 81 = S_max

Los valores de entropía en cada paso son:

| Estado | Distribución de Energía | Entropía Multiplicativa | Aumento respecto al Anterior |
|--------|-------------------------|-------------------------|------------------------------|
| Inicial | [3, 1, 5, 3] | 45 | — |
| Intermedio | [3, 2, 4, 3] | 72 | +27 |
| Final | [3, 3, 3, 3] | 81 | +9 |

La entropía aumenta estrictamente en cada paso hasta alcanzar el valor máximo acotado por la desigualdad AM-GM.

Vale la pena señalar que, dado que la energía se transfiere en cuantos enteros, no todos los sistemas pueden alcanzar una distribución perfectamente uniforme. Por ejemplo, cuando la energía total E no es divisible por N, el estado de máxima entropía es la distribución en la que todas las energías de los nodos son lo más cercanas posible. La entropía multiplicativa sigue satisfaciendo la cota superior S ≤ (E / N)ᴺ.

## 4. La Necesidad de la Evolución Impulsada por Gradientes: Eliminación de la Interpretación Probabilística

### 4.1 Equivalencia entre la "Trayectoria de Máxima Entropía" y la "Trayectoria de Máximo Gradiente"

En este marco, cada paso de transferencia de energía sigue la dirección del máximo gradiente de energía. La razón entre la entropía antes de la transferencia S y la entropía después de la transferencia S′ es:

S′ / S = 1 + (a − b − 1) / (a · b)



Esta expresión muestra directamente: cuanto mayor es el gradiente de energía, mayor es el aumento de entropía. Por lo tanto, en este marco, la "trayectoria de máxima entropía" y la "trayectoria de máximo gradiente" son equivalentes—el sistema evoluciona en la dirección del máximo aumento de entropía, que es precisamente la dirección del máximo gradiente de energía.

Esta equivalencia transforma la segunda ley de la termodinámica de una declaración estadística sobre la "probabilidad" en una declaración dinámica sobre el "gradiente".

### 4.2 Necesidad vs. Probabilidad del Aumento de Entropía

En la mecánica estadística tradicional, la formulación de la segunda ley se basa en un lenguaje probabilístico:

- "La entropía de un sistema aislado tiende a aumentar."
- "Los estados de alta entropía son más probables que los estados de baja entropía."
- "El sistema tiende hacia el estado macroscópico más probable."

Estas afirmaciones son matemáticamente válidas, pero dejan una cuestión abierta a nivel conceptual: ¿qué significa "tiende"? Si el sistema solo es "más probable" de moverse hacia un estado de alta entropía, ¿el aumento de entropía es una necesidad física o una contingencia estadística?

En este marco, esta cuestión se elimina por completo:

- Siempre que exista un gradiente de energía, la energía fluirá a lo largo del gradiente;
- Cada paso de flujo aumenta el valor de entropía;
- Este proceso no tiene excepciones y no depende de ninguna suposición estadística.

La segunda ley ya no es:

"Un sistema aislado se moverá muy probablemente hacia un estado de alta entropía."

Sino más bien:

"Un sistema aislado con un gradiente de energía redistribuirá necesariamente su distribución de energía a lo largo de la dirección del gradiente; este proceso de redistribución es precisamente el proceso de aumento de entropía."

### 4.3 Diferencias Epistemológicas Entre las Dos Formulaciones

Tabla 1: La tabla muestra los resultados del estudio.

| Dimensión | Formulación Estadística Tradicional | Formulación en Este Marco |
|-----------|-------------------------------------|---------------------------|
| Naturaleza del aumento de entropía | "Probable" | "Necesaria" |
| Definición de entropía | Logaritmo del "número de microestados" | "Producto de la distribución de energía" |
| Base de la segunda ley | Depende de suposiciones de conjuntos estadísticos | Derivada directamente de reglas impulsadas por gradientes |
| Prerrequisito | La probabilidad es un prerrequisito | La probabilidad no es un prerrequisito; el gradiente sí |
| Engrosamiento | El engrosamiento es necesario | El engrosamiento no es necesario |

Esta diferencia afecta directamente nuestra comprensión de la "irreversibilidad". En este marco, la irreversibilidad está escrita directamente en las reglas dinámicas—el flujo de energía a lo largo de un gradiente es irreversible, porque el flujo inverso requeriría que la energía se moviera de bajo a alto, lo que viola la precondición de la impulsión por gradientes. La irreversibilidad no es un subproducto estadístico, sino un producto directo de la impulsión por gradientes.

## 5. Compatibilidad con la Termodinámica Clásica

### 5.1 Recuperación en el Límite Macroscópico

Aunque este marco se basa en una red de nodos discretos, en el límite macroscópico apropiado (número de nodos N → ∞, cuanto de energía h → 0), la entropía multiplicativa puede recuperar los resultados de la termodinámica clásica.

Tomando el logaritmo de la entropía multiplicativa:

ln S = ∑ᵢ ln mᵢ

En condiciones en las que la distribución de energía es relativamente suave, los métodos estándar de la mecánica estadística pueden establecer una correspondencia entre ln S y la entropía de Boltzmann S_Boltzmann = k_B ln Ω. El aumento monotónico de la entropía multiplicativa se preserva bajo la transformación logarítmica, y por lo tanto es consistente con el principio clásico de aumento de entropía.

### 5.2 Reinterpretación de los Conceptos Termodinámicos Clásicos



### 5.3 Condiciones de Aplicabilidad

Un sistema puede adoptar una descripción de entropía multiplicativa si satisface las siguientes condiciones:

1. El número de unidades que portan valores numéricos permanece constante;
2. Cada unidad está asociada con un valor cuantificable (por ejemplo, energía, cantidad de recursos o tamaño de población);
3. La suma total de todos los valores de las unidades se conserva;
4. La evolución dinámica sigue una regla de flujo o intercambio en la que las cantidades se transfieren desde unidades con valores más altos hacia aquellas con valores más bajos;
5. El valor numérico portado por cada unidad puede ser unitizado, es decir, expresado como un múltiplo entero de la unidad básica. La quinta condición no es un requisito necesario para la definición de la entropía multiplicativa misma. Sin embargo, satisfacer esta condición asegura que el valor de entropía calculado sea un número entero, lo cual es particularmente conveniente para simulaciones computacionales e implementaciones numéricas.

## 6. Conclusión

Este artículo, basado en el marco de entropía multiplicativa impulsada por gradientes propuesto por Zou (2025), ha demostrado la existencia de una estructura de restricción matemática precisa entre la primera y la segunda ley de la termodinámica:

La primera ley (conservación de la energía) E = ∑ᵢ mᵢ = constante, como precondición de restricción, produce directamente la cota superior matemática de la entropía multiplicativa S = ∏ᵢ mᵢ mediante la desigualdad de las medias aritmética y geométrica: S ≤ (E / N)ᴺ. La segunda ley (aumento de la entropía) es entonces el producto dinámico necesario de la regla impulsada por gradientes bajo esta restricción—cada paso legítimo de transferencia de energía incrementa estrictamente la entropía multiplicativa hasta alcanzar el valor máximo acotado por la desigualdad AM-GM.

Las contribuciones centrales de este marco son:

1. Revela la relación de restricción matemática entre la primera y la segunda ley: ya no son postulados independientes que coexisten, sino que se complementan mutuamente como "restricción" e "impulso";
2. Elimina la interpretación probabilística del aumento de entropía: el aumento de entropía ya no es una "posibilidad" estadística, sino una consecuencia necesaria determinada conjuntamente por la conservación de la energía y la existencia de gradientes;
3. Proporciona una definición no probabilística de la entropía: la entropía multiplicativa no depende de la elección de engrosamiento del observador, y está enteramente determinada por la distribución de energía del propio sistema;
4. Establece la equivalencia entre la trayectoria de máxima entropía y la trayectoria de máximo gradiente: la dirección del máximo aumento de entropía es precisamente la dirección del máximo gradiente de energía, proporcionando una base dinámica intuitiva para la segunda ley.

Desde una perspectiva epistemológica, este marco reduce las dos leyes de la termodinámica de una "formulación estadística" a una "formulación geométrico-dinámica"—el aumento de entropía ya no es una proposición vaga dependiente del lenguaje probabilístico, sino un proceso evolutivo irreversible directamente impulsado por gradientes de energía y rastreable paso a paso. En este marco, los principios fundamentales de la termodinámica son visibles, comprensibles y contables. Ya no responde a "lo que no sabemos". Responde: "qué está sucediendo, y cómo está sucediendo."

## Referencias:

[1]Max Planck. (1901). Ueber das Gesetz der Energieverteilung im Normalspectrum. Annalen der Physik. https://doi.org/10.1002/andp.19013090310 

[2]Annila A(2025), Comprehensible dynamics of quanta: from the quantum of action to the 2nd law of thermodynamics. Eur. Phys. J. Plus 140, 28 2025. https://doi.org/10.1140/epjp/s13360-025-05970-5   

[3]Zou,  Z. K. (2025). The Thermodynamic Arrow of Time in a Double-Layer Topology-Invariant Chiral Space with Geometric (GR) and Gauge (QFT) Degrees of Freedom :Time-Entropy Mapping; Mass-Gravity Duality; Metric-Frequency Mirroring. Preprints. https://doi.org/10.20944/preprints202505.0270.v12 

[4]Graham, C., & Tokieda, T. (2020). An Entropy Proof of the Arithmetic Mean–Geometric Mean Inequality. The American Mathematical Monthly, 127(6), 545–546. https://doi.org/10.1080/00029890.2020.1738827

[5]Petri Tuisku, Tuomas K Pernu, Arto Annila(2009); In the light of time. Proc. A 1 April 2009; 465 (2104): 1173–1198. https://doi.org/10.1098/rspa.2008.0494 
