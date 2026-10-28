# SpendSnap — Web Expense Manager

A beginner-friendly expense tracker built with HTML, CSS, and vanilla JavaScript. It runs in a browser without Flutter, Node.js, a backend, or internet access.

## Run in VS Code
1. Extract `SpendSnap-Web.zip`.
2. Open the extracted `SpendSnap-Web` folder in VS Code.
3. Install the **Live Server** extension if you do not have it.
4. Right-click `index.html` and choose **Open with Live Server**. You can also double-click `index.html` to open it directly.
5. Add expenses; refresh the page to verify persistence.

No terminal commands are required. This is a web version, not an Android APK.

## Features
- Create, read, edit, and delete expenses.
- Browser `localStorage` persistence.
- Dashboard totals, current-month total, average transaction, recent activity.
- Search descriptions and notes, category filtering, sorting.
- Category breakdown, highest expense, six-month spending chart.
- INR formatting, form validation, delete confirmation, responsive layout.
- No sample transactions are added automatically.

## Project files
- `index.html`: page structure and expense form.
- `styles.css`: responsive design and styling.
- `app.js`: local storage, CRUD operations, search, filters, calculations, and chart.

## Storage note
Records remain in the same browser profile on the same device. There is no cloud sync. Clearing site data, private browsing, or switching browsers/devices can make records unavailable.

## Suggested demo
1. Start with the empty dashboard.
2. Add an expense (for example, Lunch, ₹180, Food & dining, today's date, UPI).
3. Add another expense, then demonstrate totals and category breakdown.
4. Search and filter transactions.
5. Edit an amount and show totals update.
6. Delete a transaction after confirmation.
7. Refresh the page and confirm records remain.

## Viva questions
1. **What is SpendSnap?** A browser-based daily expense manager.
2. **Which technologies are used?** HTML, CSS, and JavaScript.
3. **What is CRUD?** Create, Read, Update, and Delete.
4. **Where is data saved?** In browser `localStorage`.
5. **Does it need a backend?** No.
6. **What happens on refresh?** Saved records are loaded from local storage.
7. **How does edit work?** The form loads existing values and updates that record.
8. **How is delete protected?** A confirmation dialog appears first.
9. **How is monthly spending calculated?** Sum records whose date matches the current year and month.
10. **How does search work?** It checks descriptions and notes.
11. **What is validation?** Checking input values before saving.
12. **Does data sync between devices?** No.
13. **Can it work offline?** Yes, the local files run without network requests.
14. **What is responsive design?** A layout that adapts to different screen widths.
15. **What is a limitation of localStorage?** Browser/device-specific storage can be cleared.
