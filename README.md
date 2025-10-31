# *Análisis Exploratorio de Textos*

***Autor:** Juan Mesa.*

*Este proyecto se centra en el análisis lingüístico y semántico de dos textos literarios en español: “El inspector Cambalache y el robo en el museo” y “Los dos gemelos y la caja mágica”. El objetivo principal es extraer patrones relevantes del contenido textual mediante técnicas de procesamiento de lenguaje natural (PLN), incluyendo limpieza y normalización del texto, análisis léxico, extracción de relaciones gramaticales y visualización de resultados.*

## *Información sobre los textos*

*Los textos analizados son narrativas infantiles que combinan aventura y elementos fantásticos. “El inspector Cambalache y el robo en el museo” presenta un misterio centrado en un robo dentro de un museo, con personajes que interactúan con objetos mágicos y cotidianos, mientras que “Los dos gemelos y la caja mágica” narra las peripecias de dos hermanos frente a una caja con propiedades extraordinarias, mezclando acción y elementos fantásticos.*

## *Descripción del Análisis Exploratorio de Texto*

*Ambos textos fueron procesados inicialmente para limpiar el contenido de ruido como etiquetas HTML, URLs, emojis y signos de puntuación, permitiendo un análisis más limpio y preciso.*  
*Finalizado este proceso, se llevaron a cabo varios análisis exploratorios que permitieron identificar los siguientes hallazgos:*

   - *A partir del análisis de frecuencia y generación de nubes de palabras, se identificaron palabras significativas en cada texto que reflejan sus temáticas principales. En “El inspector Cambalache y el robo en el museo” destacan términos como caja, deseo, hermano y gemelo. En “Los dos gemelos y la caja mágica” sobresalen las mismas palabras, reflejando la similitud temática entre ambos textos.*
   - *El análisis específico de sustantivos, verbos y adjetivos reveló patrones consistentes. Ambos textos utilizan sustantivos relacionados con objetos mágicos y familiares (caja, hermano, deseo), verbos que reflejan acciones de interacción y movimiento (pedir, hacer, abrir) y adjetivos que evocan magia y características de los personajes (mágico, egoísta, precioso).*
   - *La identificación de tripletas Sujeto-Verbo-Objeto mostró acciones clave como ('hermano', 'brillar', 'él') en ambos textos, indicando la presencia de personajes activos que realizan acciones sobre otros, aunque con limitaciones propias del análisis automático, como interpretaciones literales de metáforas.*
   - *Se encontró que ambos textos presentan una diversidad léxica de 0.5060, indicando que aproximadamente la mitad de las palabras son únicas, lo que refleja un nivel moderado de variedad en el vocabulario relativo a su extensión.*
   - *Ambos textos presentan una predominancia de palabras de longitud media (5 a 7 caracteres), con máximos en palabras de 5, 6 y 7 letras, mostrando consistencia en la estructura léxica típica de textos narrativos infantiles.*

## *Librerías utilizadas:*

*Para realizar el análisis exploratorio de los textos, se utilizaron las siguientes librerías:*

  - *re*  
  - *spacy*  
  - *wordcloud*  
  - *matplotlib.pyplot*
