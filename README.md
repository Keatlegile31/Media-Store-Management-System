# Media Store Management System (C#)

This is a simple console-based media store management system developed in **C#** as part of a university assignment. The application manages records for Books, CDs, and DVDs. 

To go beyond the basic requirements, a **password authentication system** was implemented to restrict access to the application.

## 🔐 Features
- 🔑 Password-protected access to the media store  
- 📚 Add, view, and delete media items (Books, CDs, DVDs)  
- 🧭 Simple, menu-driven user interface  
- 🗃️ Data management using `List<T>` collections  
- 🚫 Input validation and exception handling

## 🛠 Technologies Used
- C# 
- Console application
- Object-Oriented Programming (OOP)

## 📂 How It Works
1. When the program runs, the user has the option to choose to be a regular user or an admin .
2. If admin is seleted then the admin is prompted to enter a password to access the system.
3. Upon successful login, the admin can:
   - Add a new Book, CD, or DVD
   - View all stored items by type
   - Delete items
4. All data is stored in memory using lists.
5. If user is selected then user can:
    - Add books, CDs or DVDs to cart and checks out.
    - Discounts and coupons are applied depending on how long they have been a customer.
7. The app runs in a loop until the user chooses to exit.

## 🧠 Concepts Applied
- ✅ Object-Oriented Programming
- ✅ Lists and collections
- ✅ Input validation
- ✅ Authentication logic
- ✅ Modular code structure

