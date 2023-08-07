# Assignments

<!-- TOC -->

- [Assignments](#assignments)
    - [Week2](#week2)
        - [Ungraded Assignment - UML Class Diagram](#ungraded-assignment---uml-class-diagram)
            - [Task Description](#task-description)
            - [Solution Files](#solution-files)
    - [Capstone Assignment 1.1 – UML Class Diagram](#capstone-assignment-11--uml-class-diagram)
        - [How to create your assignment](#how-to-create-your-assignment)
            - [Solution Files](#solution-files)
    - [week3](#week3)
        - [Ungraded Assignment – UML Sequence Diagram](#ungraded-assignment--uml-sequence-diagram)
            - [Task Description](#task-description)
            - [Solution Files](#solution-files)
        - [Capstone Assignment 1.2 – UML Sequence Diagram](#capstone-assignment-12--uml-sequence-diagram)
            - [How to create your assignment](#how-to-create-your-assignment)
            - [Solution Files](#solution-files)
        - [Ungraded Assignment – UML State Diagram](#ungraded-assignment--uml-state-diagram)
            - [Task Description](#task-description)
            - [Solution Files](#solution-files)

<!-- /TOC -->

## Week2

### Ungraded Assignment - UML Class Diagram

#### Task Description

“Draw a UML class diagram of an Object-Oriented model for a car rental company that keeps track of cars, renters and renters renting cars ”

Create a UML class diagram to represent this information. Showing the correct classes and relationships is enough. Do not add attributes or methods to the classes.

Hint: You may want to make a class for "renters renting cars".

#### Solution Files

- [Car rentals UML Digram](./week2/car-rentals-uml-digram.pdf)

**_[&uarr;top](#assignments)_**

## Capstone Assignment 1.1 – UML Class Diagram

> Given: this [code base](./week2/capstone_assignment_materials/Y_n_-28dR8K5__tvHdfCzA_fde608d7579b432ba1e11f4ef4ac5393_SharingApp-c1-items-only-v4.zip)

### How to create your assignment

**(1) Become familiar with the code:**

In its current state, a user of the app—the owner—is able to record the items they own and wish to share.

The owner may view all of their items, their “Available” items, or their “Borrowed” items.

The owner may change the status of an item they own from “Available” to “Borrowed” and back.

When an item’s status is changed to “Borrowed”, the owner must enter the username of the borrower.

Review the user stories, then download, examine, and run the code base provided.

**(2) Construct a diagram:**

After you have become familiar with the code, construct a UML class diagram that captures the following six classes and three types of relationships in the code base. For each class, you should document all attributes and methods.

The six classes are:

- AppCompatActivity
- AddItemActivity
- EditItemActivity
- ItemList
- Item
- Dimensions

The three types of relationships are:

- Aggregation
- Composition
- Inheritance

#### Solution Files

- [capstone-assignment-1_1–uml-class-diagram](./week2/capstone-assignment-1_1–uml-class-diagram.pdf)

**_[&uarr;top](#assignments)_**

## week3

### Ungraded Assignment – UML Sequence Diagram

#### Task Description

Create a UML sequence diagram that will show your clients how the system’s classes will interact when customers are buying their flight tickets on the booking website.

The system should allow the customer to search available flights from the database by inputting their desired location and departure/arrival date. The website will search the database and return the available flights to display. Once the customer has chosen the flight, they will add the flight to their cart and checkout. They will also then input their payment information and once everything is complete, the website should confirm the flight, empty cart and lastly display a confirmation of the ticket for the flight.

#### Solution Files

- [week3-sequence-digram-ungraded-practice-assignment](./week3/week3-sequence-digram-ungraded-practice-assignment.pdf)

**_[&uarr;top](#assignments)_**

### Capstone Assignment 1.2 – UML Sequence Diagram

> Given: this [code base](./week2/capstone_assignment_materials/Y_n_-28dR8K5__tvHdfCzA_fde608d7579b432ba1e11f4ef4ac5393_SharingApp-c1-items-only-v4.zip)

#### How to create your assignment

Review the code responsible for adding a new item.

Make a sequence diagram that captures the interactions of objects in the app when a new item is added.

**Your sequence diagram should contain the following classes:**

- AddItemActivity
- ItemList
- Dimensions
- Item

**And contain calls of the following methods:**

- onCreate() (provided for you, see Template)
- loadItems()
- saveItem() (provided for you, see Template)
- Dimensions constructor
- Item constructor
- addItem()
- saveItems()

Lastly, the activation of AddItemActivity should start with the call to “onCreate()”

#### Solution Files

- [week3-assignment-capstone-uml-sequence-digram](./week3/week3-assignment-capstone-uml-sequence-digram.pdf)

**_[&uarr;top](#assignments)_**

### Ungraded Assignment – UML State Diagram

#### Task Description

During your two previous assignments you created a UML class diagram and sequence diagram to display your new system for North American airports. You are now required to create a UML state diagram to communicate the state of the planes in the airports.

The airplanes should go through multiple different states. When planes are not in use for a flight they are usually waiting to be assigned. Once a plane is chosen to be used for a flight, they are assigned to that flight until the airplane is ready for take-off. While the plane is in the air and flying the state is termed ‘en route’. Once the plane has reached its destination, the plane has to change into a state of landing for the airport to prepare for its arrival. Finally, once the plane has successfully landed, the plane is checked to see if it is ready to be assigned to a new flight or if maintenance is required. If maintenance is required the plane is unusable and if a mechanic decides that the plane cannot be repaired it is removed from the airport and disposed.

#### Solution Files

- [week3-state-digram-practice-assignment-plane](./week3/week3-state-digram-practice-assignment-plane.pdf)

**_[&uarr;top](#assignments)_**
