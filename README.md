# Random Password Generator

This project is a graphical user interface (GUI) application built with Tkinter to generate random passwords. It allows users to specify the strength and length of the password and includes options to copy and reset the generated password.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)

## Introduction

Creating secure passwords is essential for protecting online accounts and personal information. The Random Password Generator is designed to help users easily generate strong, random passwords tailored to their specific needs. Whether you need a simple password for a less critical account or a complex one for high-security requirements, this tool provides the flexibility to create passwords of varying strengths and lengths. With a user-friendly interface, you can generate, copy, and manage passwords efficiently.

## Features

- **Password Strength Options**: Choose between weak, medium, and strong password strengths.
  - **Weak**: Lowercase and uppercase letters only.
  - **Medium**: Lowercase, uppercase letters, and digits.
  - **Strong**: Lowercase, uppercase letters, digits, and special characters.
- **Customizable Length**: Select the length of the password between 8 and 18 characters.
- **Copy to Clipboard**: Easily copy the generated password to the clipboard.
- **Reset Functionality**: Reset the selections and password field.

## Installation

To run this application, you need to have Python installed on your system. Additionally, you need to install the `pyperclip` module.

1. **Install Python**: Download and install Python from [python.org](https://www.python.org/).
2. **Install Pyperclip**: Open a terminal or command prompt and run the following command:
   ```bash
   pip install pyperclip

## Usage

1. **Run the Application**:
   - Save the provided code in a file, for example, `password_generator.py`.
   - Open a terminal or command prompt and navigate to the directory where the file is saved.
   - Run the application using Python:
     ```bash
     python password_generator.py
     ```

2. **Generate Password**:
   - A GUI window will open.
   - **Select the desired strength of the password**:
     - **Weak**: Select the "weak" radio button. This includes lowercase and uppercase letters only.
     - **Medium**: Select the "medium" radio button. This includes lowercase and uppercase letters, and digits.
     - **Strong**: Select the "strong" radio button. This includes lowercase and uppercase letters, digits, and special characters.
   - **Choose the length of the password**:
     - Use the spinbox to select a password length between 8 and 18 characters.
   - **Generate the password**:
     - Click the "Generate" button to create the password. The generated password will appear in the text field below the button.

3. **Copy Password**:
   - Once a password is generated and displayed in the text field, you can copy it to the clipboard.
   - Click the "Copy Password" button. The password will be copied to your clipboard, and you can paste it wherever needed.

4. **Reset**:
   - If you want to clear the current selections and generated password, you can reset the application.
   - Click the "Reset" button to clear the selections and the password field. The application will be ready for generating a new password with default settings.

### Example

Here is a step-by-step example of using the application:

1. Run the application:
   ```bash
   python password_generator.py
2. Choose a length of 12 characters.
3. Click the "Generate" button. A 12-character strong password will appear in the text field.
4. Click "Copy Password" to copy the generated password to the clipboard.

To generate a new password, click "Reset" and repeat the steps above.

## Contributors
| Sr No. | Name               |  git-profile     | 
| -------| -------------------| -----------------| 
| 1.     | Saniya Sonawane    |  saniyass0123    | 
