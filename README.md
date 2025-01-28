# BudgetBuddy

**BudgetBuddy** is a smart expense tracker app designed to help users manage their finances, track spending, and maintain a budget effortlessly. With an intuitive interface and powerful features, BudgetBuddy makes financial planning accessible and straightforward for everyone.

---

## Features

- **Track Expenses**: Record and categorize daily expenses in a few taps.
- **Budget Management**: Set monthly or custom budgets to monitor your spending.
- **Custom Date Filters**: View spending insights for specific time periods.
- **Analytics Dashboard**: Visualize your expenses with charts and graphs.
- **Multi-Currency Support**: Track expenses in your preferred currency.
- **Data Security**: Keep your financial data safe and secure.
- **User-Friendly Interface**: Designed for simplicity and ease of use.

---

## Tech Stack

- **Frontend**: React.js, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

---

## API Endpoints

### 1. Fetch Transactions
**GET** `/api/transactions`
- **Description**: Retrieve all transactions based on user preferences.
- **Request Body**:
  ```json
  {
    "frequency": "7",
    "selectedDate": ["2025-01-01", "2025-01-10"],
    "userid": "12345",
    "type": "expense"
  }
  ```

### 2. Add a Transaction
**POST** `/api/transactions`
- **Description**: Add a new expense or income transaction.
- **Request Body**:
  ```json
  {
    "amount": 100,
    "type": "expense",
    "category": "Food",
    "date": "2025-01-25",
    "userid": "12345"
  }
  ```

### 3. Delete a Transaction
**DELETE** `/api/transactions/:id`
- **Description**: Remove a specific transaction by its ID.

---




---

## Contributing

We welcome contributions to enhance BudgetBuddy! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.

---

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## Contact

For any queries or suggestions, reach out to:
- **Email**: [shobhitsinha231@gmail.com](mailto:shobhitsinha231@gmail.com)


---

**Happy Tracking with BudgetBuddy!**

