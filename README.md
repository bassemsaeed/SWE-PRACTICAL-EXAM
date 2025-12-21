<div align="center">
 
  <img src="assets/o6u-logo.jpeg" alt="O6U Logo" height="200" />
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="assets/cs-logo.png" alt="O6U CS Logo" height="200" />
  
  <br><br>
  <h1>Library Management System</h1>
  <h3>Software Engineering 1 (Practical)</h3>
  
  <p>
    <strong>Under the Supervision of:</strong><br>
    Prof. Ayman Hassanien (د. أيمن حسانين)
  </p>
  
  <p>
    <strong>Technical Assistants:</strong><br>
    Eng. Ahmed Abdelmonem (م. احمد عبد المنعم)<br>
    Eng. Mohamed Abdelmonem (م. محمد عبد المنعم)<br>
    Eng. Nada Hamdy (م. ندى حمدي)
  </p>

  <p><strong>Academic Year:</strong> Egypt 2025/2026</p>
</div>

---

## Team Members

| Student Name | Student ID |
| :--- | :--- |
| **Bassem Said Mahmoud Abdo** (باسم سعيد محمود عبده) | 23015282 |
| **Mahmoud Ragab Saleh Moussa** (محمود رجب صالح موسي) | 23016221 |
| **George Nasser Seif** (جورج ناصر سيف) | 23014881 |
| **Adham Tarek Ahmed Mohamed** (أدهم طارق أحمد محمد) | 23014791 |
| **Hazem Elrefaie Abdullah** (حازم الرفاعي عبدالله) | 23017340 |

---

## Introduction
Egypt has approximately 90 – 100 Universities, famous public libraries, and hosts a dedicated event every year, the “Cairo International Book Fair”. Therefore, Library Management Systems are crucial and essential to act as reliable software to manage all processes related to books, improving efficiency, accessibility, and user experience.

## Problem Definition
**Issues before implementing a Software:**
*   Borrowed and Returned Books Tracking Difficulty.
*   Inconvenience for End-Users as they must go to the library physically to search for and reserve a book.
*   Inefficient Cataloging of Books.
*   High Risk of Human Error.

## Software Definition
The Library Management System should ensure that every actor related to the system can perform all the functions required to ensure a smooth and reliable transaction, recording, addition, reserving, and registering of each book and membership of any actor on the system.

---

## System Requirements

### User Requirements

**1. Member**
*   **Books Actions:** Reserve (with a time limit), Search.
*   **Register/Login:** A reliable and secure login.
*   **Payment:** Accurate calculation of fine and updating of payment.

**2. Librarian**
*   **Books Updates:** Returned, Reserved, Borrowed.
*   **Tracking:** The status of books and membership of those enrolled in certain subscriptions.
*   **Inventory:** Handling the Inventory of Books.

**3. Admin**
*   **Reports:** Generating Reports.
*   **Accounts:** Handling the Accounts of Librarians.
*   **New Arrivals:** Registering New Books and Scanning them on new arrivals.

### Functional Requirements
1.  **Authentication & Membership & Profile:** The system must verify if a student is currently enrolled and eligible for a library card before creating a profile. The system should keep track of historical loans and fines.
2.  **Inventory Management:** Librarians must be able to scan ISBNs to add new titles or update the copy count of existing books. Categorization of books by Authors/Publishers/Subject is a must.
3.  **Borrowing Logic:** The system must validate that a member has no overdue fines and has not exceeded their borrowing limit before issuing a book.
4.  **Returns & Fines:** Upon return, the system must automatically calculate fines based on the return date and update the book status to "Available" or "On Hold" (if reserved).
5.  **Reservation System:** Members should be able to place hold on books that are currently checked out with a time limit of reservation. If the user doesn’t receive the book in the specified time period, the system cancels reservation automatically.
6.  **Search & Discovery:** The automatic calculation of fines based on how many days late and updating the status of every fine whether is paid/unpaid.
7.  **Reports Management:** Creation of Daily Reports and Inventory reports should be done by admins of the system.

### Non-Functional Requirements
1.  **Accuracy:** Financial calculations for fines must be precise.
2.  **Data Integrity:** The system must prevent duplicating member accounts, and the database must not become corrupted in case of system crash.
3.  **Usability:** The interface should provide clear feedback (e.g., "Book Not Found" or "Account Terminated").
4.  **Security and Privacy:**
    *   Authentication where only registered users can log in and only librarians can modify book data.
    *   Member Sensitive Information must be encrypted.
    *   Different actors on system have different access levels.
5.  **Performance:** The response time of search queries must be under 2 seconds and handling different transactions simultaneously should be run smoothly.
6.  **Scalability:** As the library grows in users, books, and employees, the system should be able to withstand this development.
7.  **Reliability & Availability:** The system should be available for most of the library hours.

---

## Diagrams

Per the project requirements, we have created various UML diagrams to visualize the system logic and structure. These files are organized in the following repository folders:

*   **[Activity Diagrams](./diagrams/activity/)**: Workflows for Adding, Borrowing, and Returning books.
*   **[Class Diagram](./diagrams/Class%20Diagram/)**: The static structure of the system classes and attributes.
*   **[Data Flow Diagrams (DFD)](./diagrams/DFD/)**: Visual representations of data processing and flow within the system.
*   **[Use Case & ER Diagrams](./diagrams/USE-Case%26%26ERD/)**: Actor interactions and database entity relationships.

---

<div align="center">
  <p>Submitted to the Faculty of Computer Science</p>
</div>
