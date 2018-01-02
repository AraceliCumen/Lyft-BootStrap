# Proyecto: Lyft

## Objetivos

Desarrolla una web-app que replique el sitio de Lyft, en este reto deberás cumplir los pasos necesarios para que tu usuario pueda registrarse.

## Flujo de la Aplicación

- Vista splash con duración de 2 a 5 segundos que redirecciona a tu vista de inicio. La vista de inicio cuenta con dos botones, en esta ocasión seguiremos el flujo de SING UP.

***
![Vista Splash](assets/img/splash.png "Vista Splash")
***

- En la siguiente vista tenemos un formulario donde nuestro usuario puede escoger el país y debe ingresar su número de teléfono. El botón de NEXT debe estar deshabilitado hasta que se ingrese un número de 10 dígitos.

***
![Vista principal](assets/img/ingreso-numero.png "Vista principal")
***

- Una vez ingresado el número de teléfono se habilita el botón y al dar click debe enviar una alerta con un código generado aleatoriamente (LAB-000) y redireccionar a la siguiente vista. 

***
![Vista principal](assets/img/generacion-codigo.png "Vista principal")
***

- En esta vista se debe ingresar el código dado anteriormente y una vez hecho esto se habilita el botón que redirecciona a nuestro usuario a la vista donde ingresa sus datos. (Puede tener la opción de enviar otro código.)  

***
![Vista principal](assets/imgverificacion-numero.png "Vista principal")
***

- Para ingresar sus datos necesitamos un formulario que le pida su nombre, apellido y correo electrónico. Deberá también tener un checkbox para que se acepten los términos y condiciones del servicio.   

***
![Vista principal](assets/ingreso-datos.png "Vista principal")
***

- Ya que se ha realizado lo anterior, sólo se deberá mostrar una vista al usuario que le indique que ha concluido con el registro exitosamente.    

***
![Vista principal](assets/final.png "Vista principal")
***

- NOTA: Todas nuestras vistas deben de contar con una manera de regresar a la vista anterior

## Desarrollado con

`HTML5` `Jquery` `CSS3` `Bootstrap`

## Desarrollado por

Araceli Cueva