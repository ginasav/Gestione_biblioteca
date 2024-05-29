<h2> La mia biblioteca </h1>
In quest'altro file .py vado a creare la mia biblioteca e utilizzare i metodi creati per la classe Biblioteca

```ruby

from typing import Any
from libro import Libro
from biblioteca import Biblioteca

biblioteca_casa = Biblioteca()

libro1= Libro(titolo= "Gomorra", 
              autore= "Roberto Saviano",
              anno_pubblicazione= 2006,
              disponibile= True)

libro2= Libro(titolo= "L'arte della gioia",
              autore= "Goliarda Sapienza",
              anno_pubblicazione= 1994,
              disponibile= True)

libro3= Libro(titolo= "L'amica geniale",
              autore= "Elena Ferrante",
              anno_pubblicazione= 2011,
              disponibile= True)

biblioteca_casa.aggiungiLibro(libro1)
biblioteca_casa.aggiungiLibro(libro2)
biblioteca_casa.aggiungiLibro(libro3)

# print()
# print("Sta caricando...")
# biblioteca_casa.mostraLibri()

# print()
# print("Sta ricercando...")
# biblioteca_casa.cercaLibro("L'arte della gioia")

print()
print("***Prestito libri***")
biblioteca_casa.prestitoLibro("Gomorra")

```
