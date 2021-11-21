# Miobox Inicializador

El modulo establece variables globales como preparacion para el registro de variables.

## Entrada

Se reciben los datos desde nodo Modbus, S7, o AB.

## Salida

Se obtiene los datos con ajuste de horas y se estampa el tiempo.

`msg.timeStamp` -> Almacena la estampa de tiempo con ajuste de zona horaria.

## Configuraciones

Se puede ajustar la confuracion segun zona horaria. Acepta zonas horarias  negativas(-)