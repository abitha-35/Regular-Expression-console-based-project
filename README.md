# Regular-Expression-console-based-project

## Personal Information Input Validation Script

This Python script allows users to input their personal information in a structured and validated manner. The program prompts the user to enter their name, date of birth, email ID, and mobile number while ensuring that the input adheres to the correct format. If any input does not match the expected format, the user will be prompted to enter the information again.

### Features:
- **Name Input**: Validates that the name contains only alphabetic characters and spaces (using a regular expression).
- **Date of Birth Input**: Validates the date of birth in the format `DD-MM-YYYY` and converts it to a more readable format like `DD-Month-YYYY` (e.g., 08-April-1995).
- **Email Input**: Ensures the email is in the correct `username@gmail.com` format.
- **Mobile Number Input**: Validates the mobile number in the format `XXX-XXX-XXXX`, where `X` is a digit.

### How It Works:
1. **Name**: The user is asked to enter their name, which must only contain letters and spaces.
2. **Date of Birth**: The date of birth is entered in the format `DD-MM-YYYY`. The script then converts it into a more readable format, showing the month by its name (e.g., "08-April-1995").
3. **Email ID**: The email must match the pattern `username@gmail.com`.
4. **Mobile Number**: The mobile number must be in the format `XXX-XXX-XXXX`, and the script will strip the hyphens and store it as a continuous string of digits.

After successful input validation, the script prints the user’s details in a readable format.

### How to Use:
1. Clone the repository or download the Python script.
2. Run the script using Python (version 3.x recommended).
3. Follow the prompts to enter your information.
4. The script will print your validated personal details at the end.

### Dependencies:
- `re` (Python's built-in module for regular expressions)

This script helps ensure that user inputs are properly validated before being used in any system that requires personal details.
