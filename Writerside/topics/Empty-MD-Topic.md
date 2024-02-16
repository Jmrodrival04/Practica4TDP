# Ejercicio4

INICIO

# Importar la librería NLTK
# Importar SentimentIntensityAnalyzer desde nltk.sentiment

# FUNCION determinarSentimiento(comentario)
    - Inicializar SentimentIntensityAnalyzer como sia
    - Obtener puntajes de polaridad del comentario usando sia
    - Asignar a compuesto el valor del puntaje 'compound'
    - SI compuesto es mayor o igual a 0.05 ENTONCES
        - RETORNAR 'Positivo'
    - SINO SI compuesto es menor o igual a -0.05 ENTONCES
        - RETORNAR 'Negativo'
    - SINO
        - RETORNAR 'Neutral'

# FUNCION obtenerComentarios()
    - RETORNAR lista de comentarios ["Este producto es excelente", "No me gustó el producto", "Podría ser mejor", "Estoy indiferente"]

# FUNCION analizarComentarios(comentarios)
    - PARA CADA comentario EN comentarios HACER
        - sentimiento = determinarSentimiento(comentario)
        - Imprimir "Comentario: ", comentario, " - Sentimiento: ", sentimiento

# Ejecución principal
    - comentarios = obtenerComentarios()
    - analizarComentarios(comentarios)

FIN
