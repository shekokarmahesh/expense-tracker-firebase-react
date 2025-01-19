# Expense Tracker Firebase React

This is a finance/expense tracking application built with React and Firebase. The application allows users to track their expenses, categorize them, and view their spending habits over time.

## Features

- User authentication with Firebase
- Add, edit, and delete expenses
- Categorize expenses
- View expenses by category
- Monthly expense summary
- Responsive design

## Technologies Used

- React
- Firebase (Authentication, Firestore)
- React Router
- Material-UI

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- Firebase account

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/expense-tracker-firebase-react.git
    ```
2. Navigate to the project directory:
    ```sh
    cd expense-tracker-firebase-react
    ```
3. Install dependencies:
    ```sh
    npm install
    ```
4. Create a Firebase project and set up Firestore and Authentication.
5. Create a `.env` file in the root directory and add your Firebase configuration:
    ```env
    REACT_APP_FIREBASE_API_KEY=your_api_key
    REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
    REACT_APP_FIREBASE_PROJECT_ID=your_project_id
    REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
    REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
    REACT_APP_FIREBASE_APP_ID=your_app_id
    ```
6. Start the development server:
    ```sh
    npm start
    ```

## Usage

1. Register or log in with your Firebase account.
2. Add your expenses by clicking on the "Add Expense" button.
3. View and manage your expenses from the dashboard.
4. Filter expenses by category and view monthly summaries.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.



## Acknowledgements

- [React](https://reactjs.org/)
- [Firebase](https://firebase.google.com/)
- [Material-UI](https://material-ui.com/)
