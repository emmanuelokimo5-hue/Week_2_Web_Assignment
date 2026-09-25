# Budget Tracker

## Project Description

This project is an improved version of my Week 1 Budget Tracker. It is a simple webpage designed to help users record and view their expenses.

The project uses HTML for the structure and CSS for the design and styling.

## Files

### `index.html`

The `index.html` file contains the main structure of the Budget Tracker.

It includes:

- A page heading and budget tracker icon.
- An Add Expense form.
- Input fields for expense name, amount, and date.
- A category dropdown with Food, Transport, Rent, Entertainment, and Other.
- An expense table containing five sample expenses.
- A collapsible "How to use this tracker" section.
- An embedded budgeting video using an iframe.
- A footer.

### `style.css`

The `style.css` file controls the appearance of the Budget Tracker.

It includes:

- Page and section styling.
- Form styling.
- Table borders and spacing.
- A colored table header.
- Alternating table row colors.
- Table row hover effects.
- Input focus effects.
- Button hover styling.
- Responsive iframe styling.

## HTML Table

The expense table uses:

- `<table>` for the table.
- `<thead>` for the table header.
- `<tbody>` for expense data.
- `<tr>` for table rows.
- `<th>` for column headings.
- `<td>` for expense information.

The table contains four columns:

1. Name
2. Amount
3. Category
4. Date

## Form

The Add Expense form contains:

- Expense name input.
- Amount input.
- Category select dropdown.
- Date input.
- Add Expense button.

Each input has a matching `id` and `label`.

## Multimedia

The project contains:

- An image using the `<img>` element.
- A YouTube video using the `<iframe>` element.

## Interactive Features

The project includes:

- A collapsible `<details>` section.
- Hover effects on table rows.
- Hover effects on the button.
- Focus effects on form inputs.

## Advanced CSS Selectors

The project demonstrates several advanced CSS selectors:

- Descendant selector: `.expenses-section td`
- Direct child selector: `.add-expense-section > form`
- Position pseudo-class: `tr:nth-child(even)`
- Negation pseudo-class: `input:not([type="submit"])`
- Focus pseudo-class: `input:focus`
- Hover pseudo-class: `tr:hover`

## Technologies Used

- HTML5
- CSS3
- GitHub

## How to Run

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. The Budget Tracker will be displayed.

## Future Improvements

JavaScript will be added in future weeks to make the Add Expense button functional and allow users to add expenses dynamically.
