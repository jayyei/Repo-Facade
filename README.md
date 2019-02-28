# Readme
## Source Control for your database

Patron de diseño Facade 

## Descripción del programa
Se tienen dos subclases llamadas flights y hotel, con los metodos implementados de una interfaz IsubClasses, entonces en otra clase llamada Facade se crean objetos de dichas subclases y existe un metodo llamado "result" en la clase Facade que utiliza los metodos de los objetos hechos por las subclases (Puede utiliar mas metodos o atributos). Al momento de crear un objeto de la clase Facade en la clase main indirectamente se utilizan los metodos de las subclases (o algunos de ellos dependiendo de lo que se quiera ocupar en Facade). Esto se hace para que el codigo funcione de manera simplificada en la clase principal y cabe señalar que existe un acoplamiento necesario en el metodo "result" de la clase Facade

## uso
Cuando quieres llamar varios metodos de distintas clases es recomendable crear una clase (Facade) que crea los objetos de las subclases, utilizar los metodos de dichas subclases y al momento de crear un objeto de esta clase Facade se integran los metodos de las subclases

