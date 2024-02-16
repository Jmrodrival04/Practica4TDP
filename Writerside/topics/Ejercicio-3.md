# Ejercicio 3

INICIO

# FUNCIÓN obtenerDatosRedesSociales
    - Obtener datos de redes sociales para análisis
    - RETORNAR datos

# FUNCIÓN prepararPrompt(datos)
    - Preparar el prompt para análisis usando los datos
    - RETORNAR prompt

# FUNCIÓN enviarSolicitudAnalisis(prompt)
    - Enviar solicitud de análisis a la API
    - RETORNAR respuesta de la API

# FUNCIÓN identificarTendencias(respuesta)
    - Identificar tendencias a partir de la respuesta de la API
    - RETORNAR lista de tendencias

# FUNCIÓN procesarRespuesta(respuesta)
    - Procesar la respuesta de la API para imprimir las tendencias
    - Llamar a identificarTendencias con respuesta para obtener tendencias
    - PARA CADA tendencia EN lista de tendencias
        - Imprimir "Tendencia: " seguido de la tendencia

# FUNCIÓN analizarTendencias(datos)
    - Llamar a prepararPrompt con datos para obtener prompt
    - Llamar a enviarSolicitudAnalisis con prompt para obtener respuesta
    - Llamar a procesarRespuesta con respuesta

# Flujo principal
    - Llamar a obtenerDatosRedesSociales para obtener datos
    - Llamar a analizarTendencias con datos

FIN
