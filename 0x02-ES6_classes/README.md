# 0x02. ES6 Classes

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Learning Objectives](#learning-objectives)
- [Project Structure](#project-structure)
- [Project Requirements](#project-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Author](#author)

## Introduction
In this project, you will dive deeper into **ES6 classes**, one of the key features introduced in ECMAScript 6. Classes in JavaScript provide a clearer and more concise syntax to create objects and handle inheritance. This project covers the basics of class definition, inheritance, method overriding, and other advanced features like getters, setters, and static methods.

## Project Overview
You will implement various JavaScript files using **ES6 classes** to solve practical problems. The tasks will focus on creating classes for different objects such as classrooms, buildings, currencies, cars, airports, and more. You will also explore concepts like hoisting, inheritance, and method chaining within these classes.

## Learning Objectives
By the end of this project, you should be able to:
1. Define classes and instantiate objects using ES6 syntax.
2. Use constructors to initialize class properties.
3. Implement inheritance using `extends` and the `super` keyword.
4. Understand and use getters, setters, and static methods.
5. Learn about method overriding in subclasses.
6. Understand the concept of hoisting with ES6 classes.

## Project Structure

Here’s a list of the files in this project along with a brief description of each:

1. **0-classroom.js**
   - Implements a `Classroom` class that defines a simple classroom with a capacity.

2. **1-make_classrooms.js**
   - Creates multiple `Classroom` objects using the `Classroom` class from `0-classroom.js`.

3. **2-hbtn_course.js**
   - Defines a `HolbertonCourse` class that models a course with attributes like name, length (in weeks), and students.

4. **3-currency.js**
   - Implements a `Currency` class that represents different currencies with code and name attributes.

5. **4-pricing.js**
   - Introduces a `Pricing` class that uses a `Currency` object to represent the price of a product or service.

6. **5-building.js**
   - Creates a `Building` class with an abstract method that is intended to be overridden by subclasses.

7. **6-sky_high.js**
   - Inherits from the `Building` class and implements the abstract method to create a `SkyHighBuilding` class representing a skyscraper.

8. **7-airport.js**
   - Defines an `Airport` class that models an airport, including its name and code.

9. **8-hbtn_class.js**
   - Models a class in Holberton School with attributes for the course name, student names, and teacher name.

10. **9-hoisting.js**
    - Explores hoisting with ES6 classes by comparing the behavior of function declarations and class declarations.

11. **10-car.js**
    - Creates a `Car` class that models a car with attributes like brand, model, and speed.

12. **100-evcar.js**
    - Extends the `Car` class to define an `EVCar` (electric vehicle) class, adding properties like battery level and range.

### Additional Files:
- **babel.config.js**
  - Babel configuration file to transpile ES6+ code to older versions of JavaScript for compatibility.

- **package.json**
  - Contains metadata about the project, including dependencies and scripts.

- **package-lock.json**
  - Describes the exact versions of npm packages used in the project to ensure consistency.

## Project Requirements
- **Node.js version 14.x or higher** is required to run the project code.
- Your code should follow the **Airbnb JavaScript style guide**.
- All JavaScript files should be linted using **ESLint**.

### Mandatory Tasks:
1. **Create and use classes** – Implement classes and their methods to represent different objects.
2. **Inheritance** – Extend classes using the `extends` keyword to model subclass relationships.
3. **Abstract methods** – Define and override abstract methods in subclasses.
4. **Hoisting** – Understand how hoisting works with classes and functions in JavaScript.

## Installation
To run this project, you'll need Node.js installed on your machine. Follow these steps to get started:

1. Clone this repository:
   ```bash
   git clone https://github.com/Khalidelaasry/alx-backend-javascript.git
