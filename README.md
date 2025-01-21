# MATLAB-Coffee-Machine

## Description
The Coffee Machine is a MATLAB-based application designed to emulate a real-world coffee vending machine. It offers six types of coffee, complete with an engaging preparation animation that simulates coffee being poured into a cup. Users can select their preferred coffee, and the system handles all aspects of inventory management, including coffee availability and coin quantities.

## Project Goals and Purpose
The primary objective of this project is to create an interactive and realistic coffee vending machine simulation. It serves as both a fun, engaging tool and a learning platform for MATLAB programming concepts. By focusing on inventory management and transaction handling, the project provides a hands-on experience in problem-solving, algorithm design, and file handling.

## Key Features
- **Six Coffee Options**- Users can choose from six coffee types: Espresso, Cappuccino, Latte, Americano, Mocha, and Irish Coffee. Each type has a predefined price and quantity managed by the program.

- **Pouring Animation**- The program includes a visual representation of coffee being poured into a cup, adding an element of realism and user satisfaction.

- **Change Return System**- A dedicated function calculates and dispenses the correct change based on the user's payment and coffee price, ensuring smooth transactions.

- **Inventory Management**- Coffee quantities and coin inventories are managed using two external files:
  
    coffeeQuantities.mat: Tracks the remaining quantities of each coffee type.

    coinQuantities.mat: Tracks the available coins for making change.

    The program automatically updates these files after each transaction.

- **Error Handling**- If a selected coffee is out of stock or there aren’t enough coins to provide change, the system notifies the user and prompts them to make a different selection or cancel the transaction.

- **End-of-Session Updates**- The system updates and saves the latest coffee and coin quantities in the respective files at the end of each session.

## Technologies Used
The project is implemented entirely in MATLAB, utilizing its powerful file handling, data processing, and visualization capabilities.

## Instructions for Running the Project

1. Verify Prerequisites: Ensure MATLAB is installed on your system.
2. Download Files: Download the required files from the repository:

    FINALproject.mlapp: The main program file.

    coffeeQuantities.mat: Initial coffee stock data.

    coinQuantities.mat: Initial coin inventory data.

3. Run the Program: Open FINALproject.mlapp in MATLAB and execute the file to start the simulation.
4. Enjoy the Coffee Machine Simulation: Select your coffee type, watch the pouring animation, and receive your change while the system manages the inventory in real-time.
