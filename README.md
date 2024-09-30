# ListView-Dinamico_-Romo-Campos-Luis-Angel


Lo primero que se hace es crear la aplicacion Y despues de este paso lo que haremos es modificar el activity_main.xml para tener lo basico que seria nuestros listviews de los 10 platillos que se nos requieren, en este caso puse un textview con un titulo que dice recetas del mundo, el boton de busqueda de platillos y como ya lo habia dicho el listview

![image](https://github.com/user-attachments/assets/c8b7f451-2340-4447-9a93-e4e662570eee)

en esta imagen se puede observar que utilice revursos extra para mejorar el diseño de la pagina principal.

Despues de todo esto pasamos a modificar el MainActivity.kt en el cual vamos a poner una variable privada val la cual va a contener los nombre de los 10 platillos, sus referencias en imagenes que obviamente deben de haber estado con anterioridad en la carpeta drawable con formatos Png, Jpg, o Jpge, sus paises de origen, ademas de que su descripcionde debe de estar aqui.

![image](https://github.com/user-attachments/assets/4f9c6d25-6476-4260-ab91-aeaf6240d258)


despues se crearon varios archivos kotlin, los cuales ayudarian a la eficiencia de la aplicacion como por ejemplo uno que se llamo comida el cual solo se encarga de tener un modelado de datos como el nombre de la comida, pais de referencia, sus imagenes y descripcion con asi mismo sus propios string("que no son mas que secuencias de caracteres"), asi mismo los otros archivos kt creados son HolaActivity y Adaptado, los nombres se los puse asi por irrelevancia, el Adaptado se encarga de llamar los datos que ya se encontraban con anterioridad en la variable privada val los cuales se encuentran referenciados con otro archivo xml llamado como activity_datos.xml el cual contiene los textview necesarios y las imagenes de los platillos junto con los botonoes de compartir

![image](https://github.com/user-attachments/assets/e3383325-bfa1-488a-aed6-ffb2041dc776)


![image](https://github.com/user-attachments/assets/3a43cb20-2cc1-453d-81bb-ef70325d8b27)


tambien para finalizar se creara otro xml al que le puse de nombre listavista.xml en el que tendra como se veran tanto las imagenes como asi mismo los textos y los mismos listview

![image](https://github.com/user-attachments/assets/85786c6e-7610-49ca-adad-e8000b2b849f)

![image](https://github.com/user-attachments/assets/65cb55e1-ff46-4274-8647-93807f1930cb)

![image](https://github.com/user-attachments/assets/64bb6e34-f728-448a-83a9-94519c9086f7)

![image](https://github.com/user-attachments/assets/669e8cbd-6ddf-4eeb-9d97-15d6aa12552d)

![image](https://github.com/user-attachments/assets/0f3f1d64-2573-4aa7-972a-ca8e5e253068)






