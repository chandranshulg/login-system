# LOGIN SYSTEM WITH PASSWORD MANAGEMENT

## Overview
This Python script provides a command-line interface for managing user passwords. It includes functionality for user registration, authentication, and password changes, with built-in password policy validation. User data is stored in a file, and passwords are securely hashed using SHA-1.

## Features
- **Register Users:** Allows new users to register with a username and password, provided the password meets specified policy requirements.
- **Authenticate Users:** Verifies user credentials (username and password) against stored data.
- **Change Password:** Enables users to change their password if they provide the correct current password and meet the new password policy.

## Technologies Used
- **Python** - Programming language used for scripting.
- **`hashlib`** - Provides the SHA-1 hashing function for password security.
- **`re`** - Used for regular expression operations to enforce password policy.
- **`csv`** - Handles reading from and writing to the password storage file.
- **`Pathlib`** - For file path manipulations.

## Author
Chandranshu
