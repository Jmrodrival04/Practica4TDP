# Ejercicio 6

INICIO

# FUNCIÓN preprocesarDatos(datos)
    - Limpiar los datos para eliminar valores nulos o atípicos
    - Normalizar los datos para escalarlos a un rango común
    - Extraer características automáticamente de los datos normalizados
    - RETORNAR características

# FUNCIÓN balancearClases(datos)
    - Aplicar técnicas de sobremuestreo para equilibrar las clases en los datos
    - RETORNAR datos balanceados

# FUNCIÓN seleccionarCaracterísticas(datos)
    - Seleccionar las características más relevantes utilizando un método específico
    - RETORNAR datos con solo las características seleccionadas

# FUNCIÓN entrenarModelosDeEnsamble(datosEntrenamiento)
    - Entrenar múltiples modelos con los datos de entrenamiento
    - Combinar los modelos entrenados en un modelo de ensamble
    - RETORNAR modelo de ensamble

# FUNCIÓN validaciónCruzada(modelo, datos)
    - Realizar validación cruzada del modelo con los datos para estimar su rendimiento
    - RETORNAR resultados de la validación cruzada

# FUNCIÓN evaluarModelo(modelo, datosPrueba)
    - Calcular métricas de evaluación del modelo usando los datos de prueba
    - RETORNAR métricas de evaluación

# FUNCIÓN esFraudulenta(transacción, modelo)
    - Predecir si una transacción es fraudulenta utilizando el modelo
    - RETORNAR resultado de la predicción

# FUNCIÓN detectarFraude(transacciones, modelo)
    - PARA CADA transacción EN transacciones
        - SI esFraudulenta(transacción, modelo) ENTONCES
            - ENVIAR_ALERTA("Transacción Fraudulenta Detectada")

# Flujo Principal
    - Obtener un conjunto de transacciones
    - Preprocesar los datos de las transacciones llamando a preprocesarDatos
    - Balancear las clases de los datos preprocesados llamando a balancearClases
    - Seleccionar características relevantes de los datos balanceados llamando a seleccionarCaracterísticas
    - Dividir los datos en conjuntos de entrenamiento y prueba
    - Entrenar un modelo de ensamble con el conjunto de entrenamiento llamando a entrenarModelosDeEnsamble
    - Realizar validación cruzada con el modelo y el conjunto de entrenamiento llamando a validaciónCruzada
    - Evaluar el modelo con el conjunto de prueba llamando a evaluarModelo
    - Para implementación en tiempo real, detectar fraude en nuevas transacciones utilizando el modelo entrenado llamando a detectarFraude

FIN
