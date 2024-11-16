# Expense Tracker App

This is a simple expense tracker application built with HTML, CSS, and JavaScript. It allows you to easily track your daily expenses, categorize them, and visualize your spending habits. 

## Features

- **Add Expenses:** Input the expense name, amount, category, and date.
- **Expense List:** View a list of all added expenses with details.
- **Total Expenses:** See the calculated total of all your expenses.
- **Delete Expenses:** Remove unwanted expenses from the list.
- **Edit Expenses:** Modify existing expense details.
- **Expense Summary:** Get a breakdown of your spending by category.
- **Visual Chart:** Visualize your expenses with a dynamic pie chart.
- **Sort by Date:** Arrange expenses in ascending or descending order by date.
- **Filter by Date Range:** View expenses within a specific date range.
- **Local Storage:** Persist your expense data even after closing the browser.

## Technologies Used

**Front-End:**

- **HTML:** Structuring the web page and its content.
- **CSS:** Styling the application for visual appeal and responsiveness.
- **JavaScript:** Handling user interactions, dynamic updates, and data management.

**Libraries:**

- **Chart.js:** Used for creating the interactive pie chart visualization.

## File Structure

```
expense-tracker/
├── index.html        // Main HTML file
├── styles.css         // CSS stylesheet
└── script.js          // JavaScript logic
```

## HTML Structure (index.html)

- **Header:** Contains the title of the application.
- **Main:** 
    - **Expense Form:** Collects input for adding new expenses.
    - **Filter/Sort Section:**  Provides buttons for sorting and filtering expenses.
    - **Expense List:** Displays the list of added expenses with edit/delete options.
    - **Expense Summary:** Shows a categorized breakdown of expenses.
    - **Chart Container:** Holds the canvas element for rendering the pie chart.
- **Footer:** Displays copyright information.

## CSS Styling (styles.css)

- **Global Styles:** Defines the overall look and feel of the application.
- **Component-Specific Styles:** Styles individual elements like forms, lists, buttons, etc.
- **Media Queries:**  Ensures responsiveness across different screen sizes.

## JavaScript Functionality (script.js)

- **Event Listeners:** Handles form submissions, button clicks, and other interactions.
- **DOM Manipulation:** Updates the content and structure of the web page dynamically.
- **Data Management:** Uses `localStorage` to store and retrieve expense data.
- **Chart Rendering:** Utilizes Chart.js to create and update the pie chart visualization.
- **Filtering and Sorting:** Implements logic for filtering expenses by date range and sorting them.

## How to Use

1. Download or clone the repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Start adding your expenses using the form.
4. Explore the features like deleting, editing, sorting, and filtering.
5. Analyze your spending habits using the expense summary and the pie chart.

Feel free to modify and enhance the application further to suit your needs! 
