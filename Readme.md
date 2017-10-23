Outside-In TDD con tests de aceptación
========================================
 
### Objetivo

Aprender y practicar la doble vuelta de TDD
Testear la aplicación desde fuera, identificando los efectos colaterales
 
### Descripción del problema - Bank kata
 
Crear una aplicación bancaria simple con las siguientes funcionalidades:

     - Ingresar dinero en una cuenta.
     - Retirar dinero de una cuenta.
     - Imprimir por consola el extracto, un resumen de las operaciones en orden cronológico:
 
## Criterios de aceptación

El resumen de operaciones debe tener el siguiente formato:

```
  FECHA       | CRÉDITO  | BALANCE
  10/04/2014  | 500.00   | 1400.00
  02/04/2014  | -100.00  | 900.00
  01/04/2014  | 1000.00  | 1000.00
```

## Punto de inicio y restricciones

Empezar con una clase con la siguiente estructura:

    public class Account {

        public void deposit(int amount);

        public void withdrawal(int amount);

        public void printStatement();

    }

No esta permitido añadir ningún otro método público a esta clase.

**NOTA:** Para mantener el ejercicio más simple usa _int_ para el importe y _String_ para las fechas.
Además, se puede ignorar el formato de salida del extracto (espacios entre pipes y las palabras, etc).


## Créditos

Esta es únicamente la versión java y con descripción en castellano de la kata original. La kata original está publicada en [sandromancuso github](https://github.com/sandromancuso/bank-kata-outsidein-screencast)

