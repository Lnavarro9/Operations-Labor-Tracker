# Operations Labor & Time Tracker (C++)

A command-line workforce and task management utility built in C++ designed to track shift hours, categorize operational tasks, calculate labor costs, and maintain persistent local records. 

## 🚀 Features

* **Shift & Time Logging:** Record dates, specific task categories, hours worked, and custom hourly pay rates.
* **Cost & Efficiency Analysis:** Automatically computes total labor costs per entry and aggregates overall project/shift expenditures.
* **Persistent File I/O:** Saves and loads historical time logs seamlessly using local text storage (`labor_tracker_data.txt`).
* **Clean Terminal Interface:** Organized tabular summaries for quick data review and analysis.

## 🛠️ Tech Stack

* **Language:** C++
* **Libraries:** `<iostream>`, `<vector>`, `<fstream>`, `<sstream>`, `<iomanip>`
* **Concepts:** Object-Oriented Programming (OOP), File I/O, Data Structures, Input Formatting

## 📁 Project Structure

```text
├── main.cpp              # Interactive menu and user input handling
├── LaborTracker.h        # Core class logic, file I/O, and summary analytics
└── README.md             # Project documentation
