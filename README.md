# CALCULADORA BÁSICA CON MENU

Una calculadora básica se puede realizar con condiciones.  Se desea realizar alguna de las operaciones básicas con dos números `x,y`. Además se desea calcular la potencia y el logaritmo. Se deben de considerar los casos donde `y=0` donde la división `x/ỳ` NO se puede realizar y cuando `x<=0` donde NO se puede calcualar el `long(x)`. Se desea generar un menú para que el usuario puede seleccionar la operacion a realizar. Una manera de la hacerlo es la siguiente: 

1. Se reciven los dos números `x,y` para realizar la operación. 
2. Se recibe la operación a realizar mediante la variable `opcion` la que selecciona en el menú qué operación ejecuta el algoritmo.
3. Se inicaliza la variable lógica `bandera = False`. Si la división o el logaritmo no se puede calcular, se hace `bandera = True`.
4. Mediante condiciones se realiza la operacion deseada.
    * En el caso de la división, si `y=0`, NO se puede realizar la división, se muestra un mendaje y se hace `bandera = True`.
    * En el caso del logaritmo, si `x<=o`, NO se puede calcular el logaritmo, se muestra un mensaje y se hace `bandera = True`.
5. Se muestra el resultado en el caso de que `bandera = False`


*Tomado de: Python con aplicaciones  a las matemáticas, ingenería y finansas. Cervantes O, Baez.D*