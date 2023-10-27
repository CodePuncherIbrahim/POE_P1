# Module Management App

The Module Management App is a Windows application designed to help users manage academic modules and track their study hours. It now includes user registration and login functionality with data storage in a database.

## Features

- **User Registration:** Users can register by providing their username and password. The app stores user data securely in a database.

- **User Login:** Registered users can log in using their credentials to access their personalized module and study hour data.

- **Add Modules:** Registered users can add new academic modules by entering their code, name, credits, and class hours per week.

- **Record Study Hours:** Track your study hours for each module by selecting the date and entering the number of hours worked. The app calculates the remaining self-study hours based on the module's credits and class hours per week.

- **Calculate Self-Study Hours:** Calculate the recommended self-study hours per week for each module based on the total credits and the number of weeks in the semester.

## Prerequisites

- Windows OS
- .NET Framework (Minimum version: X.X.X)
- SQL Server or another relational database management system

## Installation

1. Clone or download the repository to your local machine.

2. Set up a database for the app. You can use SQL Server or another relational database management system. Create a database and configure the connection string in the app's configuration.

3. Build and run the application using your preferred IDE or the .NET CLI.

## Usage
Launch the Module Management App.

User Registration:

Click the "Register" button.
Enter a unique username and a secure password.
Click "Register" to create your account. Your credentials will be securely stored in the database.
User Login:

After registration, click the "Log In" button.
Enter your username and password.
Click "Log In" to access your personalized module and study hour data.
Add Modules:

Click the "Add Module" button.
Enter the module code, name, credits, and class hours per week.
Click "Add" to add the module to your account.
Record Study Hours:

Select a module from the list.
Choose a date using the date picker.
Enter the number of hours worked.
Click "Record Hours" to track your study hours.
Calculate Self-Study Hours:

Select a start date for the semester using the date picker.
Enter the number of weeks in the semester.
Click "Calculate" to calculate the recommended self-study hours per week for each module.
The app will display the remaining self-study hours for each module based on the recorded study hours.

## Contributing
If you'd like to contribute to this project, please follow these steps:

Fork the repository.

Create a new branch for your feature or bug fix.

Make your changes and commit them with descriptive commit messages.

Push your branch to your forked repository.

Create a pull request to the main repository's main branch.

## License
This project is licensed.

## Contact
If you have any questions or feedback, feel free to contact the project maintainers:

Ibrahim

## Acknowledgments
Thanks to programming for the hard times
