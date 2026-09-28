# CSYE 6200 - Lab 3: Continuation of Java Swing

A Java Swing user profile form developed using **Java 21** and **NetBeans**. The application allows users to enter their personal information, validate the data, upload a photo, and display the submitted profile.

## Features

- User profile form using Java Swing
- `model.user` class with:
  - Getters
  - Setters
  - `toString()` method
- User input fields:
  - First Name
  - Last Name
  - Age
  - Gender
  - Phone
  - Email
  - Continent
  - Hobbies
  - Photo
- Gender selection using a Combo Box
- Input validation for:
  - Name
  - Phone
  - Email
- Photo upload functionality
- Photo preview
- Success popup displaying the entered information
- Maven-based Java project

## Project Structure

```text
Test/
├── src/
│   └── main/
│       └── java/
│           ├── model/
│           │   └── user.java
│           │
│           └── ui/
│               └── MainJFrame.java
│
├── Screenshots/
│   ├── form.png
│   └── success.png
│
├── pom.xml
└── README.md
