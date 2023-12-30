# React Native Expo App - Stock Market Project

## Overview

This project involves the development of a React Native Expo app with features such as a login page, signup page, dashboard with stock information, and stock detail screens. The app uses Redux for state management and integrates with the IEX Cloud API to fetch stock data.

## Installation

### Prerequisites

- Node.js (v14.x or higher)
- npm
- Expo CLI

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/react-native-expo-chat.git
   cd react-native-expo-chat
    ```
2. **Install Dependencies**

    ```
    npm install
    ```
3. **Run the Expo App**

    ```
    npm start
    ```



# Features
### 1. Login Page
- Allows users to enter a username and password.
- Generates a random captcha for additional security.
- Validates credentials against predefined values.
### 2. Signup Page
- Provides a form for users to register with a unique username, email, and password.
- Validates form input and displays error messages.
- Saves user data using Redux or a dedicated API endpoint.
### 3. Dashboard
- Displays a list of most active stocks from IEX Cloud.
- Allows users to click on a stock card to navigate to the detailed stock information page.
### 4. Stock Detail Screen
- Fetches and displays detailed information about a selected stock.
- Uses interactive charts to visualize stock data.
### 5. Device Orientation Handling
- Utilizes the react-native-orientation library to handle device orientation changes.
- Supports portrait and landscape modes.
### 6. Redux Integration
- Manages state using Redux for login, signup, and stock data.
## Contributors
Harigaran B harigaran003@pec.edu
Feel free to contribute by forking the repository and submitting pull requests.
