Python Hotel Management System
A menu-driven, console-based hotel billing application written in Python. This college mini project demonstrates basic object-oriented programming and calculates room rent, restaurant charges, laundry charges, recreation charges, and the final bill.
Features
- Collects customer name, address, check-in date, and check-out date.
- Calculates room rent for four room types.
- Adds restaurant charges based on selected items and quantities.
- Adds laundry charges based on clothing items and quantities.
- Calculates recreational activity charges by hours.
- Displays an itemized bill, subtotal, fixed service charge, and grand total.
- Uses a simple numbered menu for navigation.
Technology Used
- Language: Python 3
- Interface: Command-line / terminal
- External libraries: None
Room Rates
Room type	Rate per night
Type A	Rs 6,000
Type B	Rs 5,000
Type C	Rs 4,000
Type D	Rs 3,000


Restaurant Menu
Item	Price
Water	Rs 20
Tea	Rs 10
Breakfast combo	Rs 90
Lunch	Rs 110
Dinner	Rs 150


Laundry Menu
Item	Price
Shorts	Rs 3
Trousers	Rs 4
Shirt	Rs 5
Jeans	Rs 6
Girlsuit	Rs 8


Recreation Menu
Activity	Price
Table tennis	Rs 60 per hour
Bowling	Rs 80 per hour
Snooker	Rs 70 per hour
Video games	Rs 90 per hour
Pool	Rs 50 per hour


Requirements
- Python 3 installed on your computer.
- A terminal or Python editor such as IDLE or Visual Studio Code.
No additional Python packages are required.
How to Run
1. Download or clone this repository.
2. Save the program as hotel_management.py.
3. Open a terminal in the project folder.
4. Run:
   python hotel_management.py
   If your system uses python3, run:
   python3 hotel_management.py
5. Follow the numbered menus:
   - Choose 1 to enter customer details.
   - Choose 2 to calculate room rent.
   - Choose 3 to add restaurant charges.
   - Choose 4 to add laundry charges.
   - Choose 5 to add game/recreation charges.
   - Choose 6 to display the bill.
   - Choose 7 to exit.
Billing Formula
Subtotal = Room rent + Restaurant bill + Laundry bill + Game bill
Grand total = Subtotal + Additional service charge
The current program applies a fixed additional service charge of Rs 1,800.
Project Structure
python-hotel-management-system/
├── hotel_management.py
├── README.md
├── hotel_management_source_code.txt
├── Python_Hotel_Management_System_Extended_Report_With_Code.pdf
└── Python_Hotel_Management_System_Extended_Report_With_Code_Editable.docx
The exact files in your repository may differ depending on what you choose to upload.
Limitations
- Customer and billing data are stored only in memory; they are not saved to a database or file.
- Check-in and check-out dates are accepted as text and are not validated.
- The number of nights is entered separately rather than calculated from dates.
- Room numbers are not linked to real room inventory or availability.
- Numeric inputs are not fully validated; entering text at a numeric prompt may cause an error.
- The same billing object is reused, so charges may carry over if the program is used for another customer without resetting it.
- The service charge is fixed at Rs 1,800.
Possible Future Improvements
- Add input validation and error handling.
- Reset billing totals for each new customer.
- Calculate nights automatically from validated dates.
- Manage room inventory and availability.
- Store customers and bills in SQLite or MySQL.
- Add payment status and payment methods.
- Generate printable or PDF invoices.
- Build a graphical interface using Tkinter.
Learning Outcomes
This project demonstrates:
- Python classes and objects
- Constructors and instance attributes
- Methods and modular program structure
- Conditional statements (if, elif, else)
- Loops (while)
- User input and console output
- Arithmetic and accumulating totals
Academic Project Information
- Project: Python Hotel Management System
- Course: BCA Data Science
- Semester: 3rd Semester
- University: Chandigarh University
Add your own name, roll number, project guide, and screenshots before submitting the project to your university.
License
This project was created for educational purposes. Add a license file if you intend to publish it for reuse by others.
