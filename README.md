# 📄 Date Difference Calculator

A simple, clean and accurate GUI tool to **calculate the exact
difference between two dates** in
**Years, Months, and Days**, using **Python + Tkinter**.
It uses a **calendar-accurate algorithm**, so month lengths and leap
years are calculated perfectly.

---

## ✨ Features

-   🖱️ Easy-to-use graphical interface (Tkinter)
-   📅 Enter two dates in **DD-MM-YYYY** format
-   🔍 Calculates **accurate** difference:
    -   ✔ Years
    -   ✔ Months
    -   ✔ Days
-   🧠 Handles leap years, month lengths, and date borrowing correctly
-   💨 Lightweight -- no external libraries required
-   🎨 Clean and minimal UI

---

## 📂 Project Structure

``` bash
Date-Calculator/
│
├── main.py                # Main application
├── LICENSE
└── README.md              # Project documentation
```

---

## 🧰 Requirements

Make sure you have **Python 3.7+** installed.

No external libraries needed -- `Tkinter` and `datetime` are built into
Python.

---

## 🚀 Usage

1.  Clone or download this repository:

    ``` bash
    git clone https://github.com/sagesakshi27/Date-Calculator.git
    cd Date-Calculator
    ```

2.  Run the Python script:

    ``` bash
    python main.py
    ```

3.  A GUI window will open -- enter **two dates** and click
    **"Calculate Difference"**
    The app will display the exact **Years, Months, Days** difference.

---

## 🧠 How It Works

-   Parses both input dates.
-   Uses a **custom, precise Y/M/D calculation algorithm**:
    -   Calculates years first
    -   Then adjusts months
    -   Handles negative days by borrowing from the previous month
    -   Ensures full calendar accuracy
-   Shows the result in a clean label area.

---

## ⚙️ Tech Stack

-   **Python 3**
-   **Tkinter** --- GUI Interface
-   **Datetime** --- Date calculations

---

## 👨‍💻 Author

> **Developer:**  **Sakshi Chavan**

> **Github:** **[sagesakshi27](https://github.com/sagesakshi27)**

---
