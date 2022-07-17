# Azure Functions 
**Objetivo:** Creación de un recurso de Azure Functions.    

![](/imagenes/Azure-Function.jpg)

**Requisitos**
- Cuenta de Azure con una suscripción activa
- Equipo de cómputo con sistema operativo: Windows, Linux o MacOs.


**Pasos**  
Se inicia sesión en Portal.Azure.com.  
En la barra de búsqueda escribimos “Azure functions” y lo seleccionamos.  
Damos clic en el apartado crear.

En la pestaña datos básicos, llenamos lo siguiente:  
**En Detalles del proyecto**  
Suscripción: La suscripción que queramos utilizar.  
Grupo de recursos: Podemos crear uno o seleccionar uno ya existente.
![Imagen 1](/imagenes/Imagen1.png)

En Detalles de Instancia  
Nombre de la aplicación: Ponemos el que queramos.  
Publicar: Seleccionamos código.  
Pila del entorno: Ponemos el que queramos.  
Versión: Dejamos la que está por defecto.  
Región: Podemos escoger cualquiera, pero si no queremos que haya mucha latencia escogemos uno cercano a donde vivimos.

Todo lo demás lo dejamos como esta, por último, damos clic en el botón de revisar y crear, y luego en crear.
![](/imagenes/Imagen2.png)

Cuando se termine de crear nuestro recurso, daremos clic en el botón de ir al recurso. 
En el menú de la parte de la izquierda le damos clic en la opción de funciones.
Daremos clic en el apartado de Crear, en la ventana que se abrió a la derecha seleccionaremos un trigger, es decir un disparador que es una acción que se realizara ante una determinada acción. Seleccionaremos el HTTP Trigger y le damos en crear.
![](/imagenes/Imagen3.png)

En el menú de la parte de la izquierda le damos clic en la opción de código y prueba.  
Ahora en el menú de la parte superior seleccionaremos la opción de probar y ejecutar.  
En la ventana que se abrió a la derecha, en la líneas de código donde esta name, cambiaremos Azure por nuestro nombre y le daremos en ejecutar.
![](/imagenes/Imagen4.png)

Se nos mostrara un mensaje, saludándonos y diciendo que la función se ejecutó exitosamente.
![](/imagenes/Imagen5.png)

