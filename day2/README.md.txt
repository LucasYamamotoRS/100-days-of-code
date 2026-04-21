# Tip Calculator Project

A straightforward Python script designed to calculate the exact amount each person should pay when splitting a bill, including a tip. This is a classic beginner project that focuses on data types, mathematical operations, and f-string formatting.

---

## Features

* **Customizable Tips:** Choose between 10%, 12%, or 15% (or any other integer).
* **Dynamic Splitting:** Divide the bill among any number of people.
* **Currency Formatting:** Uses Python's formatting to ensure the final result always displays two decimal places (e.g., $12.50 instead of $12.5).

---

## How It Works

The script calculates the final amount using the following logic:

1.  **Total Tip:** `bill * (tip / 100)`
2.  **Total Bill:** `bill + total_tip`
3.  **Split:** `total_bill / people`

