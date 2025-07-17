🏦 Bank Management System (ATM Machine)
=======================================

✨ Introduction
--------------

The **Bank Management System (ATM Machine)** is a **Java-based** application that simulates basic banking operations through an **ATM-like interface**. Users can perform essential transactions such as **PIN change, cash withdrawal, deposits, balance inquiry**, and more.

The application is built using **Java Swing** for a graphical user interface and **JDBC** for secure database connectivity.

💳 Features
-----------

*   ➕ **Deposit**: Add money to your bank account.
*   ➖ **Cash Withdrawal**: Withdraw money from your account.
*   ⏫ **Fast Cash**: Quick withdrawal of pre-defined amounts.
*   📈 **Balance Inquiry**: Check your current account balance.
*   📝 **Mini Statement**: View a summary of recent transactions.
*   🔑 **PIN Change**: Securely update your ATM PIN.
*   ❌ **Exit**: Safely log out of the application.
    

💻 Technologies Used
--------------------

*   **Programming Language**: Java
*   **GUI Framework**: Swing (Java)
*   **Database**: MySQL
*   **Database Connectivity**: JDBC
*   **IDE**: IntelliJ IDEA / Eclipse / NetBeans (or any Java IDE)
📚 Database Structure
---------------------

The project uses the following tables:

### **1\. ```bank``` Table** (Stores user account details and transactions)
```
   CREATE TABLE bank (     
       account_no INT PRIMARY KEY,     
       name VARCHAR(50),     
       balance DOUBLE,     
       pin VARCHAR(4)  
       );   
```
### **2\. ```login``` Table** (Manages user authentication)
### **3\. ```signupthree``` Table** (Contains user registration details)

💻 How to Use
-------------

1.  **Run the application.**
2.  **Log in** using your account PIN.
3.  **Select** the desired operation from the menu.
4.  **Follow** the on-screen prompts to complete the transaction.
5.  **Log out** when finished by clicking the **Exit** button.

Screenshots
------------
##### **Login Page**:
![image](https://github.com/user-attachments/assets/157a9ab2-c827-46a7-8beb-b5097593ffe5)

##### **SignUpOne**: 
![image](https://github.com/user-attachments/assets/7f986c75-4d0a-4a23-9a40-6a80fe834694)

##### **Main Transactions Menu**:
![image](https://github.com/user-attachments/assets/d4e070d5-2b15-4db3-b6bd-90fd6de99eb1)

##### **PIN Change Interface**:
![image](https://github.com/user-attachments/assets/d349c918-646e-4aa6-8ed1-33596f92e993)

##### **Withdrawl**:
![Screenshot 2025-01-15 153737](https://github.com/user-attachments/assets/02f58ef8-7729-45d4-975b-0c5c4f613bc8)

##### **FastCash**:
![image](https://github.com/user-attachments/assets/2a8dd60d-27f2-46c2-a75f-5f1d4ab4ce49)

🚀 Future Enhancements
----------------------

*   ✅ **Multi-User Support**: Implement unique account numbers for multiple users.
    
*   🔒 **OTP Verification**: Add an extra layer of security during login and transactions.
    
*   🎨 **Enhanced GUI**: Upgrade the user interface for a more **modern and intuitive** experience.
    
📞 Contact
----------

For any queries or suggestions, feel free to reach out:

*   **👤 Name:** Devangi Inani
*   📧 **Email:** devangiinani@gmail.com
*   💻 **GitHub:** [Devangi Inani](https://github.com/devangi2004)
*   🔗 **LinkedIn:** [Devangi Inani](https://www.linkedin.com/in/devangi-inani-8b92b9282/)
