# 0x03. ES6 Data Manipulation

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
The **0x03. ES6 Data Manipulation** project focuses on handling and manipulating data structures in JavaScript using modern ES6 features. You'll explore different data structures such as arrays, sets, and typed arrays, while working with functions that perform operations like filtering, mapping, reducing, and more. Efficient data manipulation is a key skill in JavaScript for handling large datasets, enhancing performance, and writing cleaner, more concise code.

## Project Overview
In this project, you will implement various JavaScript functions that manipulate data in different ways. The exercises include filtering arrays based on conditions, performing operations on sets and typed arrays, and working with maps. You will also learn to handle asynchronous data and edge cases related to data structure operations.

### Key concepts covered in this project:
- **Array filtering and mapping**
- **Summing values using reduce**
- **Working with sets**
- **Typed arrays**
- **Handling data in maps**
- **Edge cases in data manipulation**

## Learning Objectives
By the end of this project, you should be able to:
1. Filter and map arrays effectively.
2. Use `reduce` to aggregate data from arrays.
3. Understand and manipulate sets.
4. Work with typed arrays in JavaScript.
5. Perform operations on maps and understand their use cases.
6. Handle edge cases when manipulating data structures.

## Project Structure

Here's a brief description of each file in this project:

1. **0-get_list_students.js**
   - Contains a function that returns an array of student objects.

2. **1-get_list_student_ids.js**
   - Exports a function that extracts student IDs from an array of student objects.

3. **2-get_students_by_loc.js**
   - Filters students by their location and returns the resulting array.

4. **3-get_ids_sum.js**
   - Implements a function that returns the sum of student IDs using the `reduce()` method.

5. **4-update_grade_by_city.js**
   - Updates the grades of students based on their location, applying specific filtering and updating logic.

6. **5-typed_arrays.js**
   - Introduces typed arrays and demonstrates their use in manipulating binary data.

7. **6-set.js**
   - Works with sets, adding and deleting elements, and performs set operations like union and intersection.

8. **7-has_array_values.js**
   - Exports a function to check if a set contains all elements from an array.

9. **8-clean_set.js**
   - Implements a function that removes specific elements from a set.

10. **9-groceries_list.js**
    - Exports a function that returns a map representing a grocery list with items and their quantities.

11. **10-update_uniq_items.js**
    - Manipulates maps and updates the quantities of unique grocery items.

12. **100-weak.js**
    - Demonstrates the use of `WeakMap` and `WeakSet` for handling object references and memory management.

### Additional Files:
- **babel.config.js**
  - Babel configuration file to transpile ES6+ code to older versions of JavaScript for compatibility.

- **package.json**
  - Contains project metadata, including dependencies and npm scripts.

- **package-lock.json**
  - Ensures that the same versions of dependencies are installed across different environments.

## Project Requirements
- **Node.js version 14.x or higher** is required to run the project code.
- Your code should follow the **Airbnb JavaScript style guide**.
- All JavaScript files should be linted using **ESLint**.

### Key Tasks:
1. **Array Manipulation** – Work with `map()`, `filter()`, and `reduce()` to perform common data operations.
2. **Sets and Typed Arrays** – Explore the efficient use of sets and typed arrays for managing and processing data.
3. **Maps and WeakMaps** – Use `Map` and `WeakMap` for storing key-value pairs and learn about their use cases.

## Installation
To run this project, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/
