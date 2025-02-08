
#Features
Secure Password Storage: Encrypts and stores user passwords securely in memory.
Password Retrieval: Allows users to retrieve stored passwords dynamically.
Dynamic Password Management: Enables users to add, update, and delete stored passwords.
Static Page Serving: Serves multiple static HTML pages for features like account management, settings, and password tips.
Error Handling: Displays error messages for invalid operations or missing pages.
Project Structure
The server uses several HttpHandler classes for different routes:

PasswordStoreHandler: Handles the secure storage of user passwords.
PasswordRetrieveHandler: Facilitates secure retrieval of stored passwords.
PasswordManagementHandler: Manages addition, deletion, and updating of passwords.
PageHandler: Generic handler for serving static HTML pages.
