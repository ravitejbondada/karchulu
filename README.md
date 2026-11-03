# Karchulu

A lightweight monthly budget tracker that runs directly in your browser. It is a single HTML file with no build step, dependencies, or server required.

## Use

Open `karchulu.html` in a browser. Use the arrows in the header to move between months. Each month is organized into Income, Loans, Expenses, and Credit cards.

- Add rows and edit their names and planned amounts.
- Mark an outflow as done to enable its actual amount. Actuals default to the planned amount and can be edited; income actuals follow the same rule.
- Review planned and actual income, expenses, net, spending percentage, and unpaid amounts in the summary.
- New installs start with example budget rows. Later months can be copied from a previous month when needed.
- Amounts are in Indian rupees (₹). Amount fields accept values such as `1,200`, `6.6k`, `1l`, and sums such as `1+0.8`.

## Data and backups

Budget data is stored in the browser's local storage on the current device. It is not sent to a server. Clearing browser data or switching browsers/devices can remove or leave behind your budget, so use **Export** to download a JSON backup. **Import** loads a backup and replaces the current data after confirmation.