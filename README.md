# Felipe's Taqueria 🌮

A simple Python program that simulates taking orders at a Mexican restaurant and keeps track of the total cost.

## About the Project

The program contains a menu of food items and their prices. It continuously asks the user to enter an item and updates the total price after each valid order.

The program is **case-insensitive**, so uppercase and lowercase letters do not affect the result. Invalid items are ignored.

The user can finish the order by sending an `EOF` signal with `Ctrl + D`.

## Menu

* Baja Taco — $4.25
* Burrito — $7.50
* Bowl — $8.50
* Nachos — $11.00
* Quesadilla — $8.50
* Super Burrito — $8.50
* Super Quesadilla — $9.50
* Taco — $3.00
* Tortilla Salad — $8.00

## How It Works

The program asks the user to enter an item:

```text
Item: Taco
Total: $3.00
```

If another valid item is entered, its price is added to the total:

```text
Item: Taco
Total: $3.00
Item: Taco
Total: $6.00
```

If an invalid item is entered, it is ignored and the program asks for another item.

The total is always displayed with two decimal places and a `$` sign.

## What I Practiced

* Dictionaries
* Dictionary keys and values
* `.get()`
* `while` loops
* `try / except`
* Handling `EOFError`
* `input()`
* Case-insensitive input
* Working with floating-point numbers
* Formatting numbers with two decimal places
* Accumulating values with variables

## Technologies

* Python

## Course

This project was completed as part of **CS50's Introduction to Programming with Python** by Harvard University.
