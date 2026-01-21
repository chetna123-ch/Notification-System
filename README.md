#  Notification System (C++)

## 📌 Overview

This project demonstrates a **Factory Design Pattern** implementation in **C++** to build a flexible and extensible **Notification System**. The system supports multiple notification channels like **Email**, **SMS**, and **Push Notifications** without changing the core business logic.

The design follows **SOLID principles**, especially:

* **SRP (Single Responsibility Principle)**
* **OCP (Open Closed Principle)**
* **DIP (Dependency Inversion Principle)**

---

## 🧠 Design Concept

* `Notifier` → Abstract base class (interface)
* `EmailNotifier`, `SMSNotifier`, `PushNotifier` → Concrete implementations
* `NotifierFactory` → Responsible for object creation
* `main()` → Client code, fully decoupled from concrete classes

This ensures **loose coupling** and **high scalability**.

---

## ⚙️ Technologies Used

* **Language:** C++
* **Concepts:**

  * OOP (Inheritance, Polymorphism)
  * Factory Design Pattern
  * Smart Pointers (`std::unique_ptr`)
  * Exception Handling

---

## 📂 Project Structure

```
NotifierFactory/
│── main.cpp
│── README.md
```

---

## ▶️ How It Works

1. User selects notification type: `email`, `sms`, or `push`
2. User enters a message
3. `NotifierFactory` creates the required notifier object
4. Message is sent using polymorphism

---

## 🧪 Sample Input / Output

```
Enter notification type (email/sms/push) or 'quit': email
Enter message: Welcome to Factory Pattern
[Email] Sending: Welcome to Factory Pattern
```

---

## 🚀 Benefits of This Approach

* Easy to add new notification types
* No modification in existing logic
* Clean, readable, and maintainable code
* Industry-standard design pattern usage

---

## 🔮 Future Enhancements

* Add WhatsApp / Slack notifier
* Use configuration-based factory
* Integrate real APIs
* Apply Abstract Factory Pattern

---

## 📌 Learning Outcome

This project is ideal for:

* Understanding **Factory Pattern**
* Practicing **SOLID principles**
* Interview & LLD preparation

---

## 👩‍💻 Author

**Chetna Gehlot**
B.Tech Student | C++ | DSA | System Design | AIML Aspirant

---

⭐ If you like this project, don’t forget to **star the repo**!

