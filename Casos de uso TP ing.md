**Caso de uso:** Cámara de velocidad

Actores: cámara

Precondiciones: \-

Camino básico:  
1\. La cámara envía al sistema fecha y hora, id de la cámara, patente y velocidad.  
2\. El sistema registra y evalúa los datos. 

Camino alternativo:  
1.a: La cámara registra que el auto va a más de 70km/h y envía los datos al sistema.  
1.a.1: El sistema envía un correo con los datos que envió la cámara a la cuenta "avisos@ciudad"  
1.b: La cámara registra que el auto va a más de 100km/h y envía los datos al sistema.

1.b.1: El sistema envía un correo con los datos que envió la cámara a la cuenta "avisos@ciudad" y envía, 3 veces, los datos recibidos por la cámara a una impresora para que sean impresos

Escenario de éxito:   
Se registraron los datos correctamente.  
Se enviaron los datos a la API.  
Se envió correctamente el correo electrónico.  
Se envió correctamente 3 veces los datos a la impresora.

Escenario de fracaso:  \-  
