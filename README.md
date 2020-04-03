# Acción javascript "Hello world"

Esta acción muestra "hello world" o "hello X", donde X es el nombre suministrado a la acción.  

## Entradas
### `who-to-greet`

**required** El nombre de la persona a saludar. Por defecto "world"

## Salidas
### `time`

El momento en el que se produce el saludo

## Ejemplo
uses: actions/hello-world-javascript-action@v1
with:
  who-to-greet: 'Sergio'