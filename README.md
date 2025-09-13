📘 Documentation: Student Finance Manager
1. Overview

The Student Finance Manager is a web-based personal finance tool tailored for students. It allows users to track expenses, manage monthly budgets, set savings goals, and gain insights through AI-powered categorization and predictive analytics. A visual dashboard powered by Chart.js helps users understand their spending habits.

2. Features

Expense Tracking

Add expenses with description, amount, and category.

AI-powered auto-categorization based on description keywords.

Recent expenses list with date, category, and amount.

Budget & Goals

Set a monthly budget.

Add savings goals with progress tracking and completion percentage.

Budget alerts when spending exceeds thresholds (75% & 90%).

Predictive Analytics

Estimates monthly spending using daily average and remaining days.

Requires at least 3 expense entries for meaningful predictions.

Spending Analytics Dashboard

Interactive doughnut chart powered by Chart.js.

Visualizes spending by category (Food, Transportation, Books, Entertainment, Housing, Health, Other).

Responsive Design

Modern, mobile-friendly UI with gradients, animations, and hover effects.

3. Technologies Used

HTML5 – Page structure & form inputs.

CSS3 – Custom styling with gradients, animations, and responsive design.

JavaScript (Vanilla) – Core functionality for expense tracking, goals, predictions, and chart updates.

Chart.js (v3.9.1) – Visualization for spending analytics.

4. File Structure
StudentFinanceManager/
│── index.html   # Main HTML file with embedded CSS and JavaScript

5. How It Works
a) Adding Expenses

User enters amount and description (category optional).

If no category is selected, the app auto-categorizes using keyword matching.

Expense is saved with a timestamp and shown in Recent Expenses.

b) Budget & Goals

User sets a monthly budget and optional savings goals.

Each goal tracks progress visually with a progress bar.

Spending alerts appear when 75% or 90% of the budget is consumed.

c) Predictive Analytics

Calculates daily average spending.

Projects total spending for the month.

Helps students anticipate overspending before the month ends.

d) Spending Dashboard

Aggregates expenses by category.

Displays as a doughnut chart.

Auto-updates whenever a new expense is added.

6. Key JavaScript Functions

categorizeExpense(description)

Auto-detects category based on keywords (e.g., "coffee" → Food).

addExpense()

Creates a new expense object and updates the display.

setBudgetAndGoal()

Updates monthly budget and adds savings goals.

updateDisplay()

Refreshes expenses, goals, and charts.

checkBudgetAlerts()

Warns when spending exceeds thresholds.

updatePredictions()

Predicts monthly spending based on current trend.

updateChart()

Generates/updates the Chart.js doughnut chart.

7. How to Run

Save the code as index.html.

Open the file in any modern browser.

Add expenses, set a budget, and watch the analytics update in real time.

8. Possible Enhancements

✅ Store expenses in localStorage or a database (so data persists).

✅ Integrate with real AI/NLP models for smarter categorization.

✅ Export expenses and reports to CSV/PDF.

✅ Add income tracking for balance calculation.

✅ Notifications/reminders for staying within budget.
