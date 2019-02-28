# Facade
## Source Control for your database

Ejemplo de Facade

## Descripción
Se tienen dos subclases llamadas flights y hotel, con los metodos implementados de una interfaz IsubClasses, entonces en otra clase llamada Facade se crean objetos de dichas subclases y existe un metodo llamado "result" en la clase Facade que utiliza los metodos de los objetos hechos por las subclases (Puede utiliar mas metodos o atributos). Al momento de crear un objeto de la clase Facade en la clase main indirectamente se utilizan los metodos de las subclases  (o algunos de ellos dependiendo de lo que se quiera ocupar en Facade). Esto se hace para que el codigo funcione de manera simplificada en la clase principal y cabe señalar que existe un acoplamiento necesario en el metodo "result" de la clase Facade

