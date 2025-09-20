# Stock-Simulator
This project is a fully self-built stock market simulator developed in C# to demonstrate my understanding of object-oriented programming, modular architecture, and financial logic. It simulates real-world trading behavior, allowing users to manage virtual portfolios, execute trades, and observe dynamic price movements — all within a clean, layered codebase and without a user interface.

🔧 Technologies & Concepts

C# (.NET Core)

Object-Oriented Programming (OOP)

Data Structures (List, Dictionary)

Randomised price simulation logic

Layered architecture: Models, Services, Data Layer

Console-based execution (no UI)

💼 Why This Project Matters

Built entirely from scratch to strengthen my software development fundamentals

Demonstrates ability to design and implement scalable, maintainable systems

Highlights problem-solving skills through custom trading logic and simulation

Serves as a foundation for future enhancements like file persistence, analytics, or UI integration

📚 Key Features

Simulates stock price changes using random walk logic

Enables buying and selling of stocks with cash balance tracking

Tracks user holdings and transaction history

Calculates portfolio value and performance metrics

Clean separation of concerns for maintainability and scalability



## 🏗️ Architecture

The project follows a layered architecture:

| Layer        | Purpose                                                                 |
|--------------|-------------------------------------------------------------------------|
| **Models**   | Define core data structures: `Stock`, `Portfolio`, `Transaction`        |
| **Services** | Handle business logic: price simulation, trading, analytics             |
| **Data Layer** | Provide mock data and future file/database integration                |

---

## 🔧 Technologies Used

- C# (.NET Core )
- Console Application (no UI layer)
- `List<T>`, `Dictionary<TKey, TValue>`
- `Random`, `DateTime`, `Math`
- Clean code principles and modular design

---

## 📚 Features

- Simulates dynamic stock price changes using random walk logic
- Allows buying and selling of stocks with cash balance tracking
- Tracks user holdings and transaction history
- Calculates portfolio value and performance metrics
- Fully modular and extensible for future upgrades

---

## 📁 Folder Structure

StockSimulator/ ├── Models/ │ ├── Stock.cs │ ├── Portfolio.cs │ └── Transaction.cs ├── Services/ │ ├── MarketService.cs │ └── TradingService.cs ├── Data/ │ └── DataStore.cs └── Program.cs
