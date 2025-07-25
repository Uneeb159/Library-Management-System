# 📚 Library Management System (LMS)

A fully documented and structured **Library Management System** designed to streamline library operations such as book issuance, returns, reservations, fine handling, and user management. Built as part of a university ISE project, this system demonstrates a complete software development lifecycle including use case modeling, UML, DFDs, testing, and more.

---

## 🚀 Project Overview

The objective of the LMS is to digitize and automate traditional library processes for smoother operations, better book/resource tracking, and improved user experience.

### ✅ Key Features

- 🔐 **User Authentication** (Login/Register with Library Card ID)
- 📖 **Book Management** (Add, Remove, Update books)
- 🔍 **Search Functionality** (by title, author, ISBN, category)
- 📦 **Book Issuing and Returning**
- ⏰ **Late Return Fine Calculation**
- 📅 **Book Reservations**
- 📩 **Email/Notification Alerts** (Due dates, returns, availability)
- 👥 **Role-Based Access Control** (Admin, Librarian, Member)
- 🗂️ **Borrowing History Tracking**
- 💬 **User Feedback Collection**

---

## 👥 Target Users

- **Students / Library Members**
- **Librarians** (staff for daily operations)
- **Administrators** (system controllers)

---

## 🛠 Functional Requirements Summary

| #  | Requirement                                         |
|----|-----------------------------------------------------|
| 1  | Secure login and registration with credentials      |
| 2  | Admins can add/remove/update books                  |
| 3  | Search books by multiple parameters                 |
| 4  | Issue and return books                              |
| 5  | Fine calculation for late returns                   |
| 6  | Reserve books if not currently available            |
| 7  | Notifications for due dates and reservations        |
| 8  | Role management with specific permissions           |
| 9  | View borrowing history                              |
| 10 | Handle multiple user roles simultaneously           |

---

## 🧪 Testing Strategy

- **Unit Testing** (login, borrowBook, etc.)
- **Integration Testing** (e.g., login + borrow flow)
- **System Testing** (entire system flow)
- **Acceptance Testing** (end-user validation)

### ✅ Sample Test Cases

| Test Case ID | Description                     | Input                          | Expected Output                     | Status |
|--------------|---------------------------------|----------------------------------|--------------------------------------|--------|
| TC-01        | Valid login                     | Valid username/password         | Dashboard appears                   | ✅ Pass |
| TC-05        | Issue available book            | Book ID + User ID               | Book issued, status updated         | ✅ Pass |
| TC-07        | Return late book                | Book ID + 5 days late           | Fine calculated and notified        | ✅ Pass |
| TC-10        | Due date reminder notification  | Book due today                  | Email/alert sent to user            | ✅ Pass |

---

## 🔧 System Design & Diagrams

- **Use Case Diagram**  
- **Class Diagram (UML)**  
- **Sequence Diagram** (Member borrows book scenario)  
- **Activity Diagram** (Borrow/reserve process flow)  
- **Data Flow Diagrams (Context, Level-0, Level-1)**

---

## 📐 Object-Oriented Model

- **Inheritance**: `Member`, `Librarian`, `Admin` ⬅ `User`
- **Aggregation**: `BorrowRecord` ↔ `Fine`
- **Composition**: `BorrowRecord` ↔ `Book`, `Member`
- **Classes**: `Book`, `User`, `Reservation`, `Feedback`, `Notification`, `Fine`, etc.

---

## 💡 Future Enhancements

- 📶 **RFID integration** for automated tracking
- 📱 **Mobile app** version for students
- 📊 **Admin dashboards** for real-time analytics
- 🌐 **Multi-language support**
- 🔄 **Continuous integration and testing pipelines**

---

## 📅 Project Details

- 👤 **Student:** Muhammad Uneeb Khan  
- 🏫 **Institution:** Air University, Multan  
- 📚 **Semester:** 2nd  
- 👩‍🏫 **Instructor:** Ms. Fatima Yousaf  
- 🗓️ **Submitted:** June 15, 2025  

---

## 📄 License

This project is built for academic purposes. Feel free to fork and enhance it for educational or non-commercial use.

---

