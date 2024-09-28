# Contoso PetFriends App

Welcome to the **Contoso PetFriends App**, a C# console application designed to help manage and find new homes for abandoned pets. This application allows users to store pet information, ensure data completeness, and edit existing records with ease. The project demonstrates key programming concepts such as branching, looping, data validation, and user interaction through a command-line interface.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Code Structure](#code-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Manage Pet Information:** Add new pets, edit existing records, and display current pet information.
- **Data Validation:** Ensures that essential pet data (age, physical description, nickname, personality) is complete and valid.
- **Menu-Driven Interface:** A simple, text-based menu allows for intuitive navigation and interaction.
- **User Prompts:** Provides detailed prompts and error messages to guide the user in entering valid data.
- **C# Fundamentals:** Showcases the use of loops, conditionals, arrays, and switch statements.

## Getting Started
Follow these steps to run the Contoso PetFriends App on your local machine.

### Prerequisites
- **.NET SDK:** Ensure you have the .NET SDK installed. You can download it from [Microsoft's official website](https://dotnet.microsoft.com/download).

### Installation
**Clone the Repository:**
   ```bash
   git clone https://github.com/ryankerbyIT/ContosoPetFriendsApp.git
```
### Build The Application
```bash
dotnet build
```
### Run The Application
```bash
dotnet run
```
### Usage
After running the application, you will be presented with a menu of options:
* List All Pets: Displays information about all the pets currently stored.
* Add a New Animal: Prompts the user to enter information for a new pet.
* Ensure Data Completeness: Checks for missing age and physical description data, prompting the user for input if incomplete.
* Edit Nicknames and Personalities: Checks for missing nicknames and personality descriptions, allowing the user to update them.
* Edit an Animal's Age: Lets the user edit the age of an existing animal.
* Edit Personality Description: Allows editing of an animal's personality description.
* Display Cats by Characteristic: Filters and displays cats based on a specific characteristic.
* Display Dogs by Characteristic: Filters and displays dogs based on a specific characteristic.
* Exit: Ends the program.
### Example Usage
- When selecting option 4 to ensure nicknames and personality descriptions are complete, the application will:
- Prompt you to enter a nickname if it's missing.
- Ensure that you provide a valid input, repeating the prompt if left empty.
- Ask for a personality description if it's incomplete.
### Screenshots
Here's an example of how the menu looks when the application runs:
```sql
Welcome to the Contoso PetFriends app. Your main menu options are:
1. List all of our current pet information
2. Add a new animal friend to the ourAnimals array
3. Ensure animal ages and physical descriptions are complete
4. Ensure animal nicknames and personality descriptions are complete
5. Edit an animal’s age
6. Edit an animal’s personality description
7. Display all cats with a specified characteristic
8. Display all dogs with a specified characteristic
...
```
### Code Structure
The project is organized into the following key sections:
- Menu System: Provides a user-friendly interface for interacting with the application.
- Data Management: Handles adding, editing, and displaying pet information.
- Validation: Ensures that inputs (age, physical description, nickname, personality) meet the requirements.
- Storage: Uses a 2D array to store pet information during the application's runtime.
### Future Enhancements
Some possible improvements to consider for future versions:
- Persistent Storage: Save pet data to a file or database for use across multiple sessions.
- Advanced Search: Implement more detailed filtering and search capabilities.
- Graphical Interface: Create a GUI version of the app using a framework like WPF or WinForms.
- Unit Tests: Add automated tests to ensure the application's logic works as expected.
### Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:
* Fork the repository.
* Create a new branch for your feature:
```bash
git checkout -b feature-name
```
* Commit your changes:
```bash
git commit -m "Add new feature"
```
* Push to the branch:
```bash
git push origin feature-name
```
* Open a pull request describing your changes.
### License
This project is licensed under the MIT License. See the LICENSE file for more details.
