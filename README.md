# Smart Expense Tracker

A lightweight, browser-based expense tracker built with HTML, CSS, and vanilla JavaScript. Add and manage expenses, organize them by category, and view the total for the expenses currently displayed.

## Features

- Record an expense with a name, amount, category, and date
- Edit existing expenses
- Delete expenses with a confirmation prompt
- Filter expenses by category
- See the total of the displayed expenses, formatted in US dollars
- Keep expense data in the browser using `localStorage`
- Use a responsive layout that adapts to smaller screens

## Getting Started

No installation, build step, or package manager is required.

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.
3. Add an expense using the form at the top of the page.

The app runs entirely in the browser and does not require a server or an account.

## Using the Tracker

Enter an expense name, amount, category, and date, then select **Add Expense**. Use **Edit** to update a saved entry or **Delete** to remove one after confirming. The category filter controls which entries are shown, and the total reflects the displayed entries.

Available categories are **Food**, **Transport**, **Shopping**, and **Other**. Amounts are displayed with a `$` symbol.

## Data and Privacy

Expenses are saved in the browser's `localStorage` for the current site origin. Data is not sent to a server and is not automatically synchronized between browsers or devices. Clearing the browser's site data can remove saved expenses.

## Built With

- HTML
- CSS
- Vanilla JavaScript
- Browser `localStorage`

## Project Structure

```text
.
├── index.html   # Page structure and expense form
├── style.css    # Styling and responsive layout
├── script.js    # Expense operations, filtering, and persistence
└── README.md    # Project documentation
```
