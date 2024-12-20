# DuoDo - Task Management App

![Project Logo](assets/logo-sq.JPG)

DuoDo is a simple and effective task management application designed specifically for two users to collaborate seamlessly. It allows users to create, assign, and track tasks effortlessly.

## Features

- **Two-User Collaboration**: Built with a focus on collaboration between two users.
- **Task Creation and Assignment**: Easily create tasks and assign them to either user.
- **Real-time Updates**: Tasks and updates are synced in real-time.
- **Intuitive Interface**: A user-friendly design for an optimal user experience.
- **Progress Tracking**: Monitor task completion and progress.

## Technologies Used

- **Frontend**: Vue.js
- **Backend**: Firebase Functions (TypeScript)
- **Database**: Firebase Realtime Database / Firestore
- **Version Control**: GitHub

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/duodo.git
   cd duodo
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure Firebase:
   - Go to the Firebase Console.
   - Create a new project or use an existing one.
   - Set up Firestore Database and Firebase Functions.
   - Update the Firebase configuration in the project.

4. Start the development server:
   ```bash
   npm run serve
   ```

5. Deploy Firebase Functions:
   ```bash
   cd functions
   npm install
   firebase deploy --only functions
   ```

## Usage

1. Open the application in your browser.
2. Sign up or log in using your account.
3. Create a task and assign it to either user.
4. Track the progress of your tasks in real-time.

## Project Structure

```
DuoDo/
├── src/
│   ├── components/       # Reusable Vue components
│   ├── views/            # Application pages
│   ├── store/            # Vuex store for state management
│   ├── router/           # Vue Router configuration
│   └── App.vue           # Main Vue component
├── functions/            # Firebase Functions code
├── public/               # Static assets
├── package.json          # Project dependencies
└── README.md             # Project documentation
```

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your fork and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any questions or feedback, feel free to reach out to [your email or GitHub profile].
