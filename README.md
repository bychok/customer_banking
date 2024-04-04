# Banking System Project

# Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

This Banking System project is designed to simulate basic banking operations. It supports creating savings and certificate of deposit (CD) accounts, calculating interest, and updating account balances. This Python-based system is easy to use and demonstrates fundamental programming concepts such as class inheritance, encapsulation, and polymorphism.

## Features

- **Create Savings Account**: Users can create a savings account with an initial balance and interest rate.
- **Create CD Account**: Users can create a CD account specifying the balance, interest rate, and the term in months.
- **Interest Calculation**: The system calculates the interest earned for the specified term and updates the account balances accordingly.
- **User Interaction**: Through a command-line interface, users can input account details and receive feedback on account balances and interest earned.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6 or higher installed on your system.

## Installation

Clone the project repository to your local machine:

```bash
git clone https://github.com/your-username/your-project-name.git
cd your-project-name
```

No additional installation is required as the project runs on Python's standard library.

## Usage

To run the banking system, navigate to the project directory and execute:

```bash
python customer_banking.py
```

Follow the on-screen prompts to enter details for savings and CD accounts. The system will calculate and display the interest earned and the updated balances.

## Project Structure

- **Accounts.py:** Defines the Account base class with methods for setting the balance and interest.
- **savings_account.py:** Contains functionality to create a savings account and calculate interest.
- **cd_account.py:** Implements the logic for creating a CD account and calculating interest over a specified term.
- **customer_banking.py:** The main script that users interact with to create accounts and view updated balances.

## Contributing

Contributions to the Banking System project are welcome. If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
