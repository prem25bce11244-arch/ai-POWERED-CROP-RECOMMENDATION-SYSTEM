# CSE-project
Project README

Project Title

Console Groceries: A Python Shopping Cart Simulator

Overview of the Project

This is a single-file application (shopping_cart.py) that runs directly in your terminal. It guides a user through the shopping process: logging in, browsing stock, adding items to a dynamic cart (with stock checks), and completing a checkout with stock updates and a final, saved receipt. It serves as an excellent, practical example for learning fundamental Python programming and data structure concepts.

Features

User Login: Simple name-based authentication for a personalized shopping experience.

Real-Time Stock Management: Inventory is automatically reduced when an item is added to the cart, preventing over-selling.

Bulk Cart Operations: Users can add or remove multiple units of a product efficiently in a single command.

Checkout & Summary: Generates a detailed frequency table of cart items and calculates the final total.

Coupon System: Accepts a hardcoded coupon (SAVE10) for a 10% discount on the total purchase.

Automated Receipt: Saves a full transaction record to a local file, receipt.txt, upon order confirmation.

Technologies/Tools Used

Tool

Purpose

Python 3

The core programming language.

random

Used for generating unique Order IDs and simulating delivery days.

datetime

Used for calculating estimated delivery dates.

collections.Counter

Crucial for aggregating and counting items in the cart for checkout summaries.

time

Used to simulate a short processing delay during the checkout finalization.

Steps to Install & Run the Project

Since this is a single, self-contained Python file, follow these steps to run the application:

Save the Code: Ensure the shopping_cart.py file is saved on your computer.

Open Terminal: Navigate to the directory where you saved the file.

Run the Script: Execute the file using the Python interpreter:

python shopping_cart.py


Follow Prompts: The application will immediately ask you for your name to begin.

Instructions for Testing

Test Stock Control: Try to add a quantity of an item that exceeds the current stock. The system must display a failure message.

Test Cart Removal: Add items, then use the remove option to take out a partial quantity. Verify that the correct quantity is removed from the cart and restored to the inventory.


Test Coupon Logic: Enter the SAVE10 code during checkout to confirm the 10% discount is applied to the final payable amount.

Verify Receipt: After a successful checkout, check the project directory for the generated receipt.txt file and confirm the content matches the final order summary.

Screenshots
<img width="1363" height="704" alt="Screenshot 2025-11-25 003745" src="https://github.com/user-attachments/assets/15e0ff4f-e6a6-4dd9-ab51-a87f57ec7bb5" />
<img width="1362" height="768" alt="Screenshot 2025-11-25 003801" src="https://github.com/user-attachments/assets/df2cfb8a-2318-427c-92f4-bb09b2b8fdcb" />
<img width="1375" height="732" alt="Screenshot 2025-11-25 003819" src="https://github.com/user-attachments/assets/3d421c7e-8952-4490-b26a-8295b971ac35" />
<img width="1365" height="661" alt="Screenshot 2025-11-25 003832" src="https://github.com/user-attachments/assets/b2bd6669-e530-4473-9314-183c394d9e1e" />
<img width="1371" height="715" alt="Screenshot 2025-11-25 003846" src="https://github.com/user-attachments/assets/a3a02bb2-b5ea-410f-bf59-9c6d5e2c5416" />
<img width="1373" height="656" alt="Screenshot 2025-11-25 003905" src="https://github.com/user-attachments/assets/9316c3a9-2190-49d7-b882-856457d1ceaa" />
<img width="1366" height="638" alt="Screenshot 2025-11-25 003916" src="https://github.com/user-attachments/assets/c6c5978b-9954-4a49-895e-87b2e02f40d0" />
<img width="1364" height="559" alt="Screenshot 2025-11-25 003926" src="https://github.com/user-attachments/assets/a5be9db0-67aa-426d-af99-65db744cba3d" />
<img width="1476" height="528" alt="Screenshot 2025-11-25 003938" src="https://github.com/user-attachments/assets/d91549a6-b80a-495b-99d6-ccd385a136b6" />
<img width="1446" height="444" alt="Screenshot 2025-11-25 003954" src="https://github.com/user-attachments/assets/a708af9a-aa7c-45cb-afdb-3c1d11b14604" />
<img width="1457" height="451" alt="Screenshot 2025-11-25 004014" src="https://github.com/user-attachments/assets/26c471f1-badb-4860-a9b5-283598a337f2" />
<img width="1452" height="475" alt="Screenshot 2025-11-25 004154" src="https://github.com/user-attachments/assets/d8f8ca82-4199-47d4-834b-271fc1cabb5d" />
<img width="1461" height="460" alt="Screenshot 2025-11-25 004209" src="https://github.com/user-attachments/assets/3caafdfe-0da2-4645-b6f9-e7ae3b2c55c0" />
<img width="1457" height="468" alt="Screenshot 2025-11-25 004227" src="https://github.com/user-attachments/assets/07d0c4f1-2373-46f1-95d4-74f3ffbe072d" />
<img width="1463" height="467" alt="Screenshot 2025-11-25 004246" src="https://github.com/user-attachments/assets/a087c75d-56b8-460c-a37f-13ea7e747a1f" />
<img width="1443" height="456" alt="Screenshot 2025-11-25 004256" src="https://github.com/user-attachments/assets/5e16da70-6dcb-41e2-ba48-57aa6d68d523" />
<img width="1464" height="458" alt="Screenshot 2025-11-25 004306" src="https://github.com/user-attachments/assets/8ad91fe5-3f15-48a8-ab7b-1b8edc7f349a" />
<img width="1460" height="465" alt="Screenshot 2025-11-25 004315" src="https://github.com/user-attachments/assets/c1ed104d-d53a-4c06-a9dd-454065c919c6" />
<img width="1435" height="420" alt="Screenshot 2025-11-25 004325" src="https://github.com/user-attachments/assets/7a6a12f8-8222-40ad-94f1-1c490b1792b2" />
