# calculadoraGIT

Ejercicio de clase para aprender Git con un proyecto pequeño en Java: una calculadora con suma y resta. Lo hice en febrero de 2022, durante el primer curso del ciclo de DAM.

## Qué hay

- `Calculadora.java` tiene los métodos `sumar` y `restar` para números enteros.
- `Principal.java` crea una calculadora e imprime `5 + 3` y `5 - 3`.

## Cómo ejecutarlo

Hace falta un JDK instalado (el proyecto de Eclipse está configurado para Java 15).

```
javac -d bin src/calculadoraGIT/*.java
java -cp bin calculadoraGIT.Principal
```

Debería imprimir 8 y 2.

También se puede abrir directamente como proyecto en Eclipse.

---

# calculadoraGIT (English)

A small class exercise to learn Git, written in Java: a calculator with addition and subtraction. I made it in February 2022, during the first year of my DAM vocational course.

## What's inside

- `Calculadora.java` has the `sumar` (add) and `restar` (subtract) methods for integers.
- `Principal.java` creates a calculator and prints `5 + 3` and `5 - 3`.

## Running it

You need a JDK (the Eclipse project targets Java 15).

```
javac -d bin src/calculadoraGIT/*.java
java -cp bin calculadoraGIT.Principal
```

It should print 8 and 2.

You can also open it directly as an Eclipse project.
