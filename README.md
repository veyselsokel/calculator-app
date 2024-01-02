

# React Native Calculator App

This is a simple calculator app built with React Native. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Components and Styles](#components-and-styles)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Make sure you have the following installed before running the app:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [React Native CLI](https://reactnative.dev/docs/environment-setup)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/react-native-calculator.git
   ```

2. Change into the project directory:

   ```bash
   cd react-native-calculator
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Run the app:

   ```bash
   npx react-native run-android
   ```

   or

   ```bash
   npx react-native run-ios
   ```

## Usage

- Launch the app on your emulator or device.
- Use the calculator to perform basic arithmetic operations.

## Components and Styles

The app is structured into several components and styles:

- **App.js**: The main component that sets up the theme context and renders the calculator interface.

- **GlobalStyles.tsx**: Defines global styles used throughout the app, including styles for buttons and the calculator screen.

- **Colors.tsx**: Contains color constants used for light and dark themes.

- **ThemeContext.tsx**: Creates a context for managing the app's theme.

- **MyKeyboard.tsx**: The calculator component that handles number input, operations, and result display.

- **Button.tsx**: A reusable button component with theme-aware styling.

## Contributing

Contributions are welcome! If you find any issues or have improvements, feel free to open a pull request.


