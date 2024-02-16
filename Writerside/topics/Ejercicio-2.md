# Ejercicio2
    - Constructor que inicializa:
        - nombre
        - tipo
        - capacidad (en Gbps)
    - Método para convertir el dispositivo a cadena de texto

# Definir clase Red con:
    - Constructor que inicializa lista de dispositivos
    - Método para añadir dispositivo:
        - Añade un dispositivo a la lista de dispositivos
        - Imprime mensaje de dispositivo añadido
    - Método para mostrar dispositivos:
        - Si la lista está vacía, imprime mensaje correspondiente
        - Si no, imprime todos los dispositivos en la lista
    - Método para simular tráfico:
        - Si la lista está vacía, imprime mensaje correspondiente y termina
        - Si no, para cada dispositivo en la lista:
            - Genera un valor aleatorio de carga de tráfico
            - Imprime la carga de tráfico para el dispositivo
            - Si la carga supera la capacidad del dispositivo, imprime alerta de cuello de botella
            - Si no, imprime mensaje de procesamiento correcto

# Definir función obtenerConfiguraciónUsuario para interactuar con el usuario:
    - Crear una instancia de Red
    - Mostrar menú de acciones al usuario con las opciones:
        - Añadir un dispositivo a la red
        - Mostrar dispositivos en la red
        - Simular tráfico en la red
        - Salir
    - Según la elección del usuario:
        - Si elige añadir dispositivo, solicita detalles del dispositivo y lo añade a la red
        - Si elige mostrar dispositivos, muestra los dispositivos en la red
        - Si elige simular tráfico, simula el tráfico en la red
        - Si elige salir, termina el ciclo

# Definir función main para:
    - Imprimir mensaje de bienvenida
    - Llamar a obtenerConfiguraciónUsuario

# Si el programa se ejecuta como script principal, llama a main

FIN
