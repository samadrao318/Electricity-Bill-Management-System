# Electricity Bill Management System

## Project Description
This is a simple Python-based Electricity Bill Management System.  
It allows you to:
- Add new users with their CNIC and units consumed.
- Show all users and their bills.
- Search for a user by CNIC.
- Delete a user.
- Show total revenue collected.

The system calculates bills based on units consumed and ensures that each CNIC is unique.

---

## Project Output

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Electricity Bill Management System</title>
    <style>
        body {
            font-family: monospace;
            background-color: #f5f5f5;
            padding: 20px;
        }
        h1 {
            text-align: center;
        }
        pre {
            background-color: #222;
            color: #0f0;
            padding: 20px;
            border-radius: 8px;
            overflow-x: auto;
        }
    </style>
</head>
<body>

<h1>Electricity Bill Management System</h1>

<h2>Project Output:</h2>
<pre>
========================================
Electricity Bill Management System
========================================
1. Add New User
2. Show All Users & Bills
3. Search User by CNIC
4. Delete User
5. Show Total Revenue
6. Exit
Enter your choice (1-6):  1
===== ADD NEW USER =====
Enter User Name :  afnan
Enter your cnic (xxxx-xxxxxxx-x) 37428-3431231-3
Enter useable unit : 400

 User Successfully Added.

========================================
Electricity Bill Management System
========================================
1. Add New User
2. Show All Users & Bills
3. Search User by CNIC
4. Delete User
5. Show Total Revenue
6. Exit
Enter your choice (1-6):  2
=== Show All User Data ===

name            cnic                 units           bill
----------------------------------------------------------------------
1 : afnan           35101-3701956-7      400             10000PKR
2 : afnan           37428-3431231-3      400             10000PKR

========================================
Electricity Bill Management System
========================================
1. Add New User
2. Show All Users & Bills
3. Search User by CNIC
4. Delete User
5. Show Total Revenue
6. Exit
Enter your choice (1-6):  afnan
Invalid choice. Please enter a number between 1 and 6.

========================================
Electricity Bill Management System
========================================
1. Add New User
2. Show All Users & Bills
3. Search User by CNIC
4. Delete User
5. Show Total Revenue
6. Exit
Enter your choice (1-6):  35101-3701956-7
Invalid choice. Please enter a number between 1 and 6.

========================================
Electricity Bill Management System
========================================
1. Add New User
2. Show All Users & Bills
3. Search User by CNIC
4. Delete User
5. Show Total Revenue
6. Exit
Enter your choice (1-6):  1
===== ADD NEW USER =====
Enter User Name :  afnan
Enter your cnic (xxxx-xxxxxxx-x) 35101-3701956-7
user already exist

========================================
Electricity Bill Management System
========================================
1. Add New User
2. Show All Users & Bills
3. Search User by CNIC
4. Delete User
5. Show Total Revenue
6. Exit
</pre>

</body>
</html>
