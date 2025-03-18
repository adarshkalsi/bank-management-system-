# Bank Management System (ATM Simulator System)

This repository contains a Java-based Bank Management System, also known as the ATM Simulator System. It functions similarly to a normal ATM, allowing users to perform essential banking operations such as account creation, deposits, withdrawals, and PIN changes.

## Features

- **Open Bank Account**: Users can create a new banking account.
- **Deposit Money**: Users can deposit funds into their accounts.
- **Withdraw Money**: Users can withdraw cash from their accounts.
- **Mini Statement**: Users can view a brief summary of recent transactions.
- **PIN Change**: Users can update their ATM PIN for security.

## Technologies Used

- **Programming Language**: Core Java (Swing & AWT)
- **Database**: MySQL
- **IDE**: NetBeans

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- MySQL Server
- NetBeans IDE

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/adarshkalsi/bank-management-system-.git
   cd bank-management-system-
   ```

2. **Import Project into NetBeans**:

   - Open NetBeans IDE
   - Click on `File -> Open Project`
   - Select the cloned repository folder
   - Click `Open`

3. **Set Up the Database**:

   - Open MySQL and create a database:
   
     ```sql
     CREATE DATABASE bank_management;
     ```
   - Import the provided SQL file (if available) to set up the necessary tables.

4. **Run the Application**:

   - In NetBeans, right-click on the project and select `Run`.

## Usage

Upon launching the application, users can:

1. **Create a New Account**: Enter necessary details to create an account.
2. **Deposit Money**: Add funds to an existing account.
3. **Withdraw Money**: Withdraw available balance from an account.
4. **View Mini Statement**: See recent transactions.
5. **Change PIN**: Update security PIN.
6. **Exit**: Close the application.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and create a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/YourFeature`)
3. Commit your Changes (`git commit -m 'Add Your Feature'`)
4. Push to the Branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by real-world ATM systems.
- Thanks to the open-source community for their contributions and support.

---

*Note: This project is for educational purposes and does not represent a real banking system.*
