# Personal Data Collector

The **Personal Data Collector** is a simple, interactive Python script designed to gather basic user information and perform a quick calculation based on that data. It demonstrates fundamental Python concepts such as input handling, variable type management, memory introspection, and basic date manipulation.

## Features

* **Data Collection:** Prompts the user to input their name, age, height, and favorite number.
* **Data Insight:** Displays the collected data along with its corresponding data type and memory address in the system.
* **Age Calculation:** Calculates the estimated birth year based on the current system date and the user's provided age.

## How to Use

1.  **Prerequisites:** Ensure you have Python installed on your system.
2.  **Running the Script:** Execute the `Project.ipynb` file in a Jupyter Notebook environment or convert the code to a `.py` script to run it in your terminal.
3.  **Interaction:** Follow the on-screen prompts:
    * Enter your name (string).
    * Enter your age (integer).
    * Enter your height in meters (float).
    * Enter your favorite number (integer).
4.  **Result:** The script will output a summary of your data, including technical details and your estimated birth year.

## Code Overview

The script utilizes the following:
* `input()`: For capturing user responses.
* `type()`: To verify the data type of the variables.
* `id()`: To display the object's unique memory address.
* `datetime`: To fetch the current year and perform dynamic calculations.

---
*Created by: Rudhiyansh Vijaybhai Sandanshiv*
