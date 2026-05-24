README : Vehicle Rental Management System
Student Name    : Nkiyasi Mahlaule
Student Number  : 26370646
Module          : COS2614
Assignment      : Assignment 1


PROJECT DESCRIPTION

A console-based Vehicle Rental Management System built using
Qt Creator 6. The system demonstrates OOP principles
including encapsulation, inheritance, polymorphism and
abstraction. It supports file handling and menu-driven
interaction.

HOW TO BUILD

1. Open Qt Creator
2. Click File -> Open File or Project
3. Open the CMakeLists.txt file in the project folder
4. Select the Desktop Qt 6.11.1 MinGW 64-bit kit
5. Click Configure Project
6. Press Ctrl+B to build the project

HOW TO RUN

1. Open Command Prompt (Windows key, type cmd, press Enter)
2. Type the following command:
   set PATH=C:\Qt\6.11.1\mingw_64\bin;%PATH%
3. Navigate to the build folder:
   cd "C:\Users\NDENGEZA HIGH\Desktop\COS2614\26370646COS2614AS1\build\Desktop_Qt_MinGW_64_bit-Debug"
4. Run the program:
   26370646COS2614AS1.exe

MENU OPTIONS

1. Add vehicle (Car)
2. Add vehicle (Motorcycle)
3. Search vehicle by ID
4. Display all vehicles
5. Display available vehicles only
6. Rent vehicle
7. Return vehicle
8. Exit

DATA FILE

The program automatically loads from and saves to:
vehicle.txt
This file is created in the build folder when the program exits.
File format: Car|ID|Brand|Model|Price|IsRented|Seats|Doors
             Motorcycle|ID|Brand|Model|Price|IsRented|EngineCC

REQUIREMENTS

- Qt 6.11.1 or later
- MinGW 64-bit compiler
- Windows Operating System
