# Bill Management System

A comprehensive **Bill Management System** built using Python and Tkinter. This application helps users manage bills by adding items, calculating totals, saving bill data to an Excel spreadsheet, and allowing easy retrieval of past bills.

---

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [File Structure](#file-structure)
- [License](#license)


---

## Features

- **Add Customer Details**: Input customer name and phone number.
- **Add Items**: Add item details such as name, price, and quantity.
- **Dynamic Calculations**: Automatically calculates the total price, tax (5%), and final total.
- **Save to Excel**: All bill data is stored in an Excel file (`bills.xlsx`).
- **Search Bills**: Retrieve past bills using their bill number.
- **Print Bills**: View the bill in a printable format in a separate window.
- **Clear and Reset**: Quickly reset the interface to create a new bill.

---

## Requirements

Make sure you have the following installed:

- Python 3.6 or later
- The following Python libraries:
  - `tkinter` (comes pre-installed with Python)
  - `openpyxl` (for Excel operations)

Install `openpyxl` via pip if not already installed:
```bash
pip install openpyxl
```

## Installation

Clone the Repository:

```bash

git clone https://github.com/yourusername/bill-management-system.git
cd bill-management-system
```

Create a Virtual Environment:

```bash
python -m venv env
```

Install Required Libraries:

```bash
pip install -r requirements.txt
```
Run the Application:

```bash
python bill_management_system.py
```

# Usage

- **Launch the application by running python bill_management_system.py.**
- **Enter Customer Details:** Add the customer's name and phone number.
- **Add Items:** Specify the item's name, price, and quantity. Click "Add Item" to add it to the bill.
- **View Calculations:** Total price, tax, and final total are calculated automatically.
- **Save the Bill:** Bill data is saved to an Excel file (bills.xlsx).
- **Search for Bills:** Use the bill number to retrieve past bills.
- **Print the Bill:** Open a printable version of the bill in a separate window.
- **Clear Data:** Reset the application to prepare for a new bill.

# Screenshots
![Image](https://github.com/user-attachments/assets/789759c0-3f53-4ed6-aff7-486063b04847)
![Image](https://github.com/user-attachments/assets/72f20eee-9fd7-44a6-8917-a10de2999d6b)
![Image](https://github.com/user-attachments/assets/9bce1986-c541-40be-a290-570046137cbb)
![Image](https://github.com/user-attachments/assets/839cac31-3c91-4e12-baa7-afc8cb95443d)

# File Structure
- **bill_management_system.py:** Main application script.
- **bills.xlsx:** Generated Excel file to store bill data.

# License
- This project is licensed under the MIT License. See the LICENSE file for details.
