# Ejercicio 10

INICIO

# Función convertirAASCII(imagen, resolución, caracteres)
    - Redimensionar imagen según la resolución indicada
    - Para cada píxel en la imagen redimensionada hacer:
        - Convertir el píxel a escala de grises
        - Seleccionar un carácter de 'caracteres' basado en la intensidad del píxel
        - Agregar el carácter seleccionado al arte ASCII
    - Retornar el arte ASCII generado

# Función mostrarArte(arte)
    - Imprimir el arte ASCII en consola o interfaz de usuario

# Función obtenerImagenUsuario()
    - Solicitar al usuario que cargue o especifique el path de una imagen
    - Retornar la imagen

# Función obtenerResolución()
    - Solicitar al usuario que ingrese la resolución deseada para el arte ASCII
    - Retornar la resolución

# Función obtenerCaracteres()
    - Solicitar al usuario que ingrese los caracteres a utilizar en el arte ASCII
    - Retornar los caracteres

# Función crearArteASCII(imagen, resolución, caracteres)
    - arte = convertirAASCII(imagen, resolución, caracteres)
    - mostrarArte(arte)

# Función principal()
    - imagen = obtenerImagenUsuario()
    - resolución = obtenerResolución()
    - caracteres = obtenerCaracteres()
    - crearArteASCII(imagen, resolución, caracteres)

# Llamar a la Función principal

FIN
