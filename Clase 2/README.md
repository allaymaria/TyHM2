# IA Generativa

Profesora: Ing. Selva S. Rivera

Herramienta: NotebookLM

**¿Qué es la Inteligencia Artificial?**

Algoritmos que procesan datos. Ocurre un procedimiento estocástico avanzado que opera en un espacio vectorial de alta dimensión. Obtenemos resultados probabilísticos.
1. *Tokenización:* la discretización del lenguaje. Muestreo y Cuantización. Word gasta muchos tokens, por los códigos ocultos que también lee. El lenguaje que menos tokens gasta es el Markdown.
2. *Embeddings:* el espacio vectorial. Cada token  se convierte en un vector. El transformer no lee en forma secuencial, sino que relaciona todo en conjunto.
3. *Generación:* el proceso estocástico. Un calculo de probabilidades para predecir los próximos tokens. Al aumentar una variable T llamada temperatura del calculo de probabilidad se puede alejar de nuestra respuesta o acercarse, aumentamos el rango en lo que busca. Le da probabilidades a todos los tokens y hace un ranking, y de todas las posibilidades una vez devuelve una y la siguiente otra.

Red neuronal Transformer. 

**¿Cómo utilizarla?**
* Es importante el prompt.
* No colocar "Por favor" si queremos respuestas más técnicas.
* La decisión final sigue siendo humana.

## Prompt
Formulación de instrucciones que produce respuestas más útiles.
1. Rol esperado: Desde que perspectiva debe responder la herramienta.
2. Objetivo.
3. Datos disponibles: Ser exacto, especificaciones, información técnica que necesita conocer la herramienta.
4. Restricciones: Límites o condiciones.
5. Producto a obtener: Indicar el resultado concreto de la consulta.
6. Formato de salida: Especificar como debe presentarse la respuesta. Darle ejemplos, referencias.

**Para imágenes:**
* Objetivo o Escena
* Acción o Situación
* Contexto o Entorno
* Atributos Visuales
* Estilo Visual
* Composición


