
# Proyecto-Final-Ciencias-3

## Participantes: 

* Marcela del Pilar Porras Quevedo - 20191020131
* Juan Sebastian Gonzalez Forero - 20181020029
* Luis Felipe Corredor Espinoza- 20171020056
### Descripción 📝 :

Generador de código a partir de entidades establecidas, para obtener una aplicación utilizando html y java Script.

## Descripción detallada

Para generar nuestra aplicacion de peliculas se necesitó una entidad pelicula que contiene los atributos  titulo, director y FechaLanzamiento, todos de tipo String, 4 templates que son: 
* **estilo.template:** genera los estilos en un CSS.
* **html.template:** genera una estructura de html a partir de la entidad pelicula que se tiene en pelicula.ent, carga y muestra los datos.
* **interfaz.template:** genera la structura para un js en donde se pueden agregar los datos y obtener la lista de datos a partir de la entidad pelicula.
* **logica.template :** guarda los datos a partir de la entidad y realiza el manejo de errores así como la eliminación de datos, además, imprime la tabla de datos.

Ahora para correr el código se debe utilizar el comando:

```
python entity_codegen.py 
```

el cual generará los archivos
* estiloPelicula.css
* indexPelicula.html
* interfazPelicula.js
* logicaPelicula.js

los cuales nos permitiran hacer uso de la aplicación.
