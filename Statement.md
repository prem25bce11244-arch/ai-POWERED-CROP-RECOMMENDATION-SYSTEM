Project Statement

Problem statement

In many small-scale retail and educational environments, there is a need for a simple, resilient, and non-graphical system to manage inventory, simulate retail transactions, and practice core programming concepts like data structures (dictionaries, lists) and procedural logic. Existing e-commerce solutions are often too complex, requiring database setup and web deployment. This project addresses the need for a simplified, console-based solution.

Scope of the project

The project is strictly limited to a console-based, single-session simulation. It covers the end-to-end transaction flow: from viewing available products, adding items to a cart (with automatic stock deduction), applying a fixed discount coupon, to generating a final order summary and a text receipt.

Out of Scope:

User authentication/passwords.

Persistent data storage (inventory resets upon script termination).

Handling multiple concurrent users.

Graphical User Interface (GUI) or web deployment.

Complex tax or shipping calculations.

Target users

Students/Beginners in Python: Individuals learning core Python concepts, including functions, dictionaries, lists, loops, and basic I/O.

Small Retailers: Businesses needing a quick, simple tool for calculating orders and checking basic stock availability in a non-networked environment.

Educational Trainers: Instructors looking for a practical, self-contained example of system design to demonstrate concepts like stock management and data aggregation (Counter).

High-level features

Stock-Aware Cart System: Automatically checks and deducts stock when an item is added.

Bulk Cart Management: Allows users to add or remove multiple quantities of an item in a single command.

Order Summary Generation: Provides a clear, tabulated breakdown of items, unit prices, and subtotals during checkout.

Discount Logic: Implements a hardcoded coupon (SAVE10) f
