# Redux Todo App - Lab 6

## Student Information
- **Name:** April Paz
- **Student ID:** N01327224
- **Course:** CPAN 213
- **Lab:** Lab 6 - Implementing Redux State Management
- **Date:** October 15, 2025

## Project Description
This todo application demonstrates Redux state management implementation in React Native using Redux Toolkit. The app shows how to manage global state for a simple todo application with filtering capabilities.

## Features Implemented
- Redux store setup with Redux Toolkit
- Todo slice with actions and reducers
- Add, toggle, and delete todos
- Filter todos (all, active, completed)
- Real-time todo statistics
- Connected React Native components using hooks

## Technologies Used
- React Native
- Redux Toolkit
- React-Redux
- React Native Vector Icons

## Installation
1. Clone the repository
2. Install dependencies: `npm install`
3. Install Redux packages: `npm install @reduxjs/toolkit react-redux react-native-vector-icons`
4. Run on Android: `npx react-native run-android`
5. Run on iOS: `npx react-native run-ios`

## Project Structure
```
ReduxTodoApp/
├── App.tsx
├── src/
│   ├── store/
│   │   ├── index.js          # Redux store configuration
│   │   └── todosSlice.js     # Todos slice with actions
│   └── screens/
│       └── TodoListScreen.js # Main todo list component
```

## Redux Implementation
- **Store:** Configured using Redux Toolkit with todos reducer
- **Actions:** addTodo, toggleTodo, deleteTodo, setFilter
- **State:** Manages todo items array and current filter
- **Components:** Connected using useSelector and useDispatch hooks

## Testing Completed
-  Add new todos functionality
-  Toggle todo completion status
-  Delete todos with confirmation
-  Filter functionality (all/active/completed)
-  State updates and component re-renders

## Challenges Faced
- Setting up Redux DevTools for debugging
- Proper state selection in components
- Icon implementation and linking

## Learning Outcomes
- Understanding Redux state management flow
- Implementing Redux Toolkit in React Native
- Connecting components to Redux store
- Managing application state predictably