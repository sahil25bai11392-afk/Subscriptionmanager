# Subscription manager
vityarthi project
# Basic Subscription Manager (List Version)

## 💡 Overview of the Project

The Basic Subscription Manager is a simple, command-line utility built in Python designed to help users track and manage their recurring monthly subscription expenses. This application prompts the user to input the name and cost of multiple services, stores this data in an **in-memory list**, and then calculates and displays the **aggregated total monthly cost**.

It serves as a fundamental example of input/output (I/O) handling, basic data storage using Python lists, and robust input validation using `try...except` logic.

## ✨ Features

* **Interactive Input:** Guides the user through entering subscription names and costs.
* **Cost Validation:** Ensures that all cost inputs are **valid numbers** and are **non-negative**.
* **Case-Insensitive Exit:** Recognizes the `done` command regardless of casing (e.g., 'Done', 'done', 'DONE').
* **Total Aggregation:** Calculates the **sum** of all entered monthly costs.
* **Formatted Output:** Displays individual subscription costs and the final total cost formatted to two decimal places (e.g., $19.99).

## 🛠️ Technologies/Tools Used

* **Language:** Python 3.x
* **Data Structure:** Python List (used as a list of lists: `[[name, cost], [name, cost], ...]`)
* **Environment:** Any standard command-line interface (CLI) or IDE environment capable of running Python scripts.

## 🚀 Steps to Install & Run the Project

Since this is a single Python script with no external dependencies, installation is straightforward.

### 1. Save the Code

Save the provided Python code into a file named `subscription_manager_list.py`.

### 2. Run the Script

Open your command-line interface (e.g., Terminal, Command Prompt, PowerShell) and navigate to the directory where you saved the file. Execute the script using the following command:

```bash
python subscription_manager_list.py
