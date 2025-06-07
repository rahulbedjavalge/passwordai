# Password AI - Generator & Security Analyzer

## Overview
Password AI is a web-based application designed to help users generate secure passwords and analyze the strength of existing passwords. It provides an intuitive interface for generating passwords with customizable options and offers insights into password security using AI-powered analysis.

## Features
- **Password Generator**: Create secure passwords with customizable length and character types.
- **Password Security Analyzer**: Analyze the strength of a password and get suggestions for improvement.
- **Copy to Clipboard**: Easily copy generated passwords to the clipboard.
- **Interactive UI**: Modern and responsive design with tabs for switching between generator and analyzer.

## File Structure
- `index.html`: Contains the entire code for the application, including HTML, CSS, and JavaScript.

## Sections

### 1. **HTML Structure**
The HTML file is divided into the following sections:
- **Header**: Displays the title and description of the application.
- **Tabs**: Allows users to switch between the Password Generator and Security Analyzer.
- **Content**: Contains the main functionality of the application.
  - **Password Generator**: Includes options for password length, character types, and a button to generate passwords.
  - **Password Analyzer**: Allows users to input a password and analyze its strength.

### 2. **CSS Styling**
The CSS is embedded within the `<style>` tag and provides:
- A modern, gradient-based background.
- Responsive design for various screen sizes.
- Styled components like buttons, sliders, and result boxes.

### 3. **JavaScript Functionality**
The JavaScript code is responsible for the interactive features:
- **Tab Switching**: `switchTab(tab)` function updates the active tab and content section.
- **Password Generator**: `generatePassword()` function generates a password based on user preferences.
- **Password Analyzer**: `analyzePassword()` function evaluates the strength of a given password.
- **Copy to Clipboard**: `copyToClipboard(elementId)` function copies text to the clipboard and provides feedback.
- **Password Analysis**: `getPasswordAnalysis(password)` function calculates the strength, entropy, and crack time of a password.
- **UI Updates**: Functions like `updateStrengthDisplay()` and `togglePasswordVisibility()` enhance user interaction.

## How to Use
1. Open the `index.html` file in a web browser.
2. Use the **Password Generator** tab to create a secure password:
   - Adjust the length and character type options.
   - Click "Generate Password" to see the result.
   - Copy the password using the "Copy" button.
3. Switch to the **Security Analyzer** tab to analyze a password:
   - Enter a password in the input field.
   - View the strength, entropy, and suggestions for improvement.

## Live Demo

You can access the live version of the application here: [Password AI Live Demo](https://passaitool.vercel.app/)

## Future Enhancements
- Add server-side validation for password analysis.
- Implement user authentication for saving password preferences.
- Provide downloadable reports for password analysis.

## License
This project is open-source and available under the MIT License.
