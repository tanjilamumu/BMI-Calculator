# BMI Calculator 🏋️

## Overview

This project is a **console-based BMI (Body Mass Index) Calculator** developed using Java.

The application calculates a user's BMI based on their weight and height. The program accepts weight in pounds and height in meters, converts the weight into kilograms, calculates the BMI value, and displays the corresponding health category.

This project demonstrates Java programming fundamentals including user input handling, mathematical calculations, data conversion, and conditional statements.

---

## Features

- Accepts user weight in pounds
- Accepts user height in meters
- Converts pounds to kilograms
- Calculates BMI using the standard BMI formula
- Displays BMI value
- Provides health classification:
  - Underweight
  - Healthy
  - Overweight
  - Obese

---

## Technologies Used

- **Java**
- **Scanner Class** - Used to collect user input
- **Arithmetic Operators** - Used for BMI calculations
- **Conditional Statements (`if-else`)** - Used for BMI classification
- **Variables and Data Types** - Used to store calculation values

---

## BMI Formula

The program uses the standard BMI formula:

```
BMI = Weight (kg) / Height² (m)
```

The program converts weight from pounds to kilograms using:

```
Weight in KG = Weight in Pounds × 0.453592
```

---

## BMI Categories

| BMI Range | Category |
|-----------|----------|
| Less than 18.4 | Underweight |
| 18.5 - 24.9 | Healthy |
| 25 - 29.9 | Overweight |
| 30 or above | Obese |

---

## Example Output

```
Enter your weight in pounds:
150

Enter your height in meters:
1.70

Your BMI is: 23.06

You are Healthy
```

---

## How to Run the Project

### Prerequisites

Make sure you have:

- Java Development Kit (JDK) installed
- Java IDE installed (Eclipse, IntelliJ IDEA, or VS Code)

### Steps

1. Clone or download this repository.

2. Open the project in your Java IDE.

3. Navigate to the Java file:

```
BMICalculator.java
```

4. Run the program.

5. Enter your:
   - Weight in pounds
   - Height in meters

6. View your BMI result and health category.

---

## Future Enhancements

Possible improvements:

- Add support for height input in feet and inches
- Add input validation for incorrect values
- Format BMI output to two decimal places
- Add metric and imperial unit options
- Create a graphical user interface (GUI)
- Add detailed health recommendations

---

## Learning Outcomes

Through this project, I practiced:

- Using Scanner for user input
- Performing unit conversions
- Applying mathematical formulas in Java
- Working with conditional statements
- Using `double` data types for decimal calculations
- Building a real-world health calculation application
