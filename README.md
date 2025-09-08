# Track-It

**Track-It** is a Java-based web application designed to help users manage personal finances efficiently. It allows users to track income, expenses, and budgets with an intuitive interface and modular backend.

---

## ✨ Features

- **User Management** – Registration, authentication, and user profile handling.
- **Transaction Tracking** – Log income and expenses with categorization.
- **Budget Management** – Create budgets per category and monitor spending limits.
- **Reports & Insights** – Generate monthly spending summaries using the Strategy Design Pattern.
- **Observer Notifications** – Get alerts when spending approaches or exceeds budgets.
- **Modular Design** – Built with controllers, models, services, factories, and strategies for easy maintainability.
- **Spring Boot + Maven** – Simple build and run workflow.
- **Thymeleaf Frontend** – Responsive HTML templates for a smooth user experience.

---

## 📂 Project Structure

```text
Track-It/
├── src/
│   ├── main/
│   │   ├── java/com/example/budgettracker/
│   │   │   ├── controllers/       # User, Transaction, Budget controllers
│   │   │   ├── models/            # Entities like Transaction, User, Budget
│   │   │   ├── observers/         # Budget alert observers
│   │   │   ├── strategies/        # Reporting strategies
│   │   │   └── services/          # Business logic and transaction handling
│   │   └── resources/templates/   # Thymeleaf templates for UI
├── data/                          # Sample CSV data
├── pom.xml                        # Maven build configuration
└── README.md
