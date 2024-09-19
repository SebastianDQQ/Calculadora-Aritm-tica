
---

# Calculadora Aritmética

Este proyecto implementa una calculadora interactiva de expresiones aritméticas en Java que acepta expresiones en notación infija. El programa convierte la expresión a notación postfija y evalúa el resultado, soportando operaciones aritméticas básicas como suma, resta, multiplicación, división y exponenciación, así como agrupaciones mediante paréntesis.

## Implementaciones

1. **Evaluación de expresiones postfijas**:  
   Se agregó el método `ComprobarPostfix` para evaluar la expresión en notación postfija. Este método utiliza una pila para procesar los operandos y operadores, calculando el resultado final de la expresión introducida por el usuario.

2. **Manejo de operadoración**:  
   El programa soporta correctamente las operaciones de suma, resta, multiplicación, división y exponenciación. Los operadores son evaluados en el orden correcto de precedencia: primero exponenciación, seguido de multiplicación y división, y finalmente suma y resta.

3. **Conversión de notación infija a postfija**:  
   El código implementó para procesar adecuadamente las expresiones en notación infija, manejando correctamente los paréntesis y operadores. La conversión a postfija se realiza utilizando un algoritmo de pila, y la expresión postfija es evaluada posteriormente.
