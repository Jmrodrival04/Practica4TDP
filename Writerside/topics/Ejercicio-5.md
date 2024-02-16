# Ejercicio 5

INICIO

# ESTRUCTURA DatosAmbientales:
    - temperatura: REAL
    - humedad: REAL
    - calidadAire: REAL

# FUNCIÓN obtenerDispositivosIoT(): LISTA<DispositivoIoT>
    - Inicializar una lista vacía de DispositivoIoT
    - Código para detectar dispositivos IoT o comunicarse con una API
    - RETORNAR lista de dispositivos IoT

# FUNCIÓN recolectarDatos(dispositivos): LISTA<DatosAmbientales>
    - Inicializar una lista vacía de DatosAmbientales
    - PARA CADA dispositivo EN lista de dispositivos:
        - Crear un nuevo objeto DatosAmbientales
        - Asignar temperatura, humedad y calidadAire leyendo valores del dispositivo
        - Agregar el objeto DatosAmbientales a la lista de datos
    - RETORNAR lista de DatosAmbientales

# FUNCIÓN mostrarInterfazUsuario(datos: LISTA<DatosAmbientales>)
    - PARA CADA dato EN lista de DatosAmbientales:
        - MOSTRAR "Temperatura: " + dato.temperatura + "°C"
        - MOSTRAR "Humedad: " + dato.humedad + "%"
        - MOSTRAR "Calidad del aire: " + dato.calidadAire

# FUNCIÓN programarAlertas(datos: LISTA<DatosAmbientales>)
    - PARA CADA dato EN lista de DatosAmbientales:
        - SI calidadAire de dato es menor que UMBRAL_CALIDAD_AIRE:
            - ENVIAR_ALERTA("Calidad del aire baja", dato)
        - Considerar otros eventos basados en temperatura y humedad

# FUNCIÓN almacenarDatos(datos: LISTA<DatosAmbientales>)
    - Implementar código para almacenar datos en una base de datos

# FUNCIÓN monitorearAmbiente()
    - Llamar a obtenerDispositivosIoT() y asignar a dispositivos
    - Llamar a recolectarDatos(dispositivos) y asignar a datos
    - Llamar a mostrarInterfazUsuario(datos)
    - Llamar a programarAlertas(datos)
    - Llamar a almacenarDatos(datos)

# Llamar a monitorearAmbiente() para iniciar el monitoreo

FIN
