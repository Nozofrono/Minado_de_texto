{
  "titulo": "Análisis Exploratorio de Textos",
  "autor": "Juan Mesa",
  "descripcion_general": "Este proyecto se centra en el análisis lingüístico y semántico de dos textos literarios en español: “El inspector Cambalache y el robo en el museo” y “Los dos gemelos y la caja mágica”. El objetivo principal es extraer patrones relevantes del contenido textual mediante técnicas de procesamiento de lenguaje natural (PLN), incluyendo limpieza y normalización del texto, análisis léxico, extracción de relaciones gramaticales y visualización de resultados.",
  "informacion_sobre_textos": "Los textos analizados son narrativas infantiles que combinan aventura y elementos fantásticos. “El inspector Cambalache y el robo en el museo” presenta un misterio centrado en un robo en un museo, con personajes que interactúan con objetos mágicos y cotidianos, mientras que “Los dos gemelos y la caja mágica” narra las peripecias de dos hermanos frente a una caja con propiedades extraordinarias, combinando acción y elementos fantásticos.",
  "descripcion_analisis_exploratorio": {
    "preprocesamiento": "Ambos textos fueron procesados inicialmente para eliminar ruido como etiquetas HTML, URLs, emojis y signos de puntuación, generando versiones normalizadas (texto_normalizado_Cambalache y texto_normalizado_Caja) listas para un análisis más limpio y preciso.",
    "hallazgos": [
      "A partir del análisis de frecuencia y generación de nubes de palabras, se identificaron palabras significativas en cada texto que reflejan sus temáticas principales. En 'El inspector Cambalache y el robo en el museo' destacan términos como caja, deseo, hermano y gemelo. En 'Los dos gemelos y la caja mágica' sobresalen las mismas palabras, reflejando similitud temática.",
      "El análisis específico de sustantivos, verbos y adjetivos mostró que ambos textos utilizan sustantivos relacionados con objetos mágicos y familiares (caja, hermano, deseo), verbos que reflejan acciones de interacción y movimiento (pedir, hacer, abrir) y adjetivos que evocan magia y características de los personajes (mágico, egoísta, precioso).",
      "La identificación de tripletas Sujeto-Verbo-Objeto mostró acciones clave como ('hermano', 'brillar', 'él') en ambos textos, indicando la presencia de personajes activos que realizan acciones sobre otros, aunque con limitaciones propias del análisis automático.",
      "La diversidad léxica calculada con la función calcular_diversidad_lexica mostró un valor idéntico de 0.5060 para ambos textos, reflejando un nivel moderado de variedad en el vocabulario.",
      "Ambos textos presentan una predominancia de palabras de longitud media (5 a 7 caracteres), con máximos en palabras de 5, 6 y 7 letras, mostrando consistencia en la estructura léxica típica de textos narrativos infantiles."
    ]
  },
  "librerias_utilizadas": [
    "re",
    "spacy",
    "wordcloud",
    "matplotlib.pyplot"
  ]
}
