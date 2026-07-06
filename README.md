# Password Generator Pro

A secure and customizable command-line Password Generator built with Python. This application generates strong passwords based on user preferences, evaluates password strength, and allows users to save generated passwords for future use.

---

## Features

- Generate secure passwords of any length
- Include uppercase letters
- Include lowercase letters
- Include numbers
- Include special characters
- Password strength analysis (Weak, Medium, Strong)
- Save generated passwords to a file
- User-friendly command-line interface
- Input validation and error handling

---

## Technologies Used

- Python 3
- random
- string

---

## Project Structure

```
password-generator/
│
├── main.py
├── passwords.txt
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/aryansrivastava26/password-generator.git
```

### Navigate to the project folder

```bash
cd password-generator
```

### Run the application

```bash
python3 main.py
```

---

## Example Output

```
=============================================
PASSWORD GENERATOR PRO
=============================================

1. Generate Password
2. Exit

Choose Option: 1

Password Length (minimum 4): 16

Include Uppercase? (y/n): y
Include Lowercase? (y/n): y
Include Numbers? (y/n): y
Include Symbols? (y/n): y

Generated Password
----------------------------------------
Q#7mLp@9X!2aWd$K
----------------------------------------
Strength: Strong

Save this password? (y/n): y

Password saved successfully!
```

---

## Future Improvements

- Generate multiple passwords at once
- View saved passwords
- Delete saved passwords
- Copy password to clipboard
- Password history management
- GUI version using Tkinter
- Web version using Flask
- Export passwords to CSV
- Password expiration reminders

---

## Learning Outcomes

This project demonstrates the use of:

- Functions
- Loops and conditional statements
- String manipulation
- Random password generation
- File handling
- Input validation
- Error handling
- Modular Python programming

---

## Author

**Aryan Srivastava**

GitHub:  
https://github.com/aryansrivastava26

LinkedIn:  
www.linkedin.com/in/aryan-srivastava-100670306

---

## License

This project is licensed under the MIT License.
