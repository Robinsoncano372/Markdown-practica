## Ejemplos para usar If - Else en C++
### Definicion

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

