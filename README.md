# KeyGuardian

KeyGuardian is a simple PowerShell-based password management application with a graphical user interface (GUI). It allows users to generate secure passwords, customize password options, and push generated passwords to a clipboard or external application.

## Features

- **Password Length Slider:** Adjust the length of the generated password using a slider control.
- **Password Options:** Customize your passwords with options for uppercase letters, lowercase letters, numbers, and special characters.
- **Password Push:** Quickly push generated passwords to the clipboard or an external application.
- **Logging:** KeyGuardian logs all activities to a text file for reference.
- **Export Logs:** Export log files to a location of your choice.
- **About Page:** Learn more about the application and its version.

## Getting Started

### Prerequisites

- Windows OS
- PowerShell

  1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/KeyGuardian.git
   Open the project in PowerShell.

Run the KeyGuardian script:
.\KeyGuardian.ps1


Usage
Password Length: Adjust the length of the password using the slider. The length is displayed in the adjacent textbox.

Password Options: Select the character types you want in your password (uppercase, lowercase, numbers, special characters).

Generate Password: Click the "Generate Password" button to create a random password based on your settings.

Password Push: Click the "Push Password" button to copy the generated password to the clipboard or an external application.

Reset Form: Click the "Reset Form" button to clear the form and start over.

Export Logs: In the "File" menu, you can export log files to a location of your choice.

About: In the "Help" menu, you can find information about the application's version and author.

Logs
KeyGuardian logs all activities to a text file located at C:\Users\Public\Keyguardian_log.txt. You can export log files to a different location using the "File" menu.

Contributing
Contributions are welcome! If you have any suggestions, feature requests, or bug reports, please create an issue or pull request on the GitHub repository.

License
This project is licensed under the MIT License - see the LICENSE file for details.

