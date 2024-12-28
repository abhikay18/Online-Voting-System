# Online Voting System

## 1. Introduction

This project aims to build an **Online Voting System**, designed to efficiently manage and handle voter, candidate, and voting data. The system offers a user-friendly and paperless way to cast votes in a poll and access them whenever required, reducing human effort. 

The system is capable of:
- Storing new voter, candidate, and poll data.
- Updating stored data when necessary.
- Providing admin access with the authority to manipulate data elements, ensuring security.
- Allowing normal users to cast their votes for their desired candidate.

The system prioritizes safety and security, ensuring that only the admin can manage the data while users are restricted to casting their votes.

## 2. OOP Concepts Covered

This project integrates several Object-Oriented Programming (OOP) concepts, which are essential for its functionality and efficiency. The following OOP concepts have been utilized:

### 2.1 Inheritance

Inheritance is a fundamental concept in this project. Different classes such as `Voter`, `Candidate`, etc., have been defined, and various data objects of these classes are accessed by the `Admin` class using inheritance. This promotes code reusability and organization.

### 2.2 Polymorphism

Polymorphism has been effectively implemented in this project, including:
- **Function Overloading**: Multiple functions with the same name but different parameters.
- **Function Overriding**: Re-defining functions in derived classes.
- **Operator Overloading**: Custom behavior for operators.

### 2.3 Abstract Classes and Virtual Functions

Abstract classes and pure virtual functions have been used to provide a common structure for different classes that share similar functionality. This simplifies the code and promotes clarity.

### 2.4 Friend Functions

Friend functions allow certain functions to access private data (e.g., the admin's username and password) of the classes. This ensures secure access to sensitive information when needed.

### 2.5 Constructors and Destructors

Constructors and destructors are used to initialize objects and clean up resources when they are no longer needed. This ensures proper management of resources throughout the program's execution.

### 2.6 File Handling

File handling plays a crucial role in this system, storing candidate, voter, and poll data. The results of polls are saved to files, ensuring that the data can be accessed and manipulated later.

### 2.7 Vectors

Vectors are used as dynamic data containers, allowing the system to store data of any type without defining a fixed size. Both 1-D and 2-D vectors are used for efficient data retrieval and storage.

## 3. Additional OOP and C++ Concepts Used

In addition to the core concepts mentioned above, the project incorporates the following:

- **Inline Functions**: Functions that are expanded in line at compile time to reduce function call overhead.
- **Default Arguments**: Functions that use default values for parameters if not provided by the user.
- **Console and Text Coloring**: Console output is enhanced with colored text using Windows' header file, creating a more interactive and user-friendly interface.

## 4. Features

- **Admin Panel**: Admins can add, update, or delete voter and candidate data.
- **Voting Process**: Users can cast their votes for a candidate of their choice.
- **Data Storage**: All data (voter, candidate, poll results) are stored in files for easy retrieval.
- **Security**: Admin login is password-protected, ensuring that only authorized personnel can manage the system.

## 5. Technologies Used

- C++
- File Handling
- Vectors
- OOP Principles

## 6. Installation

To run the Online Voting System, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/abhikay18/Online-Voting-System.git
    ```

2. Compile the C++ code:
    ```bash
    g++ main.cpp -o online_voting_system
    ```

3. Run the program:
    ```bash
    ./online_voting_system
    ```
