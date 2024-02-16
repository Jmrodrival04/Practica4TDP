# Ejercicio11

INICIO

# Función crearPatrón(tipo, tamaño, carácter)
    - Inicializar variable patrón como cadena vacía
    - Si tipo es "rectángulo" entonces:
        - Para i de 0 hasta tamaño hacer:
            - Agregar una línea de 'carácter' repetido 'tamaño' veces a patrón
            - Agregar salto de línea a patrón
    - Si tipo es "triángulo" entonces:
        - Para i de 1 hasta tamaño + 1 hacer:
            - Agregar una línea de 'carácter' repetido 'i' veces a patrón
            - Agregar salto de línea a patrón
    - Si tipo es "rombo" entonces:
        - Para i de 1 hasta tamaño hacer:
            - Agregar espacios para centrar 'carácter' en la línea
            - Agregar 'carácter' repetido '2*i - 1' veces (forma ascendente) a patrón
            - Agregar salto de línea a patrón
        - Para i de tamaño - 1 hasta 1 hacer:
            - Agregar espacios para centrar 'carácter' en la línea
            - Agregar 'carácter' repetido '2*i - 1' veces (forma descendente) a patrón
            - Agregar salto de línea a patrón
    - Retornar patrón

# Función mostrarPatrón(patrón)
    - Imprimir el patrón en consola o interfaz de usuario

# Función obtenerTipoPatrón()
    - Solicitar al usuario que ingrese el tipo de patrón (rectángulo, triángulo, rombo)
    - Retornar el tipo de patrón

# Función obtenerTamaño()
    - Solicitar al usuario que ingrese el tamaño del patrón
    - Retornar el tamaño

# Función obtenerCarácter()
    - Solicitar al usuario que ingrese el carácter a utilizar en el patrón
    - Retornar el carácter

# Función generarPatrónASCII(tipo, tamaño, carácter)
    - patrón = crearPatrón(tipo, tamaño, carácter)
    - mostrarPatrón(patrón)

# Función principal()
    - tipo = obtenerTipoPatrón()
    - tamaño = obtenerTamaño()
    - carácter = obtenerCarácter()
    - generarPatrónASCII(tipo, tamaño, carácter)

# Llamar a la Función principal

FIN
