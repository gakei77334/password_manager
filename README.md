# Password Manager Application

This Python application uses tkinter for the graphical user interface (GUI) and JSON for data storage. It allows users to generate secure passwords, store them alongside their corresponding website and username, and search for previously saved credentials.

**Key Features:**
* Password Generator: Generates random passwords with a mix of letters (both uppercase and lowercase), numbers, and symbols.
* Save Passwords: Stores website URLs, usernames, and passwords securely in a JSON file (`data.json`).
* Search Functionality: Allows users to search for saved credentials based on the website URL.
* Clipboard Integration: Copies generated passwords to the clipboard for easy pasting into websites or other applications.

**Functionality Overview:**
* **Generate Password:** Clicking the "Generate Password" button creates a random password and displays it in the password entry field. The generated password is also copied to the clipboard.
* **Save:** Stores the current website URL, username, and password into `data.json`. Checks for empty fields and prompts the user to fill them.
* **Search:** Retrieves and displays stored username and password for a given website URL from `data.json`. Notifies if no data is found for the specified website.

**User Interface:**
* The application features a simple and intuitive UI with labeled entry boxes for website URL, username, and password.
* Buttons for generating passwords, saving entries, and searching for saved credentials are prominently displayed for easy access.
* Error messages ensure data integrity by prompting users to fill required fields and notifying when no saved data is found.

**Dependencies:**
* tkinter: Python's standard GUI library for creating graphical interfaces.
* json: Handles data storage and retrieval in JSON format.
* pyperclip: Enables copying generated passwords to the clipboard for quick use.

**Future Improvements:**
* Implement encryption for enhanced security of stored passwords.
* Enhance UI with additional features like editing and deleting stored credentials.
* Add password strength indicator for generated passwords.

**Technologies Used:**
* Python
* tkinter (GUI)
* JSON (data storage)
* pyperclip (clipboard operations)
