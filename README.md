
Sales Invoice Generator
Introduction
The Sales Invoice Generator is a simple Java Swing application designed to create, save, load, and manage sales invoices. It allows users to input item details, customer information, and generate invoices.

Class: Frame2
Fields
Menubar: A JMenuBar object for menu options.
filemenu: A JMenu object representing the "file" menu.
Openmenu, Savemenu, Loadmenu, Exitmenu: JMenuItem objects for specific file-related actions.
tableO: A JTable for displaying item details.
ta: A JTextArea for displaying and editing invoice content.
btn1, btn2, btn3, btn4: JButton objects triggering various actions.
text1, text2: JTextField objects for entering invoice date and customer name.
table: A JTable for displaying customer data and total.
tb: A JTextArea for displaying and editing invoice content.
Methods
Frame2(): Constructor initializes the GUI components.
main(String[] args): Entry point of the application.
actionPerformed(ActionEvent e): Handles user actions such as opening, saving, creating, deleting invoices.
Functionality
File Operations

Open: Reads and displays content from a selected file.
Save: Saves item details and customer data to a file.
Exit: Exits the application.
Invoice Operations

Create new invoice: Loads and displays content from a selected file for creating a new invoice.
Delete invoice: Clears the invoice content.
User Interface

Table Display: Uses JTable to display item details and customer data.
Text Areas: JTextArea components for displaying and editing invoice content.
Buttons: Various buttons for saving, canceling, creating, and deleting invoices.
Usage
Run the application.
Use the "file" menu to open, save, or exit.
Enter invoice date and customer name.
Use the buttons to perform specific actions.
Edit invoice content using text areas.
Notes
Ensure Java is installed on your machine to run the application.
This application is designed for basic sales invoice management and can be extended based on specific business needs.
Feel free to modify the code and add more features based on your requirements.
