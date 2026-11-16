# Graphical-interface exercises (Java Swing)

Two small Java Swing programs from the last semester of the Computer Technician course at CEAP. They were exercises in building windows with `JFrame`, `JPanel`, labels, text fields, buttons and images.

## Programs

### `Atividade_escola_intgrafica` — grade calculator

You enter a student's name, number, class and three grades. The program calculates the average and shows the result with a matching image:

| Average        | Result          |
| -------------- | --------------- |
| 6.00 or higher | Passed          |
| 4.00 to 5.99   | Make-up exam    |
| below 4.00     | Failed          |

### `Atividade_intgrafica` — interface basics

A window with HTML, CSS and JavaScript logos, plus buttons that show a message and close the window.

## Run

Requires a JDK (8 or newer). From the repository root:

```bash
javac -encoding UTF-8 -d out *.java
java -cp out Atividade_escola_intgrafica
java -cp out Atividade_intgrafica
```

Run it from the repository root, because the images load from the relative folders next to the code.

---

Made by [Heleno Matos](https://portfolio.helenomatos.com) during the Computer Technician course at CEAP (2019–2021).
