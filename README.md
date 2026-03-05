## Movilidad urbana y productividad económica en ciudades de LATAM | TripleTen Bootcamp (2026) Académico

Entender cómo la movilidad urbana (niveles de congestión, tiempos de viaje, retrasos) se relaciona con la productividad económica (PIB per cápita, desempleo) en las principales ciudades latinoamericanas.

**Objetivo:**  identificar en qué ciudades invertir en infraestructura de transporte para aumentar la productividad y el bienestar de la población.

### Herramientas

<aside>
🛠 **Python | Numpy | Matplotlib | Seaborn |Jupyter Notebook**

</aside>

### Preguntas clave

1. ¿Qué ciudades de América Latina presentan alta congestión y baja productividad económica?
2. ¿Cuáles muestran los mejores indicadores combinados (movilidad eficiente y economía fuerte)?
3. ¿Qué variables parecen tener una relación más fuerte con el desarrollo urbano?

### Metodología

- Crucé datos de tráfico de TomTom con indicadores económicos de la OECD usando Python y Pandas.
- Se creó un dataset único y limpio a partir de dos fuentes diferentes, aplicando limpieza, estandarización y validación de tipos de datos.
- Filtró y enfocó el análisis en ciudades latinoamericanas, luego, calculó indicadores agregados (por ciudad–año).
- Por último, se unen los dos DataFrames en un solo dataset con información unificada por ciudad, generando gráficos para explorar patrones entre tráfico y economía y así, redactar un informe ejecutivo con hallazgos, implicaciones y reflexiones personales sobre la relación entre economía y movilidad.

### Hallazgos y recomendaciones

- Las ciudades con mayor PIB tienden a ser más grandes, las ciudades más grandes tienden a tener más congestión. Es decir, el PIB puede estar relacionado indirectamente con la congestión a través del tamaño urbano y la densidad, no de forma directa.
- Bogotá aparece consistentemente con tiempos de retraso altos (1.70 mins delay) comparado con muchas otras ciudades latinoamericanas (Buenos Aires 0.42, Belo Horizonte 0.49), no es una de las ciudades con PIB per cápita más altas, lo que sugiere que la congestión puede estar impactando proporcionalmente más la productividad, mejorar la movilidad aquí probablemente tenga ganancias económicas más visibles.

En conclusión, Bogotá emerge como el caso más claro que combina congestión alta con un PIB per cápita comparativamente menor, lo que la haría prioritaria para inversión en infraestructura de movilidad.
