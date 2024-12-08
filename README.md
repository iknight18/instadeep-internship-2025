# Software Engineering Internship Technical Assessment

Welcome to the technical assessment for the Software Engineering Internship position at **InstaDeep**.
This assessment is designed to evaluate your programming skills, understanding of software design principles, and ability to build functional APIs.

The test consists of three parts, each focusing on a different skill area.
You are encouraged to use any programming language and tools you are comfortable with.

---

## Scenario: Building a Task Management Tool

You have joined **TaskMaster Inc.** , a fictional startup focused on developing an innovative task management tool to help individuals and teams organize their work efficiently. Throughout this assessment, you will work on various components of this tool, simulating real-world challenges a software engineer might face in a professional setting.

---

## General Instructions

- **Time Estimates** :

  - **Part 1** : Approximately 30 mins
  - **Part 2** : Approximately 1 Hour
  - **Part 3** : Approximately 30 mins

- **Submission** :

  - Include all source code files and documentation in a single git repository
  - Provide a README file with instructions on how to run your code.
  - Focus on correctness, efficiency, code quality, and adherence to best practices.

---

## Part 1: Programming Challenge

### Objective

- Assess your basic programming skills and problem-solving abilities.

### Task

As part of the **TaskMaster** tool, you need to implement a function that processes task descriptions. Your task is to write a function that determines if a given task description is a **palindrome** .

However, task descriptions can include punctuation, spaces, and varying capitalization. Your function should correctly identify palindromic phrases regardless of these factors.

### Requirements

- **Language** : Any programming language of your choice.

- **Functionality** :

  - The function should take a single string input (the task description).
  - Return `true` if the description is a palindrome, `false` otherwise.

- **Edge Cases** :

  - Ignore punctuation marks (e.g., commas, periods, exclamation points).
  - Ignore spaces.
  - Ignore capitalization (case-insensitive comparison).

### Examples

- Example#1

  - **Input** : `"Madam, in Eden, I'm Adam"`
  - **Output** : `true`

- Example#2

  - **Input** : `"Complete the project report"`
  - **Output** : `false`

### Deliverables

- Source code file containing the function.
- A brief explanation (optional comments within the code are sufficient).

- **Optional** : Test cases demonstrating your function works as expected.

### Scoring Rubric

| Criteria | Weight |
| --- | --- |
| Correctness | 40% |
| Efficiency | 20% |
| Edge Case Handling | 20% |
| Code Readability and Documentation | 20% |

---

## Part 2: Applying Software Design Principles to Enhance Task Management

### Objective

Evaluate your understanding and application of fundamental software design principles to create scalable, maintainable, and testable code.

### Scenario

As TaskMaster Inc. continues to grow, managing tasks efficiently has become more complex.
The current system handles task categories and priorities in a rigid manner, making it challenging to introduce new categories or modify priority handling without significant code changes.

Your mission is to redesign the task management system's category and priority components using fundamental software design principles.
This will make the system more modular, extensible, and easier to maintain.

### Task

Design and implement a modular task management system that allows for flexible handling of task categories and priorities.
Apply software design principles such as **Dependency Injection** , **Inversion of Control (IoC)** , and the **Factory Pattern**  to achieve this.

### Requirements

#### Functional Requirements (Mandatory)

1. **Task Categories** :

- Allow dynamic addition and removal of task categories.
- Enable tasks to be assigned to one or more categories.
- Provide functionality to list all available categories.

2. **Task Priorities** :

- Implement multiple priority levels (e.g., Low, Medium, High).
- Enable tasks to be sorted or filtered based on their priority levels.

3. **Task Operations**

- Create new tasks with title, description, category, priority, and due date.
- Update existing tasks' details.
- Delete tasks.
- Retrieve tasks with options to filter by category and priority.

#### Design Requirements (Mandatory)

1. **Application of at Least One Design Principle** :

- Choose **one**  of the following design principles to apply in your system:

  - **Dependency Injection (DI)**
  - **Inversion of Control (IoC)**
  - **Factory Pattern**

- Clearly demonstrate how you have applied the chosen principle in your design.

2. **Code Organization** :

- Organize code into classes/modules/packages appropriately.
- Ensure high cohesion within modules and low coupling between them.

3. **Error Handling** :

- Implement proper error handling for invalid operations (e.g., adding a task to a non-existent category).

#### Optional Enhancements (Bonus Points)

1. **Applying Additional Design Principles** :

- Briefly explain how each additional principle is applied in your design.

2. **Testing** :

- Write unit tests for key components to demonstrate testability.
- Use mocking frameworks or techniques where appropriate.

3. **Advanced Features** :

- Implement additional functionalities such as:
  - Recurring tasks.
  - Task dependencies (e.g., Task B cannot start until Task A is completed).
  - Notifications or reminders for due tasks.

#### Documentation

- **Design Document**:
  - A brief write-up explaining:
    - How you applied the chosen design principle(s).
    - How your design promotes modularity, extensibility, and maintainability.
    - Any challenges faced and how you overcame them.
    - Diagrams (e.g., class diagrams) to illustrate your design are encouraged.

- **Code Comments** :
  - Include comments in your code to explain complex logic or important decisions.

  - Use DocStrings or similar documentation features provided by your programming language.

### Deliverables

1. **Source Code** :

- All source code files implementing the task management system.

- Ensure the code is clean, well-organized, and follows coding standards.

2. **Design Document** :

- A small written document explaining your design choices and how they fulfill the requirements.

3. **Instructions** :

- A README file with instructions on how to set up and run your application.

- Include any prerequisites and how to run your application.

4. **Optional Deliverables** :

- Unit test files demonstrating the testability of your system.

- Additional documentation or diagrams that support your design.

- Implementation of advanced features.

### Scoring Rubric

| Criteria | Weight |
| --- | --- |
| Application of Design Principle | 40% |
| - Correct application of at least one design principle |  |
| - Demonstration of understanding in the design document |  |
| System Modularity and Extensibility | 25% |
| - Ease of adding new categories and priorities |  |
| - Low coupling and high cohesion |  |
| Code Quality and Clarity | 25% |
| - Readable and maintainable code |  |
| - Proper naming conventions and code structure |  |
| - Adequate commenting and documentation |  |
| Optional Enhancements (Bonus Points) | Up to 10% |
| - Application of additional design principles |  |
| - Implementation of unit tests |  |
| - Addition of advanced features |  |

*Note: The total score for this part is 100%. Bonus points can enhance your score up to a maximum of 110%, providing an opportunity to exceed expectations.*

### Tips for Success

- **Focus on Core Requirements First** : Ensure that you have fully met all the mandatory requirements before attempting optional enhancements.

- **Understand the Design Principle** : If you choose to apply Dependency Injection, Inversion of Control, or the Factory Pattern, make sure you understand it well and can implement it correctly.

- **Plan Your Design** : Before coding, sketch out your classes and how they interact. This will help you organize your thoughts and create a cleaner design.

- **Write Clear Code** : Prioritize readability and maintainability in your code. Use meaningful variable and method names.

- **Document Your Work** : A well-written design document can significantly enhance your submission by clearly conveying your understanding and thought process.

- **Optional Enhancements** : If you have time and are comfortable, attempt the optional enhancements to demonstrate further skills and initiative.

### Frequently Asked Questions

**Q:**  Is it acceptable to use external libraries or frameworks?

**A:**  Yes, you may use standard libraries or frameworks appropriate for your chosen programming language, especially if they facilitate applying the design principles. Be sure to mention any such usage in your design document.

**Q:**  Do I need to create a user interface?

**A:**  No, a user interface is not required. You can demonstrate your application's functionality through a simple command-line interface or by providing example usage in your README file.

**Q:**  How detailed should the design document be?

**A:**  The design document should be concise (max 1-2 pages) but informative. Focus on explaining how you applied the design principle(s), your system's modularity and extensibility, and any significant design decisions.

**Q:**  If I apply more than one design principle, will I get extra credit?

**A:**  Yes, applying additional design principles is considered an optional enhancement and can earn you bonus points

---

## Part 3: Building an API with Database Integration

### Objective

Assess your ability to create a functional API and design a database schema for solving real-world problems.

### Task

You are tasked with developing a fully functional API for the TaskMaster tool that allows users to manage their tasks through HTTP requests.

### Requirements

- **Language & Framework** : Any language and framework suitable for API development.

- **Functionality** :

  - Implement RESTful API endpoints for the following operations:
    - **Create**  a new task.

    - **Retrieve**  tasks (with options to filter by category or due date).

    - **Update**  existing tasks.

    - **Delete**  tasks.

  - Each task should have the following attributes:
    - Title
    - Description
    - Priority
    - Category (e.g., Work, Personal, Urgent)
    - Due Date
    - Completion Status

- **Database Integration** :
  - Design a database schema to store tasks.

  - Use any relational database system (e.g., MySQL, PostgreSQL, SQLite).

- **Bonus Points** :
  - **Dockerization** : Provide a Dockerfile and/or docker-compose.yml to containerize the application for easy setup.

  - **Documentation** : Include clear instructions on how to set up and run the application, as well as API endpoint documentation (e.g., using Swagger or a README file).

### Deliverables

- Source code files for the API application.

- Database schema (SQL file or ORM models).

- Documentation:
  - Setup instructions.

  - API usage guide.

- **Optional** : Docker configuration files.

### Scoring Rubric

| Criteria | Weight |
| --- | --- |
| API Functionality | 30% |
| Database Design | 20% |
| Use of Docker | 20% |
| Documentation | 10% |
| Code Quality and Best Practices | 10% |

---

## Submission Guidelines

- Ensure all parts are completed and included in your submission.

- Organize your files into folders for each part for clarity.

- Include a main README file that outlines the contents of your submission.

---

## Evaluation Criteria Summary

Your submission will be evaluated based on the criteria outlined in each part's scoring rubric. Focus on delivering code that is not only correct but also efficient, well-documented, and adheres to best practices. Demonstrating a clear understanding of software design principles and real-world application development will set you apart.

---

## Good Luck

We look forward to reviewing your work and potentially welcoming you to the TaskMaster Inc. team!

---
