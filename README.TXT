------------------------------------------------------------------------
This Descripción del Proyecto:
Desarrolla un sistema de gestión para un cine que permita realizar operaciones básicas relacionadas con la programación de películas y la gestión de asientos en varias salas. El sistema debería permitir a los usuarios gestionar y visualizar la información de las películas en cartelera, así como las reservas de asientos en diferentes salas.

Requisitos del Proyecto:
Clases Principales:

Movie: Representa una película. Debe contener atributos como título, director, duración, y género.
Theater: Representa una sala de cine. Debe contener atributos como el nombre de la sala, y un arreglo bidimensional de booleanos que represente los asientos disponibles (true para disponible y false para ocupado).
MovieTheaterManager: Es la clase principal que maneja la lista de películas y salas. Debe permitir agregar y eliminar películas, reservar y cancelar asientos, y mostrar información sobre la programación de películas y la disponibilidad de asientos.
Operaciones Básicas:

Agregar Películas: Permite agregar nuevas películas a la cartelera.
Eliminar Películas: Permite eliminar películas de la cartelera.
Reservar Asientos: Permite a los usuarios reservar asientos en una sala para una película específica. Usa un arreglo bidimensional para gestionar los asientos.
Cancelar Reservas: Permite cancelar una reserva de asiento.
Mostrar Cartelera: Muestra todas las películas actualmente en cartelera.
Mostrar Disponibilidad de Asientos: Muestra la disponibilidad de asientos en una sala específica.
Uso de try-catch:

Implementa bloques try-catch para manejar errores comunes, como intentar reservar un asiento en una sala que no existe, o seleccionar un asiento que ya está reservado.
Uso de switch-case:

Utiliza una estructura switch-case para implementar un menú de opciones en la clase MovieTheaterManager. El menú debe permitir al usuario seleccionar acciones como agregar una película, reservar asientos, mostrar la cartelera, etc.
Arreglos de Dos Dimensiones:

Utiliza un arreglo bidimensional para gestionar la disponibilidad de asientos en cada sala de cine. Cada elemento del arreglo representa un asiento en la sala, y puedes usar true o false para indicar si un asiento está disponible o reservado.
Ejemplo de Flujo de Trabajo:
Inicia el sistema y muestra el menú principal.
El usuario selecciona una opción del menú (por ejemplo, agregar una película).
El sistema solicita los detalles necesarios (título de la película, director, duración, etc.) y realiza la acción seleccionada.
El usuario puede reservar asientos para una película específica, donde el sistema debe mostrar la disponibilidad de asientos y permitir seleccionar asientos específicos.
El usuario puede cancelar una reserva de asiento y el sistema actualiza la disponibilidad en consecuencia.is the project README file. Here, you should describe your project.
Tell the reader (someone who does not know anything about this project)
all they need to know. The comments should usually include at least:
------------------------------------------------------------------------

PROJECT TITLE:
PURPOSE OF PROJECT:
VERSION or DATE:
HOW TO START THIS PROJECT:
AUTHORS:
USER INSTRUCTIONS:
