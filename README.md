🍽️ Cravings – Restaurant Billing System (Mini Project)
This is a C++ console-based mini project simulating a restaurant billing system named "CRAVINGS". It allows users to place food orders from various menu categories, generates an itemized bill with GST, and saves the bill to a text file. It also features customer detail collection and dynamic color-coded terminal output (Windows only).

🎯 Key Features
🧾 Complete Billing System

Menu-driven food ordering experience

Multiple food categories: Beverages, Appetizers, Main Course, Dessert, Fast Food

Auto-calculates subtotal, GST (2.5%), and total bill

Stores order summary with customer details into a .txt file

🧍‍♂️ Customer Interaction

Input customer name, contact number, and delivery address

View current order anytime before finalizing

💾 Bill Export

Bill file saved with timestamped filename (e.g., Bill_20250712_1025.txt)

🎨 Colored Console Output

Uses windows.h to enhance user experience via terminal colors:

Cyan for titles & headers

Green for successful actions

Red for warnings or errors

Yellow for menus

📸 Example Output
markdown
Copy
Edit
~~~~~~~~~~~~~~~~~ MAIN MENU ~~~~~~~~~~~~~~~~~

1. Beverages 
2. Appetizer 
3. Main Course 
4. Dessert 
5. Fast Food 
6. View Current Order
7. Exit & Generate Bill

Choose category: 
🧠 Concepts Covered
Object-Oriented Programming (OOP) in C++

Inheritance and classes (BillSystem, Beverage, etc.)

Operator overloading (+ to calculate total)

File Handling (<fstream>)

Use of <ctime> for timestamps

Dynamic console color using Windows API

Use of <iomanip> for neat formatting

Clean class-based menu design

💻 Technologies Used
Language: C++

Platform: Windows (required for windows.h)

Compiler: Tested on GCC / MSVC

Tools: VS Code, Dev-C++, Code::Blocks (optional)

✅ Future Enhancements (Ideas)
Add admin login for restaurant owners

Save all orders to a central file/database

Add discount or promo code feature

Print bill in receipt format
