# CodeAlpha_Task1_Age-Calculator
HTML is used to define the structure of the Age Calculator page.

Key Elements:
<input type="date">: Allows users to select their date of birth.
<button>: Triggers the JavaScript function to calculate the age.
<div id="result">: Displays the calculated age result.
id="dob": Used to identify the input field for JavaScript.
onclick="calculateAge()": Calls the calculateAge() JavaScript function when the button is clicked.
id="result": A placeholder to display the output after calculation.
CSS is used to style the page and make it visually appealing.

Key Styling:
Centering the container:

The .container class ensures the form is centered on the page with a white background and rounded corners.
Styling the input and button:

Inputs and buttons have padding, rounded corners, and hover effects for better user experience.
Typography and colors:

Text is styled with a clear font and colors for readability.
JavaScript handles the functionality of the Age Calculator. It calculates the user's age based on the input date and displays the result dynamically.
User Action:

The user selects their date of birth using the date picker and clicks the Calculate Age button.
JavaScript Processing:

JavaScript retrieves the entered date, calculates the age, and adjusts for incomplete months or days.
It ensures all edge cases (e.g., leap years) are handled.
Output Display:

The calculated age is shown in the format:
"You are 25 years, 3 months, and 15 days old."
