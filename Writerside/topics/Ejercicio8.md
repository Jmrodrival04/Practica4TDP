# Ejercicio8

INICIO

# Inicializar citasConContexto como una lista de diccionarios con 'cita', 'autor' y 'contextos'

# Función cargarCitasConContexto()
    - Leer citas de un archivo o base de datos y llenar citasConContexto

# Función obtenerContextoUsuario()
    - Solicitar al usuario que ingrese su contexto/estado de ánimo
    - Retornar el contexto ingresado

# Función obtenerCitaPorContexto(contexto)
    - citasFiltradas = Filtrar citasConContexto donde el contexto esté en la lista de 'contextos' de cada cita
    - Si citasFiltradas no está vacía:
        - Retornar una cita aleatoria de citasFiltradas
    - De lo contrario:
        - Retornar "Lo siento, no tengo citas para ese contexto específico."

# Función generarCitaConContexto()
    - contexto = obtenerContextoUsuario()
    - cita = obtenerCitaPorContexto(contexto)
    - Imprimir("Cita Inspiradora:", cita)

# Función principal()
    - cargarCitasConContexto()
    - Mientras verdadero:
        - generarCitaConContexto()
        - accion = Solicitar al usuario si desea continuar o salir
        - Si accion es igual a 'salir':
            - Terminar el bucle

# Ejecutar la función principal

FIN
