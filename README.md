# GetsBan Banking Management System

## Overview

GetsBan is a simple console-based banking management system implemented in C. It provides basic banking operations such as client management, account creation, transactions, and data persistence. This project is designed to demonstrate fundamental programming concepts in C, including structs, file I/O, and basic security implementations.

## Features

- Client Management
  - Add new clients
  - Display client details
  - Delete clients
- Account Management
  - Create new accounts for existing clients
  - Display account details
  - Delete accounts
- Transaction Handling
  - Perform deposits and withdrawals
  - Display transaction history
- Data Persistence
  - Save all data to a binary file
  - Load data from the binary file
- Basic Security
  - Password protection for client actions
  - Limited login attempts

## Prerequisites

To compile and run this project, you need:

- A C compiler (e.g., GCC)
- Standard C libraries

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/YSN-B13/GetsBan.git
   ```
2. Navigate to the project directory:
   ```
   cd GetsBan
   ```
3. Compile the project:
   ```
   gcc -o GetsBan GetsBan.c
   ```

## Usage

Run the compiled program:

```
./getsban
```

Follow the on-screen menu to navigate through different banking operations.

## File Structure

- `GetsBan.c`: Main program file containing the menu system and program flow.
- `Getsban.h`: Header file containing function declarations, struct definitions, and global variables.
- `bank_data.bin`: Binary file for data persistence (created when you save data).

## Contributing

Contributions to improve GetsBan are welcome. Please feel free to fork the repository, make changes, and submit a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Disclaimer

This is a basic implementation for educational purposes and should not be used for actual banking operations without significant enhancements in security and reliability.
