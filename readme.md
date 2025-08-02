## Funciones en C++
### Ejemplos para usar If - Else en C++
### Definición

Los condicionales if-else (Si-Sino), son una estructura de control, que nos permiten determinar que acciones tomar dada o no cierta condición, por ejemplo determinar si la contraseña ingresada por el usuario es válida o no y de acuerdo a esto darle acceso al sistema o mostrar un mensaje de error.

1. string password = "";
1. cout << "Ingrese la contrasenia: ";
1. cin >> password;
1. if(password == "myClave")
1. {
1.    cout << "Contrasenia correcta. Bienvenido";
1. }
1. else
1. {
1.   cout << "Contrasenia incorrecta.";

-Ejemplos para usar Multiple Switch en C++
-Definición

Los condicionales Switch, son una estructura de control condicional, que permite definir múltiples casos que puede llegar a cumplir una variable cualquiera, y qué acción tomar en cualquiera de estas situaciones, incluso es posible determinar qué acción llevar a cabo en caso de no cumplir ninguna de las condiciones dadas.

 1.   cout << "Ingrese la Opción a ejecutar: ";
 1.   int opcion = 0;
 1.  cin >> opcion;
1.
1.  switch(opcion)
1.  {
1. case 1: cout << "Usted ha seleccionado la opción 1";
1.    break;
1.    case 2: cout << "Usted ha seleccionado la opción 2";
1.    break;
1.   case 3: cout << "Usted ha seleccionado la opción 3";
1.   break;
1.   default: cout << "Usted ha ingresado una opción incorrecta";
1. }
1. // system("PAUSE"); //Solo ponla si no te da error





