-   [ ] Investiguen un poco sobre cómo se relacionan los contaminantes del aire, y cómo y a qué biomarcadores impactan.
    -   [ ] Con ayuda de compañerxs o profesorxs de medicina y química realicen lo siguiente:
        -   [x] Conseguir Experto 1
        -   [ ] Conseguir Experto 2
        -   [ ] Conseguir Experto 3
    -   Revisen la información de la ENSANUT y decidan qué **variables numéricas** biológicas y socio-demográficas incluirán en su estudio de modo que se alineen al objetivo del proyecto, es decir, qué factores ambientales influyen en la salud mexicana y qué biomarcadores se ven afectados.
    -   Entrevisten a al menos 3 personas especialistas (pueden ser del campus o externas) que les ayuden a proponer una DAG que represente las relaciones de dependencia, es decir, contarán al final con al menos 3 estructuras diferentes de redes.
        -   Una vez que cuenten con una selección de variables que les satisfaga, construyan el conjunto de datos que utilizarán. Para ello será necesario unir diferentes tablas para obtener la información necesaria. En el caso de los contaminantes del aire asumiremos lo siguiente.

            -   La información que tenemos es comparable con las condiciones a las que estuvieron sujetas las personas que participaron en la ENSANUT 2022, es decir, asumiremos que los valores de reporta la SEMARNAT para 2025 son buenas estimaciones para esos contaminantes en 2022.

        -   Necesitarán considerar, ya sea sólo en el Estado donde reside la persona entrevistada o su municipio, para cruzar esta información con la que contiene la tabla sobre calidad del aire y deberán elegir una sola fuente de información de esta última tabla para obtener los datos sobre los contaminantes para cada persona. **Hint**: Consideren la fuente que tenga menos valores faltantes, por ejemplo, las fuentes fijas casi siempre contienen información para todos los municipios.
-   [ ] Ajusten una GBN para cada una de las DAG propuestas.
-   [ ] Reporten el BIC y el AIC para cada GBN.
-   [ ] Investiguen y discutan cómo podrían incluir las variables categóricas a la red, por ejemplo, una variable de interés puede ser el sexo.
-   [ ] Con la mejor estructura que han encontrado hasta el momento, intenten incluir el sexo de las personas.
-   [ ] Con ayuda de las personas especialistas propongan al menos 3 queries que podrían resolver utilizando su red bayesiana y respóndalas usando su mejor modelo.
-   [ ] Investiguen si incluir modelos no paramétricos les ayuda a mejorar el BIC y el AIC de su mejor modelo.
-   [ ] Redacten un artículo científico que incluya un abstract, introducción, descripción de los métodos que utilizaron, aplicación de los métodos al problema en cuestión, conclusiones y referencias.
