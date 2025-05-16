# Employee Task Manager (MongoDB)

This project demonstrates how to manage employees and their tasks using MongoDB. It includes the following:

- Creating employee and task collections.
- Establishing a one-to-many relationship between employees and tasks using `ObjectId`.
- Performing various aggregation operations like `$lookup`, `$group`, `$match`, `$project`, `$sort`, and `$limit`.

## Collections

- `employee`: Stores employee details including name, age, salary, skills, and address.
- `task`: Stores tasks assigned to each employee.

## Features

- Insert multiple employees and tasks.
- Use `$lookup` to fetch related tasks for each employee.
- Aggregate data such as total salary, average age, and filtering by salary.
- Sort and limit results to find top-paid employee.

## Sample Queries

- View all employees with their tasks.
- Filter employees with salary greater than 10,000 and display their tasks.
- Group statistics: total salary, average age, and total employees.
- Find the highest paid employee.

## Technologies

- MongoDB
- JavaScript (Mongo Shell syntax)
