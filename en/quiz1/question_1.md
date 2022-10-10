## Quick quiz

Answer the three questions. There are hints to guide you to the correct answer.

When you have answered each question, click on **Check my answer**.

Have fun!

--- question ---
---
legend: Question 1 of 3
---

This code sets the `world` variable to contain the text '🌍🌎🌏' (the three different world emoji):

--- code ---
---
language: python
---

world = '🌍🌎🌏'

--- /code ---

Which code correctly uses the `world` variable and outputs Hello 🌍🌎🌏?

![The output area from the Trinket editor with Hello 🌍🌎🌏 showing.](images/quiz1.png)

--- choices ---

- ( ) 

--- code ---
---
language: python
---

output('Hello' world)

--- /code ---

 --- feedback ---

 Not quite, `output` is not the way to output messages to the screen.

 --- /feedback ---


- ( ) 

--- code ---
---
language: python
---

print('Hello' world)

--- /code ---

 --- feedback ---

 Not quite, in Python `print` outputs messages to the screen, but something is missing in this example.

 --- /feedback ---

- (x) 

--- code ---
---
language: python
---

print('Hello', world)

--- /code ---

 --- feedback ---

 That's correct, in Python `print` outputs messages to the screen. The text output is inside single quotes `'` , a comma separates the two items and provides a space, then the `world` variable is called, which stores the earth emoji 🌍🌎🌏, like in your project.

 --- /feedback ---

- ( )

--- code ---
---
language: python
---

print(Hello, world)

--- /code ---

 --- feedback ---

  Not quite, in Python `print` outputs messages to the screen, but something is missing in this example.

 --- /feedback ---

--- /choices ---

--- /question ---
