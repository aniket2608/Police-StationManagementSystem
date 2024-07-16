# Police-StationManagementSystem
The Police Station Management System in C++ is a comprehensive application designed to manage and maintain records of convicts efficiently. The system provides functionalities to log in, add, modify, display, delete, and list records of convicts, all implemented using object-oriented programming principles.

The system includes various structures and classes to handle different aspects of convict management. These include structures for date of arrest (date), crime details (court), physical descriptions (descp), and FIR details (police). The core functionality is encapsulated within the criminal class, which handles input, output, deletion, modification, and display of convict records.

The system starts with a login function that ensures only authorized personnel can access the system. Upon successful login, the main page is displayed, and users can choose from various options such as adding a new record, modifying an existing record, displaying a record, deleting a record, listing all records, or exiting the system.

The input function in the criminal class gathers comprehensive details about the convict, including personal information, court details, physical description, and police information. These details are then stored in a file named "Jail_Information.txt" for future reference.

The output function displays the convict's record in a well-organized manner, providing a clear and detailed view of all the stored information. The system also includes validation functions to ensure that inputs are in the correct format and adhere to the required constraints.

Overall, the Police Station Management System in C++ is a robust and user-friendly application that aids in the efficient management of convict records in a police station. It leverages file handling and class-based design to ensure data integrity and ease of use for the end-users.
