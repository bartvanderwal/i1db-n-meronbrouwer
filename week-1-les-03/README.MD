# Week 1 - les 3

## Opgave Damsteen deel 1

### Opgave A
Maak de klasse waarmee je damstenen kunt maken. Een damsteen is rond en moet een x- en y-punt hebben, een kleur en een diameter. Maak een constructor waarmee de gebruiker van de klasse alle eigenschappen van een damsteen kan meegeven.

### Opgave B
Test de klasse damsteen door in het hoofdprogramma twee damstenen te maken: een witte en een zwarte en deze op het tekenvenster van Processing te tekenen.

## Opgave Student null
Tik iets. En nog iets.g

```java
void setup() {
  Student s = new Student("kareltje", 12);
  println(s.naam);
}

class Student {
  String naam;
  int nummer;
  
  Student(String naam, int nummer) {
    naam = naam;
    nummer = nummer;
  }
}
```