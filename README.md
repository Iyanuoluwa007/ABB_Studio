# ABB RobotStudio Drawing Project

This project demonstrates a simulated ABB robot programmed using RAPID in ABB RobotStudio to draw various shapes and text including names and words using precise robotic motion paths.

## 📁 Project Files

- **Oke_Iyanuoluwa.rspag** — The ABB RobotStudio project file (simulation environment and configuration).
- **Oke_Iyanuoluwa_ABB_Code.docx** — The RAPID code used to control the robot's motion and drawing tasks.

## 🛠️ Features

The robot is programmed to draw:
- **Shapes**:
  - Circle
  - Box
  - Letter 'D'
- **Text**:
  - "SALFORD"
  - The full name: **Iyanuoluwa**

The user selects which drawing to perform using the teach pendant interface via `TPReadFK`.

## 🧠 How It Works

- The `main` procedure initializes the user interface.
- Based on user input, it calls one of the following procedures:
  - `Shapes()` — draws geometric shapes.
  - `Salford()` — writes out the word “Salford”.
  - `MyName()` — writes out the user's name.
  - `All()` — executes all drawings sequentially.

Each drawing is composed of predefined `robtarget` positions using `MoveJ`, `MoveL`, and `MoveC` instructions.

## 🤖 Tools & Configuration

- **ABB RobotStudio** (tested version: 202X.X.X)
- **RAPID** programming language
- **Tooldata** and **wobjdata** are customized for pen-like drawing applications.

## 📸 Screenshots

(*You can add screenshots or short gifs of the simulation here for better presentation.*)

## 🧑‍💻 Author

Oke Iyanuoluwa E.
