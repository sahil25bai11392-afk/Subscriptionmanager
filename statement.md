# 📄 Project Statement: Basic Subscription Manager 

## 🎯 Problem Statement

Individuals increasingly struggle to maintain an accurate, consolidated view of their total monthly expenditure on recurring subscription services (e.g., streaming, software, content). This lack of visibility can lead to overspending or budgeting errors. The problem addressed by this project is the need for a simple, interactive program that can **capture multiple subscription names and their costs**, store this transactional data, and **calculate the definitive total monthly financial commitment**.

---

## 🧭 Scope of the Project

The scope of the Basic Subscription Manager is intentionally **narrow and foundational**, focusing on core programming concepts.

* **Inclusions (What is included):**
    * Command-Line Interface (CLI) input for subscription name and cost.
    * Basic **data storage in an in-memory Python list**.
    * Input validation for cost (must be a non-negative number).
    * Calculation and display of the aggregate total monthly cost.
    * Formatted output of the final summary.

* **Exclusions (What is excluded):**
    * **Data Persistence:** The data is lost once the program terminates (no file or database storage).
    * Advanced CRUD operations (Update or Delete functionality).
    * User authentication or multiple user profiles.
    * Currency conversion or annual cost calculations.
    * Graphical User Interface (GUI).

---

## 👥 Target Users

The primary target user for this application is:

* **Students and Novice Programmers:** As a learning tool to understand fundamental data structures, input/output operations, and error handling in Python.
* **Individuals Needing Quick Cost Aggregation:** Any user who requires a simple, temporary calculation of their monthly subscription commitments without needing a complex, persistent application.

---

## ✨ High-Level Features

1.  **Subscription Data Entry (FR1, FR2):** Allows for the sequential input of subscription **Name** and **Cost**.
2.  **Robust Input Validation (NFR2, NFR3):** Utilizes `try...except` and conditional logic to prevent the entry of invalid text or negative numbers for cost.
3.  **In-Memory Storage (FR3):** Uses the core Python **list** data structure to temporarily hold all entered subscription records.
4.  **Total Cost Aggregation (FR5):** Efficiently iterates through the stored data to calculate and accumulate the final **Total Monthly Cost**.
5.  **Summary Display (FR6, FR7):** Presents a clear, formatted summary showing the list of entered items and the final aggregated cost.
