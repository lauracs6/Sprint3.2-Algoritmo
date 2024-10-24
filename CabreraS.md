//declaración de las variables:

numRegristro, hermanoCentro, viveZona, trabajoZona, discapacidad, famNumerosa, famCentro, puntosTotal:= entero;


//petición de datos por teclado:

escribirPantalla "Tu número de registro: ";
leerPantalla;

escribirPantalla "¿Tiene un/a hermano/a en el centro? (0:no / 1:sí): ";
leerPantalla;

escribirPantalla "¿Vive en la zona del centro? (0:no / 1:sí): ";
leerPantalla;

escribirPantalla "¿Trabaja el padre, la madre o el tutor en la zona del centro? (0:no / 1:sí): ";
leerPantalla;

escribirPantalla "¿Tiene alguna discapacidad? (0:no / 1:sí): ";
leerPantalla;

escribirPantalla "¿Forma parte de familia numerosa o monoparental? (0:no / 1:sí): ";
leerPantalla;

escribirPantalla "¿El padre, la madre o un/a hermano/a asistió al centro? (0:no / 1:sí): ";
leerPantalla;


//Conversión de puntos:

si hermanoCentro == 1 entonces
hermanoCentro + 40;
fsi 

si viveZona == 1 entonces
viveZona + 30;
fsi

si trabajoZona == 1 entonces
trabajoZona + 20;
fsi

si discapacidad == 1 entonces
discapacidad + 10;
fsi

si famNumerosa == 1 entonces
famNumerosa + 15;
fsi

si famCentro == 1 entonces
famCentro + 5;
fsi


//Cálculo de puntuación total:

puntosTotal := hermanoCentro + viveZona + trabajoZona + discapacidad + famNumerosa + famCentro;








