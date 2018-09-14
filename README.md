# BondiCard app
Esta app está desarrollada con la plataforma [App Inventor 2](http://ai2.appinventor.mit.edu) con el fin de poder gestionar fácilmente el saldo de la tarjeta RedBus, sobre todo con la cantidad de pasajes de abono.
 ## Primer Uso
 Después de la instalación hay que setear el estado inicial, dale valores a algunos campos y demás.

### Este es el "Home" de la aplicación

 ![Home](/img/01.png)

 Home de la app.
 De arriba hacia abajo. Primero se muestra la fecha actual, debajo el saldo actual. Debajo del saldo hay 3 campos, el que muestra la fecha del último viaje , el de los viajes restantes (considerando los que se cobran con descuento de abono y los que se cobran completos) y un botón de reporte que muestra más en detalle el estado actual de la tarjeta. Los siguientes dos botones son para 'cargar saldo' (una vez que se haya cargado realmente el saldo como lo hagamos usualmente) y para 'pagar boleto' (una vez hayamos pasado la tarjeta), respectivamente.

### Carga de saldo
 ![Cargar saldo](/img/02.png)

 Desde el ícono de dinero se carga el saldo (pantalla anterior). En el primer uso se le puede poner directamente el saldo actual, pero después se usa para "cargar" saldo (es decir, después de cargar realmente el saldo, ingresamos ese monto desde esta opción para que se sume al saldo anterior).

 ### Configuración del abono
 ![Configuración](/img/03.png)

Acá hay que configurar lo siguiente:
+ El precio del boleto general actual
+ Si hay abono, marcar la casilla y seleccionar el porcentaje de descuento
+ Definir el límite máximo de pasajes (actualmente, para el abono universitario, es de 46 viajes).
+ Definir la cantidad de viajes previstos por día para la "semana normal" que tengamos.
 Una vez hechas las configuraciones hay que guardar (boton verde) y ya podemos salir de esta ventana.
 Para ajustar saldos hay que entrar a la opción de "Config. de estado"

### Configuración del estado del abono
 ![Configuración de estado](/img/04.png)

En esta sección se pueden ajustar los saldos y fecha/hora del último viaje. Estas opciones sólo deberían modificarse si hay algún saldo que por algún motivo esté mal calculado. Por ejemplo, que el saldo que muestra la app no sea el real. También, al principio de cada mes hay que poner manualmente la cantidad de viajes restantes (estos son los viajes restantes con el abono), el valor a colocar debe ser el mismo de la ventana anterior, es decir, el máximo permitido con descuento de abono (46 para el abono universitario)
