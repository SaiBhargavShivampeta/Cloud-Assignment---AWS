**Project Overview:**
This project showcases a web application hosted on an AWS EC2 instance. The app includes features for user registration, login, and profile management. Additionally, it offers extra credit functionality, such as file uploads, word count calculation, and persistent storage of user data.

**Key Features:**

User Registration: Collects username, password, first name, last name, and email, storing the data securely in a SQLite3 database.

Login: Authenticates users by their username and password.

Profile: Displays user details (username, first name, last name, and email). If a file is uploaded, it shows the word count and provides a download link.

File Upload (Extra Credit): Users can upload text files, which are stored securely on the EC2 instance. The application calculates and displays the word count of uploaded files and retains file information between sessions.
