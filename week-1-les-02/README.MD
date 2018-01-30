# Week 1 - Les 2

### Onderdeel A

```java
int testGetal = 5;

void setup() {
  doeKeerTwee(testGetal);  
  println(testGetal);
}

void doeKeerTwee(int getal) {
  getal = 2 * getal;
}
```

### Onderdeel B

```java
int[] testGetallen = {5, 5};

void setup() {
  doeKeerTwee(testGetallen);
  
  println(testGetallen);
}

void doeKeerTwee(int[] getallen) {
  for (int i = 0; i < getallen.length; i++) {
    getallen[i] = 2 * getallen[i];
  }
}
```
