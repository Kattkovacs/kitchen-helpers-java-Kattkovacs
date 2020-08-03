# Kitchen helpers showcase

## Story

Gordon Ramsey figured out that he wanna digitalize his kitchen.
So he's trusted you the task to model hell’s kitchen.
Restaurants have cooks, one chef, and kitchen helpers.

## What are you going to learn?

- How to design a library
- How to use UMLs to communicate your design
- Using `Optional<E>` to specify alternate values to return or alternate code to run

## Tasks

1. Store every employee's name, birth date, and salary
    - Each of these attributes can be retrieved via getters.
    - Whenever an employee is printed at least its name is printed.
    - Every employee can print her own tax which is the 99% of the salary
    - There are three kind of employees: *chefs*, *cooks* and *kitchen helpers*.

2. *Chefs* and *cooks* can cook.
    - Chefs are either shouting or requesting ingredients.
    - Cooks are always shouting that they are cooking. (So the chef will leave them be)

3. Kitchen helpers have ingredients.
    - the kind of ingredients are
- meat
- potato
- carrot
    - Helpers at all times have a random number (0-3) of each ingredient.

4. When the chef requests an ingredient the kitchen helpers have to provide it.
    - The first kitchen helper who has that ingredient should give the chef one piece.
    - If none of them have any they should all yell "We're all out".

5. The restaurant provides good quality knife sets for cooks and chefs
    - The knives are received some time after the employee have been hired.
    - Cooks and chefs can't cook without a knife.

6. Role of the chef
    - A kitchen has only one chef.
    - A kitchen can't produce meals without a chef.

7. As an extra task write unit tests for the different classes
    - Cook class has covered with unit tests
    - Chef class has covered with unit tests
    - KitchenHelper class has covered with unit tests
    - Kitchen class has covered with unit tests

## General requirements

- There is a class UML representing the assignment. The UML is implemented. the code compiles.
The UML doesn't have to contain every last detail. Try to collect the important parts.
The implementation can diverge in slight ways from the original plan.

## Hints

- This is a **showcase project**, a regular project with a step-by-step guide.
In order to learn the most, try and implement it on your own first, and 
check the solution only when you feel your version is ready. However,
when you feel completely stuck, feel free to check the guide for hints.
- Take lots of notes. Even when something seems trivial it can turn
  out to be more complex than it first seems
- Use diagrams (sequence diagrams, flow charts) to plan out scenarios
- Handle exceptional cases with exceptions

## Starting your project

To start your project click [this link](https://journey.code.cool/v2/project/solo/blueprint/kitchen-helpers/java).

## Background materials

- [Creating objects](https://learn.code.cool/full-stack/#/../pages/java/creating-objects)
- [Methods](https://learn.code.cool/full-stack/#/../pages/java/methods)
- [OOP basics](https://learn.code.cool/full-stack/#/../pages/java/basics-of-object-oriented-programming)
- [OOP basics 2](https://learn.code.cool/full-stack/#/../pages/java/basics-of-object-oriented-programming-with-java-part-2)
- [Collections](https://learn.code.cool/full-stack/#/../pages/java/collections)
- [Abstraction, abstract classes and interfaces](https://learn.code.cool/full-stack/#/../pages/java/abstraction)
- [UML class diagrams](https://learn.code.cool/full-stack/#/../pages/general/uml-unified-modeling-language.md)
- [Other kind of UMLS](https://learn.code.cool/full-stack/#/../pages/general/uml-beyond-class-diagram.md)
- [Functional elements in Java](https://learn.code.cool/full-stack/#/../pages/java/functional-elements-in-java.md)
- [Exception handling](https://learn.code.cool/full-stack/#/../pages/java/exception-handling.md)

!> [Kitchen Helper step-by-step guide](https://learn.code.cool/full-stack/#/../pages/java/kitchen-helpers-step-by-step)
