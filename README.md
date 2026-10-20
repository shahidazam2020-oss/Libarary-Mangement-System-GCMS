# 📚 Library Management System (GCMS)

## 📌 Project Overview

The **Library Management System (GCMS)** is a database-driven application developed using **Microsoft Access** to manage and organize the daily operations of a library. The system provides a structured way to maintain information about books, authors, categories, library members, staff, and book issuing/returning activities.

The system is designed to reduce manual record-keeping, improve data organization, and make it easier for library staff to search, update, and generate reports from library records.

---

## 🎯 Purpose of the Project

**The main purpose of this project is to provide an efficient database system for managing library resources and transactions.**

**It helps library staff to:**

* Manage book collections
* Store author information
* Organize books according to categories
* Register and manage library members
* Maintain staff information
* Record book issuing transactions
* Record book return dates
* Calculate/manage fines
* Search and analyze library records
* Generate useful library reports

---

## 🗂️ Main Database Components

**The system contains several interconnected tables for storing and managing library information.**

### 📖 Book Collection

The **BookCollection** table stores information about books available in the library, including:

* Book ID
* Book Name
* Author ID
* Category ID
* Purchase Price
* Number of Pages

This allows the library to maintain a complete inventory of its books.

### ✍️ Author Data

The **AuthorData** table maintains information about book authors, including:

* Author ID
* Author Name
* Country
* Life Status
* Monthly Income

The author information is connected with the books in the collection.

### 🏷️ Category Management

The **Category** table organizes books into different categories.

It contains:

* Category ID
* Category Name

This makes it easier to classify and search for books.

### 👥 Library Members

The **LibraryMember** table maintains information about people registered with the library, including member identification and membership information.

It contains fields such as:

* Member ID
* Membership Date
* Name
* Address
* Phone

### 👨‍💼 Staff Management

The **StaffPErsonnal** table stores information about library staff members, including:

* Staff ID
* Staff Name
* Address
* Phone
* Appointment Date

This information can also be associated with book issuing transactions.

### 📚 Book Issue & Return

The **BookIssue** table manages book circulation and records transactions when books are issued to members.

Important fields include:

* Issue Number
* Book ID
* Member ID
* Staff ID
* Issue Date
* Return Date
* Fine

This component allows the library to track which member has borrowed a particular book and when it should be returned.

---

## 📊 Reports

The system includes several predefined reports that can help library management analyze its records.

Examples include:

* **Book Issue Between Desired Period**
* **Book Issue by Desired Category**
* **Book Issue by Desired Authors**
* **Book Issue After 30 June 2018**
* **Book Issued by Staff**
* **Member Issued Books**
* **Book Issue by Category**
* **Book Issue by Authors**
* **Category Wise Books**
* **Author Wise Books**

These reports make it easier to obtain useful information without manually searching through database records.

---

## 🖥️ Forms

The project also includes Microsoft Access forms that provide a user-friendly interface for entering and managing information.

Available forms include:

* **Book Issue Form**
* **Book Collection Form**
* **Library Member Form**
* **Book Category Form**
* **Staff Personnel Form**
* **Author Data Form**

These forms allow users to add, update, and manage database records efficiently.

---

## 🔗 Database Relationships

The database uses relationships between its tables to maintain organized and consistent data.

The major relationships include:

```text
AuthorData
     │
     └── BookCollection
              │
              ├── Category
              │
              └── BookIssue
                       ├── LibraryMember
                       └── StaffPErsonnal
```

For example, a book can be associated with an author and category, while a book issue transaction connects the book with a library member and the staff member who processed the transaction.

---

## ⚙️ Software & Technologies

* **Microsoft Access**
* **Microsoft Access Database (.accdb)**
* **Relational Database Design**
* **Tables**
* **Forms**
* **Queries**
* **Reports**
* **Database Relationships**

---

## 💡 Use of the Software

This software can be used by:

* 📚 **Libraries** to manage their book collections
* 👨‍💼 **Librarians** to manage issuing and returning books
* 👥 **Library staff** to maintain member records
* 🏫 **Schools and colleges** to manage academic libraries
* 🎓 **Universities** to organize library resources
* 🏢 **Small organizations** that require a basic library database

The system is particularly useful for libraries that want to replace manual registers or spreadsheets with a structured database solution.

---

## ⭐ Key Features

* ✅ Book inventory management
* ✅ Author management
* ✅ Category management
* ✅ Member registration
* ✅ Staff management
* ✅ Book issuing management
* ✅ Book return tracking
* ✅ Fine management
* ✅ Multiple database forms
* ✅ Predefined reports
* ✅ Relational database structure
* ✅ Organized and searchable records

---

## 📁 Project File

The main database file is:

```text
LibararyMangementSystem GCMS.accdb
```

> **Note:** The filename contains the spelling `LibararyMangementSystem`; this is retained from the original project file.

---

## 🚀 How to Use

1. Install **Microsoft Access**.
2. Download or clone this repository.
3. Open the `.accdb` database file using Microsoft Access.
4. Open the available forms to manage library data.
5. Add or update books, authors, categories, members, and staff.
6. Use the **Book Issue Form** to record book transactions.
7. Use the available reports to analyze library records.

---

## 🎓 Project Objective

This project demonstrates the practical implementation of a **relational database management system** using Microsoft Access. It focuses on database design, relationships, data management, forms, queries, and reporting to provide a complete solution for basic library management.

---

## 👨‍💻 Author

**Shahid Azam**

This project was developed as a database management project demonstrating practical skills in **Microsoft Access, relational databases, data organization, forms, queries, and reporting**.
