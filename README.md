# Al Jefoon Tents — Customer Accounts

A standalone browser-based customer accounts application. No server, npm, database, or external libraries are required.

## Start immediately
Open `index.html` in Chrome or Edge. Everything is contained in this one file.

## Data
Data is stored in the browser's localStorage. Use **Backup & Data → Export Full Backup** regularly.

## Accounting rules
- Credit Sale: increases amount customer owes Al Jefoon.
- Payment Received: reduces amount customer owes Al Jefoon.
- Credit Purchase: increases amount Al Jefoon owes the customer.
- Payment Made: reduces amount Al Jefoon owes the customer.
- Positive balance = receivable from customer.
- Negative balance = payable/credit owed by Al Jefoon.

## Included
Customers, opening balances, transactions, payments, cheque register, 5-day cheque reminders, pending/due/overdue/cleared/returned cheque statuses, edit/delete, customer statements, multi-customer A4 printing, payment report, CSV exports, JSON backup/restore, dashboard clock, dark mode, search/filtering, responsive layout.
