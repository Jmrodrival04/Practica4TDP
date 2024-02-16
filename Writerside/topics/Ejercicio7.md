# Ejercicio7

INICIO

# Inicializar lista de citas vacía

# Función cargarCitas(archivo)
    - Abrir archivo para lectura
    - Para cada línea en el archivo hacer:
        - Dividir la línea en cita y autor usando '|' como delimitador
        - Agregar la cita y el autor a la lista de citas
    - Cerrar archivo

# Función obtenerCitaAleatoria()
    - Si la lista de citas no está vacía entonces:
        - Seleccionar aleatoriamente una cita de la lista
    - De lo contrario:
        - Retornar None

# Función generarCita()
    - citaSeleccionada = obtenerCitaAleatoria()
    - Si citaSeleccionada no es None entonces:
        - Imprimir la cita y el autor de forma amigable
    - De lo contrario:
        - Imprimir mensaje indicando que no hay citas disponibles

# Función principal()
    - Llamar a cargarCitas() con la ruta del archivo de citas
    - Si la lista de citas está vacía entonces:
        - Imprimir mensaje de error y terminar el programa
    - De lo contrario:
        - Mientras verdadero hacer:
            - Llamar a generarCita()
            - Solicitar al usuario acción (nueva cita o salir)
            - Si el usuario decide salir entonces:
                - Terminar el bucle

# Iniciar ejecución de la función principal

FIN

