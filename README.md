React Native Calculator App
This is a simple calculator app built with React Native. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

Table of Contents
Getting Started
Prerequisites
Installation
Usage
Components and Styles
Contributing
License
Getting Started
Prerequisites
Make sure you have the following installed before running the app:

Node.js
npm
React Native CLI
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/react-native-calculator.git
Change into the project directory:

bash
Copy code
cd react-native-calculator
Install dependencies:

bash
Copy code
npm install
Run the app:

bash
Copy code
npx react-native run-android
or

bash
Copy code
npx react-native run-ios
Usage
Launch the app on your emulator or device.
Use the calculator to perform basic arithmetic operations.
Components and Styles
The app is structured into several components and styles:

App.js: The main component that sets up the theme context and renders the calculator interface.

GlobalStyles.tsx: Defines global styles used throughout the app, including styles for buttons and the calculator screen.

Colors.tsx: Contains color constants used for light and dark themes.

ThemeContext.tsx: Creates a context for managing the app's theme.

MyKeyboard.tsx: The calculator component that handles number input, operations, and result display.

Button.tsx: A reusable button component with theme-aware styling.

Contributing
Contributions are welcome! If you find any issues or have improvements, feel free to open a pull request.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
