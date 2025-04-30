# EJERCICIO_CLASE_6
Ejercicio propuesto al final de la clase 6

```
class Person:
    Species = "Human"
    
    def __init__(self, age: int = 20, name: str = "Jhon Doe"):
        self.age = age
        self.name = name
        
    def greet(self):
        print(self.name ,"is greeting you!")

    def is_older_than(self, person: "Person")-> bool:
        return self.age > person.age       
    
Daniel = Person( age=18, name= "Daniel" )
Jorge = Person( 12 , "Jorge" )

Daniel.greet()
print(Daniel.is_older_than(Jorge))
```
El return de estas 2 funciones es:
```
Daniel is greeting you!
True
```
