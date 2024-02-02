# juego-adivina-numero-cobol
El juego consiste en adivinar un numero de 4 cifras que previamente le pedimos a una rutina que nos devuelva,sin decirnos el numero, y que no tiene digitos repetidos entre sus cifras.
El juego nos pedira ingresar un numero hasta que demos con el numero o hasta cuando decida el usuario no seguir con el juego, por cada vez que ingresemos un numero nos dira si acertamos el numero y la posicion del mismo, si solo acertamos el numero o si no acertamos ni una ni la otra.
Por ejemplo, si el numero que nos genera la rutina es 6192, y nosotros ingresamos 7295, el juego retornará lo siguiente:
acertaste 1 numeros en la posicion correcta (no dice cual, pero en nuestro caso seria el 9)
Acertaste 1 numeros, pero no en la poscion correcta (en este caso seria el 2)
No acertaste 2 numeros (en este caso serian los numeros (7 y 5, ya que los otrso digitos del numero a adivinar son 6 y 1)
Con esas pistas debemos seguir intentando adivinar el numero.
Ahora si para el mismo numero decidieramos continuar e ingresamos el numero 7283, el programa retornará:
acertaste 0 numeros en la posicion correcta
Acertaste 1 numeros, pero no en la poscion correcta
No acertaste 3 numeros
