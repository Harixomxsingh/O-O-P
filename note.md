# Date: 3 / 11 / 2021

# Object Oriented programming 

## What is Object Oriented Programming? (oop)

- oop is programming paradigm (style of the code) based on teh concept of objects;
- We use Objects to model (describe) real world or abstract features;
- Objects may contain data (properties) and code (method), By using Objects, we pack data and teh corresponding behavior into one block;
- In OOP, objects are self-contained pieces/blocks of code;
- object are building blocks of applications, and interact with one another;
- interactions happen through a public interface(API): method that the code outside of the object can access and use to communicate with the object;

### why just oop exist

well this paradigm was developed with the goal of organizing code, so to make it more flexible and easier to maintain.

## CLASS AND INSTANCES (TRADITIONAL OOP)

in traditional oop we use something called **CLASSES**.
<br>

_you can think of a class as a blueprint, which can then be used to create new objects based on the rules described in the class._

<br>
so it's just like an architecture where the architect develops a blueprint to exactly plan and describe a house.

## THE 4 FUNDAMENTAL OOP PRINCIPLES

1. Abstraction
2. Encapsulation
3. Inheritance
4. Polymorphism

### PRINCIPLE1: ABSTRACTION

Abstraction: Ignoring or hiding details that don't matter, allowing us ot get an overview perspective of the thing we're implementing instead of messing with details that don't really matter to our implementation.

#### example

let's say that we're implementing a phone for a user to use. so with our abstraction like the phone's temperature and voltage, turning on the vibration motor or the speaker, and other low level details, but as a user interacting with a phone, do we really need all of this detail? well no.

<br>
in reality, when we interact with a real phone, all of these details have been abstracted away from us as the user.

### PRINCIPLE 2: ENCAPSULATION

Encapsulation: Keeping properties and methods **private** inside the class, so they are **not accessible from outside the class**. some methods can be **exposed** as a public interface(API)

### PRINCIPLE 3: INHERITANCE

Inheritance: Making all properties and methods of a certain class **available to a child class**, forming a hierarchical relationship between classes. this allows us to **reuse common logic** and to model real-world relationship

### PRINCIPLE 4: POLYMORPHISM

Polymorphism: A Child class can overwrite a method it inherited form a parent class [it's more complex that, but enough for our purposes].
