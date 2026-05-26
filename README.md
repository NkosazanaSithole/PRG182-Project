# PRG182-Project
PRG182 Project Milestone 2 - Group 6
–––––––––––––––––––––––––––––––––––––
Shared Budget Tracker application
This is a C# console application designed to help university students living together keep track of their shared expenses and income. It gives housemates a simple menu interface to log transactions, categorize spending, and check financial summaries so everyone stays on top of the budget.

Features:
> Record Transactions: Log income or expenses and link them to a specific user and category.  
> Financial Summary: View a quick breakdown of total income, total expenses, and the remaining net balance.  
> Filter Data: Check accumulated totals broken down by a specific category (e.g., Rent, Groceries, WiFi) or a specific user.  
> Input Validation: Includes custom helper functions (ReadInt and ReadDouble) so the program handles typos or incorrect menu choices > without crashing.

How it Works:
> Built using core C# structures: arrays for predefined users/categories, an enum for transaction types, and a list to hold the records.
> Uses a basic while loop to keep the menu active and a switch case to handle user navigation.
> Runs completely in the console with no database configuration or extra setup required.
