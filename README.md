# APP-desktop-para-bibliotecas
Aplicación de escritorio creada para servir en la gestión de bibliotecas, programada con SQL y diseño de la interfaz con Microsoft Access. 

LA APP ES UN EJECUTABLE LLAMADO "APP.accdb" SOLO SE PUEDE EJECUTAR CON MICROSOFT ACCESS (version 2016+ si es posible) 

En caso de ejecutarlo con una versión anterior a la 2016 es posible que la interfaz no funcione o el diseño se rompa. 

Para poner en funcionamiento la base de datos se recomienda agarrar un libro y arrancar a cargar datos en el siguiente orden: 
1- Autor
2- Temática 
3- Editorial
4- Libro

Para generar un prestamo se recomienda primero asegurarse que el libro a prestar ya este cargado (de caso contrario cargarlo), segundo cargar el usuario a la base de datos y tercero realizar el prestamo.

***PARA PODER ACCEDER A LAS TABLAS Y FORMULARIOS SIN INTERFAZ GRAFICA: APRETE LA TECLA "SHIFT" Y MANTENGA APRETADA MIENTRAS ABRE LA APLICACIÓN. 

    Sobre la App: 
  
    -La app es una base de datos correlacional provista de una interfaz grafica para poder ser usada por cualquier usuario sin importar su conocimiento en el campo. 
  
    -En esta App especifica (pues hice varias versiones para diferentes bibliotecas) nos encontramos con seis (6) tablas de datos relacionadas entre sí. 
  
  
    -Tiene en existencia un total de ocho (8) formularios
  
      APP: este formulario es el unico que no posee interfaz grafica, pues tiene un codigo que vuelve a la app un ejecutable, al hacer doble click en la app se lanza           este codigo que a su vez lanza la interfaz grafica principal. 
    
      Principal: este formulario contiene la interfaz grafica inicial del programa, con seis botones para abrir los otros 6 formularios, más uno de cerrar la app.
    
      Autor, Tematica, Libros, Préstamos, Editorial, Usuarios: estos formularios cargan datos directamente a las tablas, algunos de ellos poseen selects con diferentes         options que toman de otras tablas. Otros de ellos no pueden ser usados a menos que el valor ingresado exista en otra tabla, algunos poseen mascara de entradas           (como usuario con DNI) para que se ingrese un valor especifico (en este caso 8 numeros enteros). 
      
     -También posee dos consultas simples, que fueron usadas de uso interno para controlar ciertos datos; no las borre para mostrar la posibilidad de realizar las mimas.
    
    
