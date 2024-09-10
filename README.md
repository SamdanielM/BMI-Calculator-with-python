# BMI-Calculator-with-python
This Python script calculates BMI based on weight (kg) and height (cm), then provides a personalized health risk assessment. It categorizes users as underweight, normal, overweight, obese, severely obese, or morbidly obese and gives relevant health advice based on their BMI.

BMI Calculator in Python
This Python script is designed to calculate an individual's Body Mass Index (BMI) based on their input weight (in kilograms) and height (in centimeters). BMI is a measure commonly used to assess whether a person has a healthy body weight relative to their height. This calculator provides both the BMI value and a detailed health risk assessment, allowing users to understand their category in terms of underweight, normal weight, overweight, or obesity.

How It Works:
User Input:
The program starts by asking the user to enter their name.
The user is then prompted to input their weight in kilograms and their height in centimeters.
BMI Calculation:
The BMI is calculated using the formula:
BMI = weight / (height * height)
Since height is typically measured in meters for BMI calculations, the input height in centimeters is squared in the calculation to align with the formula.
BMI Interpretation:
Based on the calculated BMI, the script provides personalized feedback. The categories and associated health risks are as follows:
Underweight (BMI < 18.5): The individual is advised to gain muscle, as their health risk is minimal but present.
Normal weight (18.5 ≤ BMI ≤ 24.9): The individual is deemed fit, with minimal health risks.
Overweight (25 ≤ BMI < 29.9): The user is informed that their health risk has increased and is advised to take caution.
Obese (30 ≤ BMI < 34.9): At this stage, health risks are high, and fat loss is recommended.
Severely obese (35 ≤ BMI < 39.9): Health risks become very high, and the user is urged to lose weight.
Morbidly obese (BMI ≥ 40): The health risk is extremely high, with a strong recommendation to take immediate action.
Example:
Enter your Name: Sarah
Enter your Weight in Kg: 80
Enter your Height in cm: 160

BMI: 31.25
Sarah, you are obese & your health risk is high. Lose some fat and be more cautious.
