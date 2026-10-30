# Envelope Budgeter

## Overview

Envelope Budgeter is a simple web-based budgeting application that helps users manage their monthly income and expenses. It allows users to enter their income, add expenses under different categories, and calculate how much money remains after expenses.

The application also shows whether the user is within their budget or has exceeded it.

## Features

- **Monthly Income:** Enter your total monthly income.
- **Rent Tracking:** Add your monthly rent amount.
- **Expense Categories:** Manage expenses under Food, Utilities, and Entertainment.
- **Dynamic Expense Entries:** Add multiple expenses to each category.
- **Budget Calculation:** Calculate total expenses and remaining income.
- **Budget Status:** Display whether you have a surplus or are over budget.
- **Clear Form:** Reset all input fields and calculated results.
- **Responsive Design:** Works on desktop and smaller screen sizes.

## Technologies Used

- **HTML5** – Provides the structure of the application.
- **CSS3** – Handles styling, layout, colors, and responsive design.
- **JavaScript** – Manages user input, expense calculations, validation, and dynamic form elements.

## Project Structure

text
envelope-budgeter/

index.html
style.css
script.js

## Getting Started

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the Project Folder

```bash
cd envelope-budgeter
```

### 3. Run the Application

Open the `index.html` file in your preferred web browser.

No additional installations or dependencies are required.

## How to Use

1. Enter your total monthly income.
2. Enter your rent amount.
3. Select an expense category from the dropdown menu.
4. Click **Add Entry** to add an expense.
5. Enter the expense name and amount.
6. Repeat the process to add more expenses under different categories.
7. Click **Calculate Remaining Budget** to view your results.
8. Use the **Clear** button to reset the form and start again.

## Budget Calculation

The application calculates the budget using the following logic:

```text
Total Expenses = Rent + Food + Utilities + Entertainment

Remaining Budget = Total Income - Total Expenses
```

- If the remaining budget is positive or zero, the application displays the remaining amount.
- If expenses exceed income, it displays the amount by which the user is over budget.

## Validation

The application includes input validation to detect invalid number formats, including scientific notation such as `2e3`.

## Future Improvements

- Add the ability to edit and remove individual expenses.
- Save budget information using local storage.
- Add expense summaries and visual charts.
- Support additional expense categories.
- Add monthly budget history.

## Author

Developed as a practice project to improve skills in HTML, CSS, and JavaScript.
