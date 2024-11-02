# Body Fat Percentage Calculator

This Python program helps users calculate their body fat percentage by gathering specific body measurements. It includes separate calculations for males and females, utilizing skinfold measurements and circumferences for accurate body fat estimation. The program employs stack operations for efficient data handling and offers a simple, menu-based interface for user interaction.

## Features

- **User-Friendly Interface**: The program starts with a welcome message and provides a clear menu to select gender-specific calculations or exit.
- **Gender-Specific Calculations**: It offers tailored body fat percentage calculations for males and females, accounting for different body measurement requirements.
- **Stack Operations**: Utilizes stack operations for efficient data management.
- **Validation**: Ensures that body fat percentage results are within a realistic range.

## Usage

1. **Run the Program**: Start by running the program, and you’ll see a welcome message guiding you to the menu.
2. **Choose Gender**:
   - Press `1` for the male body fat percentage calculator.
   - Press `2` for the female body fat percentage calculator.
   - Press `3` to exit the program.
3. **Input Measurements**:
   - For males: Input values for chest skinfold, abdomen skinfold, thigh skinfold, waist circumference, forearm circumference, and age.
   - For females: Input values for tricep skinfold, thigh skinfold, suprailiac skinfold, gluteal circumference, and age.
4. **View Results**: The program will calculate and display the body fat percentage based on the provided inputs. It ensures the calculated percentage is within a feasible range.

## How it Works

The program calculates body fat percentage using the **Jackson-Pollock formula**, which leverages skinfold thickness and circumferences for different body areas. By obtaining values through user input and performing calculations based on body density formulas, it returns an estimated body fat percentage.

- **Formula for Males**: The program uses measurements from the chest, abdomen, and thigh skinfolds, along with waist and forearm circumference.
- **Formula for Females**: The program uses measurements from the tricep, thigh, and suprailiac skinfolds, along with gluteal circumference.

## Requirements
-Python 3.x

