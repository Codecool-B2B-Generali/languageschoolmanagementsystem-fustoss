# Language School Management System

## Story

You were asked to write a simple ERP system for your friend Andrew, who happens to run English school. He needs a system to store all data about teachers, classes, and students.

## What are you going to learn?

In this project you will:

- learn what is Object Relational Mapping
- design a database using code first approach

- use azure boards (repository and general environment)


## Tasks

1. Implement logic for the user that has an access to some manager level features. 
    - Admin is able to CRUD (create, edit, update and delete) classes that exists in the school. 
    - Admin is able to CRUD (create, edit, update and delete) teachers that works in the school. 
    - Admin is able to enlist student grouped by class with their personal info (first,last name and age) and enlist  number of students in every class. Also, admin can view all classes managed by teachers.

2. Implement logic for the user that has an access to some teacher level features. 
    - Teacher is able to join/quit to given class.
    - Teacher is able to CRUD (create, edit, update and delete) students in class, also - teacher is able to deactivate or activate students within class. 
    - Teacher is able to check attendance for a student at a given day of given month. 
    - Teacher can be assigned to unlimited number of classes.
    - Classes can have from 10 to 25 students with at most 2 teachers assigned.

3. Implement some simple data representation for student.
    - Student can be enlisted in only one class.
    - Student can check his/her attendance at given day of month.
    - Student join/quit class

## General requirements

- Entity Framework core is used in project with code first approach
- Project is a console based application
- Project follows SOLID principles and utilizes all four pillars of OOP.
- There are three account types - admin, teachers, and students.
- For any account, a combination of the account type, first name, last name, and age must be unique.

## Hints



## Background materials

- [Wikipedia on ORM](https://en.wikipedia.org/wiki/Object%E2%80%93relational_mapping)
-
- <i class="far fa-book-open"></i> [EF Core introduction](https://docs.microsoft.com/en-gb/ef/core/get-started/?tabs=netcore-cli)
- <i class="far fa-video"></i> [EF Core microsoft tutorial](https://www.youtube.com/watch?v=xx5_pVsLP44)
- <i class="far fa-book-open"></i> [Azure board usage tutorial](https://docs.microsoft.com/en-us/azure/devops/boards/get-started/?view=azure-devops)
- <i class="far fa-book-open"></i> [Entity framework code first short explanation](https://entityframeworkcore.com/approach-code-first)
- <i class="far fa-book-open"></i> [Azure repositories](https://azure.microsoft.com/pl-pl/services/devops/repos/)
  
