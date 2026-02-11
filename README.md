This project is a Java-based console application developed using JDBC and Oracle Database. The system is designed to manage pet adoption processes and maintain medical records of pets in an organized manner. 
It allows users to add new pets, view pet details, update medical status, adopt pets, cancel adoptions, and remove pets from the system.
The application follows a layered architecture using packages such as bean (model classes), dao (database operations), service (business logic), util (database connection and custom exceptions), and app (main class).
JDBC is used to connect Java with Oracle XE Database.

Two main tables are used in the database: PET_TBL to store pet details and ADOPTION_TBL to store adoption records. 
A sequence is used to generate unique adoption IDs. Custom exceptions are implemented to handle cases like invalid input, pet not available for adoption, and active adoption restrictions.
This project demonstrates the implementation of CRUD operations, database connectivity, exception handling, and layered architecture using Core Java and JDBC.

Structure : <img width="397" height="518" alt="image" src="https://github.com/user-attachments/assets/f994aad7-2076-47d2-bc64-7ac753d09e63" />

output: <img width="1425" height="888" alt="image" src="https://github.com/user-attachments/assets/a6da5e66-e819-4c27-af03-25b5d5390f7f" />

