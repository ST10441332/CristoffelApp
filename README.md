Restaurant Management App
This React Native application is designed for restaurant management, specifically for Christoffel's restaurant. It provides features for both customers and staff, including menu viewing and chef-specific functionalities.

Features
Home Screen: Welcomes users and provides navigation options.
Menu Viewing: Allows customers to view the restaurant's menu.
Chef Login: Secure login for kitchen staff.
Add Menu Items: Chefs can add new dishes to the menu.
Edit Menu Items: Functionality for modifying existing menu items (to be implemented).
Installation
Ensure you have Node.js and npm installed on your system.
Install React Native CLI globally:
npm install -g react-native-cli
Clone this repository:
git clone [repository-url]
Navigate to the project directory and install dependencies:
cd restaurant-management-app
npm install
Running the App
For iOS:
npx react-native run-ios
For Android:
npx react-native run-android
Dependencies
This project uses several key dependencies:

React Navigation
React Native Picker
React Native Elements (for UI components)
Ensure all dependencies are properly installed by running npm install in the project directory.

Project Structure
App.js: Main component and navigation setup
HomeScreen.js: Landing page of the app
Login.js: Chef login functionality
Menu.js: Customer-facing menu view
AddItem.js: Interface for adding new menu items
EditItem.js: Interface for editing existing menu items (to be implemented)

Changelog
[Unreleased]
Planned
Implement EditItem functionality for modifying existing menu items

Add user roles and permissions for different staff members

Integrate with a backend database for persistent storage


###Added

styling and css
filter system for menu

Added
AddItem screen for chefs to add new menu items
Functionality to display list of added menu items
Total cost calculation for added items
Changed
Improved styling across all screens for better user experience
Fixed
Navigation issues between Home and Login screens

Added
Basic Menu viewing capability for customers
Changed
Refactored navigation structure for better performance

Added
Chef Login functionality with basic authentication
Navigation between different screens using React Navigation
Implemented Home screen with welcome message and navigation buttons

Added
Set up React Native project structure
Implemented basic app skeleton with placeholder screens
Changed
Updated project dependencies to latest versions
Added
Initial project setup
Created project repository
Added README with basic project description
##[0.0]

refrences
The IIE.2024.Mobile App Scripting [MAST5112 Module Manual]. The Idnependent Instatute of Education: unpublished
React Native. 2024. [SourceCode].https://reactnative.dev [accessed October 6 2024].
NPM.2024. @react-native-picker/picker [source code] https://www.npmjs.com/package/@react-native-picker/picker [accessed October 7 2024]
