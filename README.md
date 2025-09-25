This is a MERN (MongoDB, Express, React, Node.js) stack application that demonstrates a robust and secure user authentication system. The project focuses on key principles of modern web security to protect user data.
-Key Features -
User Registration: Users can create an account with a unique email and password.
Secure Password Handling: We use Bcrypt, a powerful password-hashing library, to store passwords in the database. Bcrypt adds a salt to each password before hashing it, preventing common attacks like rainbow table lookups. This means we never store plain-text passwords, ensuring user data remains secure even if our database is compromised.
User Login: Existing users can securely log in using their credentials. The application verifies the password by hashing the user's input and comparing it to the stored hash, without ever revealing the original password.
Protected Routes: Certain parts of the application are accessible only to authenticated users, ensuring data privacy and a secure user experience.![Uploading Screenshot (78).png…]()
![Uploading Screenshot (77).png…]()
![Uploading Screenshot (76).png…]()
