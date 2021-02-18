# Employee Report

### Problem Description

Build an employee management system of a local grocery store. The shop-owner wants to open the shop on Sunday and due to legal restrictions employees younger than 18 years are not allowed to work Sundays. The employee asks for a reporting feature so she can schedule work shifts. All employees are already stored somewhere and have the following properties:

```js
name: string (the name of the employee)
age: number (the age in years of the employee)
const employees = [
  { name: 'Max', age: 17 },
  { name: 'Sepp', age: 18 },
  { name: 'Nina', age: 15 },
  { name: 'Mike', age: 51 },
];
```

### User Stories

- As shop owner I want to view a list of all employees, which are older than 18 years, so that I know who is allowed to work on Sundays.
- As shop owner I want the list of employees to be sorted by their name, so I can find employees easier.
- As shop owner I want the list of employees to be capitalized, so I can read it better.
- As shop owner I want the employees to be sorted by their names descending instead of ascending.
