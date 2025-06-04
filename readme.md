# Sales Invoice Generator (SIG)

## 📌 Project Overview

The **Sales Invoice Generator (SIG)** is a Java-based desktop application designed to help businesses generate, manage, and retain sales invoices efficiently. It enables users to create, view, update, and delete invoices, while keeping track of invoice items and totals. This tool is especially useful for small to medium-sized businesses for streamlined accounting and record-keeping.

---

## 🧠 Key Features

- **Invoice Preview Table**: Displays a summary of all invoices with fields such as Invoice No., Date, Customer Name, and Total Amount.
- **Detailed Invoice View**: Shows selected invoice details including individual line items (description, quantity, price).
- **Create & Delete Invoices**: Users can add new invoices or remove existing ones via intuitive buttons.
- **Edit & Save Functionality**: Users can modify invoice details and either save or cancel changes.
- **File Operations**:
  - **Save File**: Saves the latest state of invoices to a file.
  - **Load File**: Loads previously saved invoice data from a file.
- **Initial Invoice Loading**: Automatically loads pre-existing invoice data from CSV files on startup.
- **User-Friendly GUI**: Adheres to a provided design layout for consistency and usability.

---

## 🛠️ Technologies Used

- **Programming Language**: Java
- **GUI Framework**: Java Swing
- **File I/O**: CSV reading and writing
- **IDE**: [Your IDE, e.g., IntelliJ IDEA, Eclipse]
- **Data Storage**: Local file system (CSV files)

---

## 📂 File Structure

- `InvoiceHeader.csv`: Stores metadata of invoices (Invoice No., Date, Customer Name)
- `InvoiceLine.csv`: Stores line-item details for each invoice (Item Name, Count, Price)

## 📘 What I Learned

Through developing the Sales Invoice Generator, I gained practical experience in:

- **Object-Oriented Programming (OOP)**: Designed structured classes for `Invoice`, `InvoiceLine`, and data models.
- **GUI Development**: Created responsive desktop interfaces using **Java Swing**, including layouts, event listeners, and forms.
- **Data Management**: Implemented reading and writing operations for CSV files to simulate persistent storage.
- **MVC Architecture**: Structured the application using a clear Model-View-Controller pattern to separate concerns.
- **Event-Driven Programming**: Handled user actions via listeners and dynamic UI updates.
- **Error Handling & Validation**: Ensured robust handling of file operations, invalid inputs, and user interactions.
- **Project Planning**: Understood requirement analysis and UI alignment to functional specifications.

---

## 📄 License

This project is open for educational and personal use. For other use cases, please contact the developer.
