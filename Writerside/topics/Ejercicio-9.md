# Ejercicio 9

INICIO

# Función comprobarCaracteresVálidos(expresión)
    - para cada carácter en expresión hacer:
        - si no esDígito(carácter) y no esOperador(carácter) y no esParéntesis(carácter) entonces:
            - retornar falso
    - retornar verdadero

# Función comprobarOperadores(expresión)
    - para i de 0 a longitud(expresión) - 2 hacer:
        - si esOperador(expresión[i]) y (esOperador(expresión[i + 1]) o expresión[i + 1] == ')') entonces:
            - retornar falso
    - si esOperador(expresión[0]) o esOperador(expresión[longitud(expresión) - 1]) entonces:
        - retornar falso
    - retornar verdadero

# Función paréntesisBalanceados(expresión)
    - pila = nuevaPila()
    - para cada carácter en expresión hacer:
        - si carácter == '(' entonces:
            - pila.apilar(carácter)
        - si carácter == ')' entonces:
            - si pila.estaVacia() entonces:
                - retornar falso
            - pila.desapilar()
    - retornar pila.estaVacia()

# Función comprobarSintaxis(expresión)
    - retornar comprobarCaracteresVálidos(expresión) y comprobarOperadores(expresión) y paréntesisBalanceados(expresión)

# Función obtenerExpresiónUsuario()
    - imprimir("Introduce una expresión matemática:")
    - retornar leerEntradaUsuario()

# Función validarExpresión(expresión)
    - es_valida = comprobarSintaxis(expresión)
    - si es_valida entonces:
        - imprimir("La expresión es válida")
    - sino:
        - imprimir("La expresión no es válida")

# Función principal()
    - expresión = obtenerExpresiónUsuario()
    - validarExpresión(expresión)

# Llamar a la Función principal

FIN
