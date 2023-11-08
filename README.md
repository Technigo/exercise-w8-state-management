<h1 align="center">
  <a href="">
    <img src="./src/assets/state-management.svg" alt="Boiler Plate">
  </a>
</h1>

# React State Management Task Manager with Redux and useContext Exercise

For this weeks practice you will Create a simple task manager where tasks are managed using Redux and theme (dark/light mode) is managed using React useContext.

## Getting Started with the Project

### Dependency Installation & Startup Development Server:

Once forked and cloned, navigate to the project's root directory and this project uses npm (Node Package Manager) to manage its dependencies.

The command below is a combination of installing dependencies, opening up the project on VS Code and it will run a development server on your terminal.

```bash
npm i && code . && npm run dev
```

### Looking for some hints?

### Redux Installation

Redux isn't included in the boiler plate. You'll need to install it using `npm install redux react-redux`.

### State Management with Redux

Redux is a centralized state management library. You'll need to set up a Redux store to manage the application's tasks. Follow these steps:

- Create a store directory for your Redux store.

- Inside the store directory, create a tasksReducer.js file. Define a reducer function to manage the tasks state.

- Create an action file, such as taskActions.js, to define actions for adding, removing, and updating tasks.

- Configure your Redux store in a file, e.g., store.js, using createStore from Redux.

- Create action types for your task actions and use them in your reducer and action creators.

### Integrating Components

In your main `App.jsx`, integrate both the task manager and theme toggler. 
Ensure that the `ThemeProvider` wraps your entire application so that the theme context is accessible everywhere.

### Testing

Before pushing to GitHub, test your application thoroughly. Add tasks, remove them, and toggle the theme. Ensure everything works seamlessly.

### Committing and Pushing

Use `git add .` to stage your changes, followed by `git commit -m "Your commit message here"` to commit them.
Push your changes to the GitHub repository using `git push origin main`.
