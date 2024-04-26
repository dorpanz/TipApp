# Let's Split Our Bill!!

This web application helps you calculate how much each person should pay when splitting a bill, including an optional tip.
<p>Live site -  <a>https://main--billcalculatoronline.netlify.app/</a></p>
## Usage

1. Enter the total bill amount in the "Bill" field.
2. Enter the number of people sharing the bill in the "Number of people" field.
3. Optionally, you can add a tip by clicking the "Add a tip!" button and selecting a tip percentage from the dropdown menu.
4. Click the "Calculate" button to see the amount each person needs to pay.

## Technologies Used

- HTML
- CSS
- JavaScript
- [SweetAlert2](https://sweetalert2.github.io/) (for error messages)

## How It Works

- The JavaScript code listens for clicks on the "Calculate" button and calculates the amount each person should pay based on the total bill, the number of people, and the optional tip.
- If any of the required fields are empty or invalid, an error message is displayed using SweetAlert2.

## File Structure

- `index.html`: Contains the HTML structure of the application.
- `style.css`: Stylesheet for the application.
- `script.js`: JavaScript code for the functionality of the application.
- `README.md`: This file, providing information about the application.

## How to Run

1. Download or clone the repository.
2. Open `index.html` in a web browser.
3. Enter the bill amount, the number of people, and optionally add a tip.
4. Click the "Calculate" button to see the split bill details.

Feel free to contribute to this project by making improvements or adding new features!
