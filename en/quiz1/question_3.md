--- question ---
---
legend: Question 3 of 3
---

This function outputs two random numbers:

--- code ---
---
language: python
---

def two_dice():
  print('First number:', randint(1, 6))
  print('Second number:', randint(1, 6))

--- /code ---

Which code will call the function to run it?

![The Trinket editor with output area showing two randomly generated numbers.](images/quiz3.png)

--- choices ---

- ( ) 

--- code ---
---
language: python
---

def two_dice():
  print('First number:', randint(1, 6))
  print('Second number:', randint(1, 6))

--- /code ---

 --- feedback ---

 No, this is the code to define the function, but it does not run the function. You'll need to use different code to call it.

 --- /feedback ---

- ( ) 
--- code ---
---
language: python
---

two_dice

--- /code ---

 --- feedback ---

Close! `two_dice` is the name of the function, but to call it you need more than just the name.

 --- /feedback ---

- () 

--- code ---
---
language: python
---

two_dice[]

--- /code ---

 --- feedback ---

 Not quite, think about they type of brackets you used to call the functions in your project. 

 --- /feedback ---

- (x) 

--- code ---
---
language: python
---

two_dice()

--- /code ---

 --- feedback ---

 That's correct, using the function name followed by `(` `)` brackets will call the function.

 --- /feedback ---

--- /choices ---

--- /question ---
